# nginx-ansible
simple ansible project for learning how to use ansible with simple use case

how to use:

`ansible-playbook -i inventory.ini nginx_start.yml` for install nginx, and start the service

`ansible-playbook -i inventory.ini nginx_status.yml` for checking nginx status

`ansible-playbook -i inventory.ini nginx_stop.yml` for stop the nginx service

`ansible-playbook -i inventory.ini helloworld.yml` for ping checking

inventory set to localhost, so you can use it on local machine (if you dont have a virtual machine/cloud server)
