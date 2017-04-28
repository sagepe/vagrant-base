Vagrant.configure(2) do |config|
  config.vm.define "trusty", autostart: false do |trusty|
    config.ssh.insert_key = false
    config.vm.provider "virtualbox" do |v|
      v.name = 'vagrant-base-trusty'
    end
    trusty.vm.box = 'ubuntu/trusty64'
    trusty.vm.hostname = 'trusty'
  end
  config.vm.define "xenial", autostart: false do |xenial|
    config.ssh.insert_key = false
    config.vm.provider "virtualbox" do |v|
      v.name = 'vagrant-base-xenial'
    end
    xenial.vm.box = 'ubuntu/xenial64'
    xenial.vm.hostname = 'xenial'
  end
  config.vm.define "wheezy", autostart: false do |wheezy|
    config.ssh.insert_key = false
    config.vm.provider "virtualbox" do |v|
      v.name = 'vagrant-base-wheezy'
    end
    wheezy.vm.box = 'debian/wheezy64'
    wheezy.vm.hostname = 'wheezy'
  end
  config.vm.define "jessie", autostart: false do |jessie|
    config.ssh.insert_key = false
    config.vm.provider "virtualbox" do |v|
      v.name = 'vagrant-base-jessie'
    end
    jessie.vm.box = 'debian/jessie64'
    jessie.vm.hostname = 'jessie'
  end
  config.vm.define "centos6", autostart: false do |centos6|
    config.ssh.insert_key = false
    config.vm.provider "virtualbox" do |v|
      v.name = 'vagrant-base-centos6'
    end
    centos6.vm.box = 'centos/6'
    centos6.vm.hostname = 'centos6'
  end
  config.vm.define "centos7", autostart: false do |centos7|
    config.ssh.insert_key = false
    config.vm.provider "virtualbox" do |v|
      v.name = 'vagrant-base-centos7'
    end
    centos7.vm.box = 'centos/7'
    centos7.vm.hostname = 'centos7'
  end
end
