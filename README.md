# Ansible playbooks

## Debian

### Prerequisites

```bash
sudo apt install ansible git
```

### system

```bash
sudo ansible-pull --url https://github.com/alexeydonov/playbooks.git debian/system.yml
```

### user

```bash
ansible-pull --url https://github.com/alexeydonov/playbooks.git debian/user.yml
```
