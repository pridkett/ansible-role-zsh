ansible-role-zsh
================

A simple role to install and manage zsh

Requirements
------------

There are no specific additional reqiurements.

Role Variables
--------------

* `set_default_shell`
  * Type: Boolean
  * Usage: If `true`, sets fish as the default shell for `ansible_user`.
  * Default: `false`

Dependencies
------------

There are no specific additional dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: local
  roles:
    - pridkett.zsh
  vars:
    zsh:
      set_default_shell: false
```

License
-------

MIT

Author Information
------------------

Patrick Wagstrom &lt;patrick@wagstrom.net&gt;

- [Personal Home Page](https://patrick.wagstrom.net/)
- [GitHub Profile Page](https://github.com/pridkett/)
