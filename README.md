# bruce
Brew services manager

## Usage
`bruce [-h|-l] {load|unload|reload} servicename`

```bash
# list of available brew services 
$ bruce -l
dnsmasq
httpd22
mongodb
mysql
php56
postgresql
redis
```

```bash
# manage service
$ bruce load php56
$ bruce reload php56
$ bruce unload php56
```
