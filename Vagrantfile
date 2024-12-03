Vagrant.configure("2") do |config|
    config.vm.box = "bento/ubuntu-22.04"
    config.vm.hostname = 'sonarqube'
    config.vm.network 'forwarded_port', guest: 9000, host: 9000, host_ip: '127.0.0.1'
    config.vm.provision 'shell', path: 'provision.sh'
    config.vm.provider 'virtualbox' do |v|
        v.memory = 1024
    end
end