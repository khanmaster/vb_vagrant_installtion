

Vagrant.configure("2") do |config|

  config.vm.provider "virtualbox" do |v|
    v.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
    v.customize ["modifyvm", :id, "--natdnsproxy1", "on"]
  end

 config.vm.box = "ubuntu/xenial64"
# creating a virtual machine ubuntu 

 config.vm.network "private_network", ip: "192.168.10.100"
# creating a private ip to access our nginx server on the web from inside the VM

# redirect the above to the specific web address
 config.hostsupdater.aliases = ["development.local"]


end
