
Vagrant.configure("2") do |c|
  c.vm.box = "ubuntu/trusty32""
  c.vm.synced_folder ".", "/vagrant", disabled: true
  c.vm.provider :virtualbox do |p|
    p.customize ["modifyvm", :id, "--memory", "128"]
    p.gui = true
  end
end
