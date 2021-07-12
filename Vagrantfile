
Vagrant.configure("2") do |config|
 
  config.vm.box = "ubuntu/xenial64"

  #config.vm.network "forwarded_port", guest: 80, host: 80
  config.vm.network "private_network", ip: "192.168.10.100"
  #config.vm.hostname = "www.brittany.local"
  config.hostsupdater.aliases = ["development.local"]

 
end
