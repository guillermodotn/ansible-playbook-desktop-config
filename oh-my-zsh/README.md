Role Name
=========

Installs ZSH shell allongside Oh-my-zsh and the following plugins:
- zsh-autosuggestions
- zsh-history-substring-search
- zsh-syntax-highlighting

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

### prompt_theme
Oh-my-zsh theme to enable

### plugins_repos
Dictionaries list that stores the plugins to be installed with zsh in the following format:

    plugins_repos:
      - url: <url_to_repo>
        repo: <repo_name>
      - url: <url_to_repo>
        repo: <repo_name>


Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: username.rolename
          vars:
            prompt_theme: gentoo

License
-------

BSD

Author Information
------------------

Guillermo-N