## Directory Summary

**Name:** Matienzo, John Edward Sam T.

## Requirements

- Ansible - installed in Alpine.
- SSH - installed and configured in both Alpine and Ubuntu machines.
- Pre-requisite packages - installed using the playbook.

## Goals

- Create a playbook that installs and configures nagios in both Ubuntu and Centos.

## Directory Structure

```
README.md
ansible.cfg
inventory
playbook_availability.yaml
roles/
	install_nagios_centos/
			defualts/
				main.yml
			files/
			handlers/
				main.yml
			meta/
				main.yml
			tasks/
				main.yml
			templates/
			tests/
				inventory
				test.yml
			vars/
				main.yml
			README.md
	install_nagios_ubuntu/
			defaults/
				main.yml
			files/
			handlers/
				main.yml
			meta/
				main.yml
			tasks/
				main.yml
			templates/
			tests/
				inventory
				test.yml
			vars/
				main.yml
			README.md
````
