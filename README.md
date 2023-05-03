# Ansible Role: Update OS

This Ansible role updates the operating system for Debian, Ubuntu, RedHat, CentOS, SLES, and openSUSE distributions.

## Requirements

- Ansible 2.9 or higher
- Target hosts should be running one of the supported Linux distributions

## Usage

1. Clone this repository to your local machine:

```bash
$ git clone git@github.com:HYUEHFJKhfjklkej/ansible.git
ansible-playbook -i /ansible_roles/update_os/inventory.ini /ansible_roles/update_os/update_os_playbook.yml