# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant::Config.run do |config|
  config.vm.box = "base"
  config.vm.network :bridged, :bridge => "vagrant"
  config.vm.provision :puppet_server do |puppet|
    puppet.puppet_server = "puppet.lugons.org"
  end
end
