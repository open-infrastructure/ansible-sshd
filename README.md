# SSHD

Configures the SSH daemon.

## Example playbook
```yaml
- hosts: all
  roles:
    - sshd
```

## Configuration
See `default/main.yml` and `man sshd` for a list of config options.
Defaults where chosen to get an A+ score on [sshaudit](https://www.sshaudit.com).
An ascii art banner is installed by default.
