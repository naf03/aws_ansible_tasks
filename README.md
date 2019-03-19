# aws_ansible_tasks
Ansible playbooks for automating AWS resources

The playbook security_group.yml can be used to create a security group with security rules. In addition, you can also use it
to append new security rules to the security group. 

The "purge_rules" parameter is set to false to not purge existing rules on the security group. 

Before running the playbook, you need to populate your AWS keys in group_vars/all

You can run the playbook by issuing ansible-playbook -i inventory/hosts security_group.yml
