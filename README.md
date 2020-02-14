3 tier application deployment via Ansible
1.	Installing and configure Nginx. 
2.	Installing PostgreSQL, creating DB, user for DB, and password for user.
3.	Installing simple Python application which serve "Hello World!".

DIRECTORY STRUCTURE
-------------------

      HelloWorld.py       Python app for installing on server via Ansible
      hosts               inventory file for Ansible
      nginx.conf.tpl      template for nginx configuration
      playbook.yml        playbook for deployment via Ansible

RUNNING
-------------------
$ ansible-playbook -i hosts playbook.yml -b
