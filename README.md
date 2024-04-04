Role Name
=========

Template for role building

Requirements
------------

None but basic usage of ansible

Role Variables
--------------
```
    in_dict_all_<role_name_with_underscores> : /inventory/group_vars/all.yml
    in_dict_group_<role_name_with_underscores> : /inventory/group_vars/mygroup/main.yml (one group in inventory)
    in_dict_host_<role_name_with_underscores> : /inventory/host_vars/myhost/main.yml
    in_dict_vault_<role_name_with_underscores> : /inventory/(host_vars|group_vars)/(myhost|mygroup)/vault.yml
```
Dependencies
------------

none

Example Playbook
----------------

included into the role : {{ role_path }}/playbooks/00-blob.yml

License
-------

BSD

Author Information
------------------

I'm a poor lonesome cowboy !

