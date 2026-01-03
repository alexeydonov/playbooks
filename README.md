# Ansible playbooks

## Debian

### Prerequisites

```bash
sudo apt install ansible git
```

### system

```bash
sudo ansible pull --url https://github.com/alexeydonov/playbooks.git debian/system.yml
```

### user

```bash
ansible pull --url https://github.com/alexeydonov/playbooks.git debian/user.yml
```

For prompt colors use:

```bash
ansible pull --url https://github.com/alexeydonov/playbooks.git debian/user.yml -e prompt=PRESET
```

Available presets:

- `green` (default)
- `magenta`
- `orange`
- `yellow`

## macOS

### Prerequisites

```zsh
sudo port install ansible git
```

### Ports

```zsh
sudo ansible pull --url https://github.com/alexeydonov/playbooks.git macos/ports.yml
```

### user

```zsh
ansible pull --url https://github.com/alexeydonov.net/playbooks.git macos/user.yml
```
