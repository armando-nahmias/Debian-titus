# Debian-Data-Science
Debian customizations for Data Science

Primeiro, baixe a imagem ISO do endereço: <https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/weekly-builds/amd64/iso-cd/>
Não utilize a versão EDU.

Mudar a lista de fontes para o debian sid

    cp /etc/apt/sources.list /etc/apt/sources.list.bak
    cp sources.list /etc/apt/sources.list 


Disable Root Login in Linux with passwd Command

To disable the root login, you can use the passwd command as below:

    sudo passwd -l root

This will lock the password for the root user and you won’t be able to access the root account with its password until a new one is set.

Install git

    sudo apt install git


Clonar o repositório a ser usado

    git clone https://github.com/armando-nahmias/Debian-Data-Science/

Se precisar fazer alterações no repositório, será necessário configurar o git

git config –global user.email "email"
git config –global user.name "nome"


