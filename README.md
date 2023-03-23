# Running

Ativa o reload do daemon
```
systemctl daemon-reload
```

É preciso que o arquivo do service esteja em: */etc/systemd/system*
```
systemctl start teste.service
```

Ativa para rodar no boot
```
systemctl enable teste.service
```

Verifica log somente dessa aplicacao (-b => last boot)
```
journalctl -b -u teste.service
```
