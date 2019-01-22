# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
VAGRANT_API_VERSION = "2"

Vagrant.configure(VAGRANT_API_VERSION) do |config|

config.ssh.insert_key = false

config.vm.define "vagrant1" do |vagrant1|
  vagrant1.vm.box = "bento/ubuntu-18.04"
  config.vm.synced_folder "/yandex/ubuntu-configs", "/mnt/yandex"
end

end
