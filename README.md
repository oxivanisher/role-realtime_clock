realtime_clock
==============
[![Ansible Lint](https://github.com/oxivanisher/role-realtime_clock/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-realtime_clock/actions/workflows/ansible-lint.yml)

Configure the realtime hwclock to `local`, so that Windows and Linux won't fight over the time on daylight saving changes on dual boot systems. ... Thanks Microsoft. -.-

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Configure realtime clock
  hosts: desktops
  roles:
    - role: oxivanisher.linux_base.realtime_clock
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_base](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_base/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_base).
