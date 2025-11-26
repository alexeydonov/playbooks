# Ansible playbooks

## Prerequisites

```bash
sudo apt install ansible
```

## init-debian

```bash
sudo ansible-pull -U https://github.com/alexeydonov/playbooks.git -C main -i localhost, init-debian.yml
```

## user-config

```bash
ansible-pull -U https://github.com/alexeydonov/playbooks.git -C main -i localhost, user-config.yml
```
