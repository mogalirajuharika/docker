# _*_ mode: ruby _*_
# vi: set ft=ruby :
Vagrant.configure("2") do |config|
config.vm.define "server" do |server|
	config.vm.box = "ubuntu/trusty64"
	config.vm.network "private_network", ip: "192.168.56.90"
	config.vm.hostname = "server"
	
config.vm.define "client" do |client|
	client.vm.box = "centos/7"
	client.vm.network "private_network", ip: "192.168.56.10"
	clinet.vm.hostname = "client"
	
end
end
end
