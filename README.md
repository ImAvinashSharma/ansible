# ansible
```
ansible all --key-file ~/.ssh/ansible -i inventory -m pinga# ansible

become root user
ansible all -m apt -a update_cache=true --become --ask-become-pass

to downlode
ansible all -m apt -a name=vim-nox --become --ask-become-pass

run playbook
ansible-playbook --ask-become-pass install_apache.yml
```