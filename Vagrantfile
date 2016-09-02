Vagrant.configure(2) do |config|
  config.vm.define "webserver" do |webserver|
      webserver.vm.box = "ubuntu/trusty64"
          webserver.vm.network "private_network", ip: "198.162.2.201"
	      webserver.vm.hostname = "webserver"
	        end
config.vm.define "ansible" do |ansible|
ansible.vm.box = "ubuntu/trusty64"
ansible.vm.network "private_network", ip: "198.162.2.202"
ansible.vm.hostname = "ansible"
end
end
