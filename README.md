start vm:

     vagrant up

run playbook:

     ansible-playbook --private-key .vagrant/machines/default/virtualbox/private_key -u vagrant -i 192.168.33.10, sonar.yml
