# owncloud10-centos7.x
Install ownCloud10 on CentOS7.x

#Requirements
Ansible 1.4 or higher and platform.

#System Requirements
CentOS7.x Minimal Install

#How to install<br>
(1) yum install -y git epel-release<br>
(2) yum makecache<br>
(3) yum install -y ansible git<br>
(4) git clone [GitHub URL]<br>
(5) cd ansible-edi-rhel7/<br>
(6) ansible-playbook -i host install.yml -vvv <br>

#構文チェック <br>
ansible-playbook install.yml --syntax-check <br>

#dry-run <br>
ansible-playbook -i host install.yml --check <br>
