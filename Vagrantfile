
Vagrant.configure("2") do |config|
#### change to file to show ssh working
  # configures the VM settings
  config.vm.box = "ubuntu/xenial64"
  config.vm.network "private_network", ip:"192.168.10.100"

  # provision the VM to have Nginx
  config.vm.provision "shell", path: "provision.sh"


end
