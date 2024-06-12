lxml
======

Installs and configures lxml for the user.

Requirements
------------

To include this role in your `requirements.yml` file, add the following list item:

```yaml
---
roles:
  - name: whalej84.lxml
    src: https://github.com/WhaleJ84/ansible-role-lxml.git
    scm: git
```

Example Playbook
----------------

This example playbook shows how I would use this role, with custom variables to suit my needs.

```yaml
---
- hosts: localhost

  roles:
    - role: whalej84.lxml
      tags: [ lxml ]
```

