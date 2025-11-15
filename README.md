
```markdown
# Ansible Playbook: Docker Installation & Setup

A clean and efficient Ansible playbook for installing and configuring Docker Engine on Linux servers. Ideal for quick setups, testing, or automating Docker provisioning.

## Features
- Installs latest Docker CE packages
- Enables & starts Docker service
- Optionally adds users to the `docker` group
- Supports common Linux distributions

## Getting Started
1. Clone the repo:
```bash
git clone https://github.com/arunprakash432/ansible-docker-installation-and-configuration.git
cd ansible-docker-installation-and-configuration
````

2. Add your hosts to `inventory.ini`.

3. Run the playbook:

```bash
ansible-playbook -i inventory.ini site.yaml --ask-become-pass
```

## Structure

```
site.yaml         # main playbook
inventory.ini     # hosts list
ansible.cfg       # optional ansible configuration
```

## Requirements

* Ansible 2.9+
* Python on remote hosts
* SSH + sudo access

## Thank you!


