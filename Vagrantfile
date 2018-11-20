
Vagrant.configure("2") do |c|
  c.vm.box = "senglin/win-10-enterprise-vs2015community"
  c.vm.synced_folder ".", "/vagrant", disabled: true
  c.vm.provider :virtualbox do |p|
    p.customize ["modifyvm", :id, "--memory", "128"]
    p.gui = true
  end
end
