Vagrant.configure("2") do |config|
 config.vm.box = "centos/7"
 config.vm.network "forwarded_port", guest: 80, host: 8080
 config.vm.provision "ansible" do |ansible|
   ansible.playbook = "site.yml"
 end
end
