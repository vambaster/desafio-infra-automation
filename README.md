
## Objetivo
Instalar e configurar Docjker em 10 servidores linux

Versao do ansible utilizado - Ansible 2.16.10
## Instruções

### Parte 1: Executar ansible
1. Executar o seguinte comando:

ansible-playbook playbook.yaml -i hosts

Ao executar o comando acima, sera instalado os pacotes de atualizacao do yum, pacote docker, dependencias, instalacao do docker e iniciar o servico nos 10 servidores configurados em hosts.

O arquivo hosts esta configurado com os 10 servidores.

