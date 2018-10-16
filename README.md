# provisioning
Ansible based provisioning of infrastructure on AWS and GCP to host private projects.

All sensitive data contained on my own personal PC in encrypted files.
ansible vault file, pem keys, vars file pointing to AWS images, security groups, etc.


Setting up environment: 
  vault password file in /etc/ansible/.vault_pass
  aws pem key at: /etc/ansible/ssh_keys/aws.pem
  encrypted variables file at: /etc/ansible/group_vars/private.yml
