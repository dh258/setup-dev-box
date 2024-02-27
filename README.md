# Ansible Playbook for Dev Setup

This repository contains an Ansible Playbook for setting up your development environment.

## Prerequisites

Before you begin, ensure you have met the following requirements:

* You have installed the latest version of Ansible.
* You have a `<Linux/Mac>` machine. Windows systems are not currently supported.

## Installing Ansible Roles

This playbook requires certain Ansible roles to be installed. You can install these roles using the `ansible-galaxy` command. Run the following command to install the necessary roles:

```bash
ansible-galaxy role install buluma.git gantsign.oh-my-zsh geerlingguy.docker markosamuli.asdf
```

## Using Ansible Playbook

To use the Ansible Playbook, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the directory containing the playbook.

    ```bash
    cd <directory>
    ```

3. Run the playbook using the following command:

    ```bash
    ansible-playbook -i inventory.yml playbook.yml
    ```
