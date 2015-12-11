# ansible-docker-mongodb-backup
Backup MongoDB docker container

## Install backup scripts

	ansible-playbook -i hosts playbook.yml -t setup 

## Backup manually

	ansible-playbook -i hosts playbook.yml -t backup


*Based on [ssilab/ansible-mongodb](https://github.com/ssilab/ansible-mongodb)*
