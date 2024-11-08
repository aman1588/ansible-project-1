# Learning Ansible with a project
I've made a working project to deploy a simple Nginx webserver form the Controller node to the Manager node.
>project-1 

***Just to check the networking***
```
ansible -i inventory.ini -m shell -a "echo hello" all -v
```
