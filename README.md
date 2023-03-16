# Ansible role: msteams

Installs [msteams](https://maven.apache.org).

## Requirements

None

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

None.

## Example Playbook
```
- hosts: servers
  roles:
    - { role: adrianjuhl.msteams }

or

- hosts: servers
  tasks:
    - name: Install msteams
      include_role:
        name: adrianjuhl.msteams
```

To install a particular version:

```
- hosts: servers
  tasks:
    - name: Install msteams
      include_role:
        name: adrianjuhl.msteams
      vars:
        adrianjuhl__msteams__version: 1.5.00.23861
```

## License

MIT

## Author Information

[Adrian Juhl](http://github.com/adrianjuhl)
