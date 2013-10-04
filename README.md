Basil Provisioning
==============================

Getting Ansible
------------
``` bash
sudo add-apt-repository ppa:rquillo/ansible
sudo apt-get install ansible
```

Local provisioning of node and npm global dependencies
------------
``` bash
$ cd local
$ ansible-playbook -i local playbook.yml
```

Vagrant provisioning
------------
``` bash
$ cd vagrant/snake
$ vagrant up
```

Remote provisioning
------------
``` bash
$ cd vagrant/snake
$ ansible-playbook -i development-hosts development.yml
```