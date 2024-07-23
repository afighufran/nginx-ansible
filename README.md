# nginx-ansible
simple ansible project for learning how to use ansible with simple use case

how to use:
`ansible-playbook -i inventory.ini playbook.yml` for install nginx

`ansible-playbook -i inventory.ini helloworld.yml` for ping checking

inventory set to localhost, so you can use it on local machine (if you dont have a virtual machine/cloud server)
