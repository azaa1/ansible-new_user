# new_user

This repo contains 2 playbooks 

1. ping.yml             -- a simple playbook to ping remote hosts
2. add-user.yml         -- this playbook will add a new user to reomte host/hosts

add-user.yml playbook is set to take user's input for:

    - hosts             -- which hosts to run the playbook on 
    - username          -- 'username' for the new user
    - fullname          -- 'full name' of the user
    - uid               -- 'uid' for the user
    - group             -- 'group" to which the user should be added
    - password          -- 'password' for the new user (it will be encrypted)
    
