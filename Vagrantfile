Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-22.04" 
  config.vm.box_download_options = {"ssl-no-revoke" => true}
  config.vm.box_download_insecure = true
  #config.vm.boot_timeout = 60000
  config.vm.network "public_network", ip:"192.168.4.222"
  config.vm.provider "virtualbox" do |vb|
     vb.memory = "5000"
	 vb.cpus = "2"
   end
end