start vm:

     vagrant up

run playbook:

     ansible-playbook --private-key .vagrant/machines/default/virtualbox/private_key -u vagrant -i 192.168.33.10, sonar.yml

Sonar should be running at http://192.168.33.10:9000/
