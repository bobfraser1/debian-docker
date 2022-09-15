VAGRANT_BOX = 'generic/debian11'
VM_HOSTNAME = 'debian1'
VM_MEMORY = '2048'
VM_CPUS = '2'

Vagrant.configure('2') do |config|
  config.vm.box = VAGRANT_BOX
  config.vm.hostname = VM_HOSTNAME
  config.vm.provider 'virtualbox' do |vm|
    vm.name = VM_HOSTNAME
    vm.memory = VM_MEMORY
    vm.cpus = VM_CPUS
  end
  config.vm.provision 'docker' do |d|
  end
end
