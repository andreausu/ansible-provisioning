Basil Provisioning
==============================

Getting Ansible (Ubuntu)
------------
``` bash
$ sudo add-apt-repository ppa:rquillo/ansible
$ sudo apt-get install ansible
```

Getting Ansible (Mac OS X)
------------
``` bash
$ brew install ansible
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