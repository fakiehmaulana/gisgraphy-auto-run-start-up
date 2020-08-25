### Gisgraphy auto run when start up os

* set Gisgrapgy As Service centos 7
### Installation
```sh
$ cp gisgraphy.service /etc/systemd/system/
$ systemctl daemon-reload
$ systemctl enable gisgraphy.service
$ systemctl start gisgraphy.service
```

* set Gisgrapgy As Service ubuntu
### Installation
```sh
$ ./setGisgrapgyAsService.sh
```



