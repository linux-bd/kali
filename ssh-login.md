## ssh remote login
```sh
leafpad /etc/ssh/sshd_config
```
## Change Line according to this
```sh
PermitRootLogin yes
```
## Restart ssh service
```sh
sudo service ssh restart
```
