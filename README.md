install-gitlab
=========

Role do Ansible para instalação de um servidor GitLab CE.

Distribuições Suportadas pela Role
------------

- Debian 9 ou superior
- RedHat ou CentOS 7 ou inferior


Tags da Role 
--------------

- main: Tag a ser utilizada em conjunto com outras tags, se alguma tag for especificada no comando.
- deps: Instala as dependências do GitLab CE.
- script: Baixa e executa o script de instalaçaõ do repositório do GitLab CE.
- gitlab: Realiza a instalação do pacote do GitLab CE.
- config: Realiza a configuração de pós instalação do GitLab CE.
  

Variáveis da Role
--------------


Exemplos de Playbook
----------------

Exemplo de uso da Role:

    - hosts: servers
      roles:
         - install-gitlab

Exemplo de Comandos
----------------

Comando para executar todas as tasks:

    ansible-playbook -i <caminho_inventario> <caminho_playbook>

Comando para executar a tag "config" (em caso de uso de tags, a tag "main" é obrigatória):

    ansible-playbook -i <caminho_inventario> <caminho_playbook> --tags "main, config"


License
-------

MIT License