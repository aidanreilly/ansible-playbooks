Master is set up with Python, boto, etc installed and configured as standard. AWS keys added to the machine using export. 

Then, I created a ~/HOSTS file with the following:

    [local]
    localhost

    [webserver]

Using vi, I added a create-instances.yml playbook and run it as follows:

    ansible-playbook create-instances.yml

