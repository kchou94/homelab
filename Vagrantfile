# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
    # Base VM OS configuration.
  config.vm.box = "debian/bookworm64"
    # config.ssh.insert_key = false
    # config.vm.synced_folder '.', '/vagrant', disabled: true

    # General VirtualBox VM configuration.
    # config.vm.provider :virtualbox do |v|
    #     v.memory = 1024
    #     v.cpus = 1
    #     v.linked_clone = true
    #     v.customize ["modifyvm", :id, "--natdnshostresolver1", "on"]
    #     v.customize ["modifyvm", :id, "--ioapic", "on"]
    # end

    # Prometheus.
    # config.vm.define "prometheus" do |prometheus|
    #     prometheus.vm.hostname = "prometheus.test"
    #     prometheus.vm.network :private_network, ip: "192.168.56.2"
    # end

#   config.vm.provision "ansible" do |ansible|
#     ansible.playbook = "test.yml"
#     ansible.become = true
#   end
end