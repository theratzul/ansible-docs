ansible --list-hosts all  
sudo vi /etc/ansible/hosts  
sudo vi /etc/ansible/ansible.cfg  
cat dev  
[webserver]  
localhost  ansible_connection=local

ansible -i dev --list-hosts all  
    hosts (1):  
    localhost  

└──╼ $cat ansible.cfg  
[defaults]  
inventory = ./dev  
┌─[bogdan@parrot]─[~/ansible-bog]  
└──╼ $ansible --list-hosts all  
  hosts (1):  
    localhost  
