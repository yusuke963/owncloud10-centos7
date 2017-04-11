# owncloud9.x-centos7
Install ownCloud9.x on CentOS7.x

#Requirements
Ansible 1.4 or higher and platform.

#System Requirements
CentOS7.x Minimal Install

#How to install
(1) yum install -y git epel-release
(2) yum makecache
(3) yum install -y ansible git
(4) git clone [GitHub URL]
(5) cd ansible-edi-rhel7/
(6) ansible-playbook -i host install.yml -vvv 

#構文チェック 
ansible-playbook install.yml --syntax-check 

#dry-run 
ansible-playbook -i host install.yml --check
