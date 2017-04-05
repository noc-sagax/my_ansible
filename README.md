### my_ansible
My personal Ansible repository

  * Dynamic inventory

`AWS_PROFILE=zenoss_sagax ansible -i ec2.py -u centos eu-west-1 -m ping --private-key ~/.ssh/ivan.pem`
