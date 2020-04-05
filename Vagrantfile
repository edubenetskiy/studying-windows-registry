# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.define 'windows' do |it|
    it.vm.box = "mwrock/Windows2012R2"
    it.vm.communicator = 'winrm'
    it.vm.provision 'script', type: 'shell', path: 'provision.ps1'
  end
end
