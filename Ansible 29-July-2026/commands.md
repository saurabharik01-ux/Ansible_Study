
to install ansible in debian based system 

sudo apt-get install ansible


Note - main.yml is the actual file name you can replace this with your actual yml file name

To Run Any File 

ansible-playbook main.yml

To Run Any Files With Sudo/Become Privillages 

ansible-playbook --ask-become-pass main.yml

