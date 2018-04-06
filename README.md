# ansible
# devops
## Create automation enviroment network AWS.

![it-pedrops](/aws/infrastructure/vpc-itlabs%20V2.png?raw=true)

### Pre-req
      1. Ansible instalado 
      2. AWS Cli API 
      3. Conta na AWS

### SETUP enviroment AWS

   ###### resources created for role "vpc" in ansible/playbooks/roles/vpc/tasks/main.yml

      - 1 VPC  
      #Create security group
      - 4 subnets
      - 2 NAT-GW
      - 2 EIP

  for execute script in format fit:
  `ansible-playbook playbook.yml -i inventory -e @vars.yml -vvv`

---
