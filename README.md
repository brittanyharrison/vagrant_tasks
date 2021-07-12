# Vagrant Task

## Launch Nginx 
Nginx (pronounced as “Engine-X”) is an open source web server that is often used as reverse proxy or HTTP cache. 

To install Nginx, use the following commad:

```
sudo apt update
sudo apt install nginx
```

To see nginx in browser we need to connect using private ip uisng the below config settings. 
```
config.vm.network "private_network", ip: "192.168.10.100"
```

To update hostname install plugin: 

```
vagrant plugin install vagrant-hostsupdater

```

Now you can choose hostname using:
```
#config.vm.hostname = "www.brittany.local"
config.hostsupdater.aliases = ["development.local"]
```

```
systemctl status NAME
```