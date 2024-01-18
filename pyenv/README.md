Role Name
=========

Role designed to install pyenv for the remote user running the playbook

Requirements
------------

OS for the intallation must be one of the following families:
- Debian
- RedHat
- Suse
- Alpine

Role Variables
--------------

- **os_packages**: Dictionary with the packages to install as dependencies for pyenv
- **pyenv_path_lines**: Block of text to add to the .bashrc or .zshrc

Dependencies
------------

N/A

Example Playbook
----------------

Simple role, no need nothing else besides calling it.

    - hosts: servers
      roles:
         - pyenv

License
-------

BSD

Author Information
------------------

Guillermo-N
