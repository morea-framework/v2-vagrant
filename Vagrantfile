Vagrant.configure("2") do |config|

  config.vm.box = "morea-framework/basic-box"
  config.vm.network :forwarded_port, host: 4000, guest: 4000
  config.ssh.forward_agent = true

end