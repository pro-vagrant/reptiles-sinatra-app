VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box = "http://argon.kul.lublin.pl/gajdaw/sinatra-v0.1.2.box"

  config.vm.provider "virtualbox" do |v|
    v.memory = 1024
  end

  config.vm.network :forwarded_port, guest: 4567, host: 8880
end
