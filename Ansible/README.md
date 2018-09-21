# OpenShift
yum install ansible, git -y

/etc/ansible/hosts: localhost ansible_connection=local

ansible-playbook oc_cluster_up.yml
