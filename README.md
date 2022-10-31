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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: igr33k.setup_working_environment, user_name: hacker, user_pass: changeme, key_url: "http://github.com/hacker.keys" }
