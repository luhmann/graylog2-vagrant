# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "graylog2"
  config.vm.box_url = "https://www.dropbox.com/s/23gupgb0xompvkm/Wheezy64.box?dl=1"

  config.vm.provision :puppet do |puppet|
    puppet.manifest_file = "graylog2.pp"
    puppet.module_path = "modules"
  end

  config.vm.network :forwarded_port, guest: 9000, host: 9000
  config.vm.network :forwarded_port, guest: 12201, host: 12201

end
