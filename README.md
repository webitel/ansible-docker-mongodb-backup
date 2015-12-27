# ansible-docker-mongodb-backup
Backup MongoDB docker container

## Install backup scripts

	ansible-playbook -i hosts playbook.yml -t setup -u root

## Backup manually

	ansible-playbook -i hosts playbook.yml -t backup -u root


*Based on [ssilab/ansible-mongodb](https://github.com/ssilab/ansible-mongodb)*
