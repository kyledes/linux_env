# linux_env
yum install ansible

sudo ansible-playbook linux_env.yml --extra-vars "target_password=<pass> target_user=<user>"
