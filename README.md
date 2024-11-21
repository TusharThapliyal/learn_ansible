# learn_ansible
## ad_hoc commands
ansible all -m <module> -a "<args for this module> --become --ask-become-pass"  
## executing playbook
ansible-playbook --ask-become-pass <path to playbook>  


- in command ''ansible all -m'' , all means all hosts in inventory. you can just use webserver or webserver[1] to point to one host
