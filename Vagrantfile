# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  # Every Vagrant virtual environment requires a box to build off of.
  config.vm.box = "windowsIE9"
  config.vm.boot_timeout = 100
  config.vm.box_url = "http://aka.ms/vagrant-win7-ie9"

   config.vm.provider "virtualbox" do |vb|
  #   # Don't boot with headless mode
     vb.gui = true
   end

end
