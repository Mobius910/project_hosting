# Firewall Fighters Ansible

This is the Firewall Fighters Ansible Master Node on our hosting platform.

## Usage

```bash

ansible-playbook playbooks/playbook.yml -f inventory/hosts

## Structure

my-ansible-project/
├── .gitignore
├── README.md
├── ansible.cfg
├── inventory/
│   └── hosts
├── playbooks/
│   └── site.yml
├── group_vars/
│   └── all.yml
├── host_vars/
│   └── myhost.yml
└── roles/
    └── example_role/
        ├── defaults/
        │   └── main.yml
        ├── files/
        ├── handlers/
        │   └── main.yml
        ├── meta/
        │   └── main.yml
        ├── tasks/
        │   └── main.yml
        ├── templates/
        └── vars/
            └── main.yml
