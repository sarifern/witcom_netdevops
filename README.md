# NETDEVOPS DEMO FOR WITCOM 2020

## Authors: 
- Sari Fernandez sarifern@cisco.com
- Alfonso Sandoval alfsando@cisco.com

## Link to Demo video
To be updated

## Using the code

1. Update the inventory file to hit devices in your network. The current inventory uses devices in a Cisco Sandbox.
2. Install the requirements.yml file:
``` 
ansible-galaxy collection install -r requirements.yml
```
3. Run any playbooks:
``` 
ansible-playbook playbook/<name of playbook>.yml
```

a. Docker images for TIG stack (no tls and tls) can be found here:
https://hub.docker.com/repository/docker/sarifern/tig-stack-tls