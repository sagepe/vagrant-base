Vagrant.configure(2) do |config|
  config.vm.define "trusty", autostart: false do |trusty|
    trusty.vm.box = 'ubuntu/trusty64'
    trusty.vm.hostname = 'trusty'
  end
  config.vm.define "xenial", autostart: false do |xenial|
    xenial.vm.box = 'ubuntu/xenial64'
    xenial.vm.hostname = 'xenial'
  end
  config.vm.define "wheezy", autostart: false do |wheezy|
    wheezy.vm.box = 'debian/wheezy64'
    wheezy.vm.hostname = 'wheezy'
  end
  config.vm.define "jessie", autostart: false do |jessie|
    jessie.vm.box = 'debian/jessie64'
    jessie.vm.hostname = 'jessie'
  end
  config.vm.define "centos6", autostart: false do |centos6|
    centos6.vm.box = 'centos/6'
    centos6.vm.hostname = 'centos6'
  end
  config.vm.define "centos7", autostart: false do |centos7|
    centos7.vm.box = 'centos/7'
    centos7.vm.hostname = 'centos7'
  end
end
