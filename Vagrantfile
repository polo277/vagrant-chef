Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu"

  config.vm.provision "shell", path: "script.sh"
  config.vm.provision :chef_solo do |chef|
	chef.add_recipe "nodejs"
  end
end
