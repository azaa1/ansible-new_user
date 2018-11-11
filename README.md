# new_user

This playbook adds a new user to remote hosts

The playbook is set to take user's input for:

    - hosts             -- which hosts to run the playbook on 
    - username          -- 'username' for the new user
    - fullname          -- 'full name' of the user
    - uid               -- 'uid' for the user
    - group             -- 'group" to which the user should be added
    - password          -- 'password' for the new user (it will be encrypted)
    
