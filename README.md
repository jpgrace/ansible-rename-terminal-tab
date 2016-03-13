ansible-rename-terminal-tab
===========================

An Ansible role to rename the terminal tab in Ubuntu. Having multiple terminal tabs open at once, it can be a pain to remember which box I'm ssh'ed into on each tab. This gives me a way to quickly see where I need to go next.

Requirements
------------

This role is meant to work with Ubuntu. It has only ever been used on version 14.04, but may work on other versions as well.

Role Variables
--------------

There is only one variable:

```
tab_name: Hi!
```

Dependencies
------------

There are no dependencies

Example Playbook
----------------

Here's a quick example use.

    - hosts: servers
      roles:
         - role: rename-terminal-tab
           tab_name: example.com

License
-------

BSD

Author Information
------------------

[JP Grace](https://github.com/jpgrace)
