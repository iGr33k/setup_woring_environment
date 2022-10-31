Role Name
=========

Install some software and configs for personal confort

Role Variables
--------------

user_name: hacker  
user_pass: changeme  
key_url: "http://github.com/username.keys"  

Example Playbook
----------------

```YAML
- hosts: servers
  roles:
      - { role: igr33k.setup_working_environment, user_name: hacker, user_pass: changeme, key_url: "http://github.com/hacker.keys" }
```