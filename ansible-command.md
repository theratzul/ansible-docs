ansible --list-hosts all  
sudo vi /etc/ansible/hosts  
sudo vi /etc/ansible/ansible.cfg  
cat dev  
[webserver]  
localhost  

ansible -i dev --list-hosts all  
    hosts (1):  
    localhost  
