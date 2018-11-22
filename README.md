install-gitlab
=========

Role do Ansible para instalação de um servidor GitLab CE.

Distribuições Suportadas pela Role
------------

- Debian
- RedHat ou CentOS


Tags da Role 
--------------

- deps: Instala as dependências do GitLab CE.
- script: Baixa e executa o script de instalaçaõ do repositório do GitLab CE.
- gitlab: Realiza a instalação do pacote do GitLab CE.
- config: Realiza a configuração de pós instalação do GitLab CE.
  

Variáveis da Role
--------------


Examplos de Playbook
----------------

Exemplo de uso da Role:

    - hosts: servers
      roles:
         - install-gitlab

License
-------

BSD
