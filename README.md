#Ansible-ABS:#

---  

###*Main goal:*###
* This document describes the work-flow of Ansible-ABS project.   

---  

###*Folder structure:*###

    .  
    ..  
    ├── ansible.cfg  
    ├── hosts  
    └── roles  
    	├── abs  
        │   └── tasks  
        └── test-server  
            └── tasks  
                ├── dev_agent_provisioning.yml  
                ├── aptInstallation.yml  
                └── command_test.yml  
    
---  

###*commands examples:*###

**ping all agents:**  
ansible -m ping all -u builder  

**ping build_agents:**  
ansible -m ping build_agents -u builder  

**ping (Lior's) test_server:**  
ansible -m ping test_server -u builder  
  
----  

