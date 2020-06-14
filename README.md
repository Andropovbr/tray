# Lista de comandos e pacotes instalados para a avaliação para o cargo de Analista de Infraestrutura II

#-----------------------------------

#Atualizar pacotes após instalação do Ubuntu Server 18
sudo apt-get update
sudo apt-get upgrade

#Instalação do Ansible
sudo apt-get install ansible

#Criação no home do usuário ubuntu o arquivo "ansible.cfg"
nano ansible.cfg

#Criação do arquivo de hosts, contendo o endereço do webserver e configuração de autenticação por chave
nano hosts

#Criação do playbook para atualização do Ubuntu
nano ubuntu_update.yml

#Criação do playbook para instalação e configuração do Apache com PHP no servidor web
nano apache.yml

#Criação do template para a configuração do site padrão do Apache
mkdir templates
nano templates/apache-default.j2

#-----------------------------------

#Lista de softwares/pacotes instalados
Ansible 2.5.1
Apache 2.4.29
PHP 7.2

#-----------------------------------
