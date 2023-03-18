# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
	config.vm.define "web-server" do |wb|
	wb.vm.hostname = "web-server"
 	 wb.vm.box = "ubuntu/focal64"
	wb.vm.network "private_network", ip: "192.168.33.20"
end
   	config.vm.provider "virtualbox" do |vb|
 
    	vb.memory = "1024"
  end




end
