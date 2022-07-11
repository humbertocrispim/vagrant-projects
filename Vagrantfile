# -*- mode: ruby -*-
# vi: set ft=ruby :

#

Vagrant.configure("2") do |config|
  config.vm.define "asenble-vm" do |vm1|
    vm1.vm.hostname = "asenble-vm"
    vm1.vm.box = "ubuntu/focal64"
    vm1.vm.network "private_network", ip: "192.168.56.30"
    vm1.vm.provider "virtualbox" do |vb|
      vb.name = "asenble-vm"
      vb.gui = false
      vb.memory = "1024"
      vb.cpus = "2"
    end
  end


  config.vm.define "machina01-vm" do |vm2|
    vm2.vm.hostname = "machine01-vm"
    vm2.vm.box = "ubuntu/focal64"
    vm2.vm.network "private_network", ip: "192.168.56.31"
    vm2.vm.provider "virtualbox" do |vb|
      vb.name = "machine01-vm"
      vb.gui = false
      vb.memory = "502"
      vb.cpus = "2"
    end
  end


  config.vm.define "machina02-vm" do |vm3|
    vm3.vm.hostname = "machine02-vm"
    vm3.vm.box = "centos/7"
    vm3.vm.network "private_network", ip: "192.168.56.32"
    vm3.vm.provider "virtualbox" do |vb|
      vb.name = "machine02-vm"
      vb.gui = false
      vb.memory = "502"
      vb.cpus = "2"
    end
  end
end

#ok