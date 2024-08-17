Criar 3 Vms
- Ansible para instalação
- Wordpress para instalação
- Mysql para instalação


Para pegar as chaves criptografadas da base de dados

https://api.wordpress.org/secret-key/1.1/salt/ 


Você pode executar as tarefas do Ansible do playbook "provisioning.yml"
    ansible-playbook provisioning.yml -i hosts -K

inserir a senha do sudo.
