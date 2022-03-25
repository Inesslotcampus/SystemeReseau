# Système Réseau

SSH (Secure Shell) est un protocole de communication sécurisé qui permet de se connecter à un ordinateur distant de façon sécurisée, au sein d’un réseau potentiellement non sécurisé comme Internet.

## Autentification

Dans git bash 

- ssh ines_slotwinski@51.15.252.63
- yes 
- mdp

## Commandes

 - cp: copier le fichier => cp fichier1.txt fichier2.txt
-  mv: bouge ou renome un fichier =>mv ancien_nom.txt nouveau_nom.txt
=> mv /tmp/fichier1.txt /home/plv/
-  cat: affiche le contenu d’un fichier => mv ancien_nom.txt nouveau_nom.txt

 - nano/vim : permet de créer un fichier ou de modifier un fichier existant => nano fichier.txt
 - RTFM : read the fucking manual
 - STFW: search the fucking web
 - ATFG: ask the fucking google

## Chercher qqch dans liste des dossiers

## changer mdp

- passwd


## Créer un sudo user

https://thucnc.medium.com/how-to-create-a-sudo-user-on-ubuntu-and-allow-ssh-login-20e28065d9ff

- $ sudo adduser Namenewuser
- $ usermod -aG sudo newuser
- $ su - newuser
- $ mkdir ~/.ssh
- $ vim ~/.ssh/authorized_keys
- $ ssh -i path_to_your_ssh_private_key newuser@server_address


## Installer php8/mysql

https://memo-linux.com/installer-php-8-0-sur-debian-10/

## Installer apache 

https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-debian-10


Nom du domaine

-nessou.me








