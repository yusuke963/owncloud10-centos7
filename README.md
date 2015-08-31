#Install owncloud8-centos6.7-memcache
Requirements
ownCloud8 on CentOS6.7

Ansible 1.4 or higher and platform.
System Requirements

CentOS6.x Minimal Install
How to install Ansible

(1) yum install -y git epel-release
(2) yum makecache
(3) yum install -y ansible git
(4) git clone [GitHub URL]
(5) ansible-playbook -i host install.yml
