# Ansible Role: Ngrok

This role will deal with the setup and the config of ngrok

It's part of the Manala <a href="http://www.manala.io" target="_blank">Ansible stack</a> but can be used as a stand alone component.

## Requirements

A debian repository with ngrok package (such as manala one).

## Installation

### Ansible 2+

Using ansible galaxy cli:

```bash
ansible-galaxy install manala.ngrok,2.0
```

Using ansible galaxy requirements file:

```yaml
- src:     manala.ngrok
  version: 2.0
```

## Role Handlers

None

## Role Variables

### Definition

| Name                           | Default  | Type   | Description     |
| ------------------------------ | -------- | ------ | --------------- |

### Example

```yaml
- hosts: all
  roles:
    - role: manala.ngrok
```

# Licence

MIT

# Author information

Manala [**(http://www.manala.io/)**](http://www.manala.io)