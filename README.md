AnsiblePathogen
=========

Install pathogen and plugins.

Example Playbook
----------------
``` yml
    - hosts: all
      roles:
        - role: ansible_pathogen
          pathogen_plugins:
            - repo: "https://github.com/elixir-lang/vim-elixir.git"
              name: some_name ## default: vim-elixir
              version: some_tag ## default: master
```
