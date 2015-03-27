Vagrant.configure("2") do |config|
  config.vm.box      = "centos7"
  config.vm.box_url  = "centos.box"
  config.vm.hostname = "devbox"
  config.vm.box_check_update = false
  config.vm.provider :"VirtualBox"
  config.vm.network  :public_network
  #config.vm.network  :private_network, ip: "192.168.56.10"
  config.ssh.username = "root"
  config.ssh.password = "vagrant"
  
  config.vm.provider "virtualbox" do |v|
    v.memory = 2048
    v.cpus = 2
  end
  #config.vm.synced_folder "D:/", "/workspace"
  
end