VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
	config.vm.box = "heroku"
 	config.vm.box_url = "https://dl.dropboxusercontent.com/s/rnc0p8zl91borei/heroku.box"
 	config.vm.provision :shell, path: "bootstrap.sh"
 	config.vm.network :forwarded_port, guest: 4567, host: 4567
end