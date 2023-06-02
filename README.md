# ansible
Ansible Repository zum Testen auf ansiblemaster.vreden.home


Start 27.05.2023


ansible all -m gather_facts --limit rockyansible.vreden.home -bK --become-method su | grep ansible_distribution | ohne sudo

ansible all -m gather_facts --limit raspberrypi.vreden.home -bK | grep ansible_distribution

ssh-copy-id -i /.ssh/id_rsa.pub torsten@mywebserver.vreden.home


raspberrypi.vreden.home.