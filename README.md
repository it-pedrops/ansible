# ansible
# devops
## Criando automação de criação do ambiente de network na AWS.
![it-pedrops](/ansible/master/aws/infrastructure/vpc-itlabs%20V2.png?raw=true)

### Pré-requisitos
      1. Ansible instalado 
      2. AWS Cli API 
      3. Conta na AWS

### SETUP do ambiente AWS

   ###### Recursos criado pela role "vpc" in ansible/playbooks/roles/vpc/tasks/main.yml

      - 1 VPC  
      #Create security group
      - 4 subnets
      - 2 NAT-GW
      - 2 EIP

  Para executar o script no formato que está no git:
  `ansible-playbook playbook.yml -i inventory -e @vars.yml -vvv`
#Adicionando uma pasta do cloud-formation para as stacks
---
