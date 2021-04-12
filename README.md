# dnsbob-pc-account-config-ansible
Configure new computer account for my use - various settings and apps - using Ansible

account-config.yml - calls playbook common.yml  

common.yml - calls roles:  
-  common-apps  
-  dot-ssh-setup  

common-apps  
-  installs a long list of apps  

dot-ss-setup  
-  set up ssh configuration  
