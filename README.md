Syncthing
=========

This Ansible role installs Syncthing using the system's package repositories. Syncthing is an open-source file synchronization tool that allows you to sync files between devices securely.

Requirements
------------

- Ansible 2.9 or higher. 
- Debian or Debian based distribution.

Role Variables
--------------

```shell
syncthing_version: '1.28.0'
syncthing_user: 'syncthing'
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```shell
- hosts: servers
  become: true
  roles:
    - role: syncthing
      syncthing_version: '1.28.0'
      syncthing_user: 'syncthing'
```

License
-------

GNU

Author Information
------------------

This role was created in 2024 by Raif Coonjah