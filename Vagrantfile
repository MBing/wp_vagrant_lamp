Vagrant.configure("2") do |config|
    config.vm.box = "Ubuntu1204LTS"
    config.vm.box_url = "http://files.vagrantup.com/precise64.box"
    config.vm.network :hostonly, "192.168.0.10"
    config.ssh.forward_agent = true
    config.vm.provider "Ubuntu1204LTS" do |vb|
        config.vm.customize ["modifyvm", :id, "--cpuexecutioncap", "90"]
    end
end
