# Système Réseau

- RTFM : read the fucking manual
 - STFW: search the fucking web
 - ATFG: ask the fucking google

SSH (Secure Shell) est un protocole de communication sécurisé qui permet de se connecter à un ordinateur distant de façon sécurisée, au sein d’un réseau potentiellement non sécurisé comme Internet.

## Autentification

Dans git bash 

- ssh ines_slotwinski@51.15.252.63
- yes 
- mdp

## Commandes
scp <fichier à envoyer> <utilisateur>@<hôte distant>:<dossier cible>
 - cp: copier le fichier => cp fichier1.txt fichier2.txt
-  mv: bouge ou renome un fichier =>mv ancien_nom.txt nouveau_nom.txt
=> mv /tmp/fichier1.txt /home/plv/
=> mv ancien_nom.txt nouveau_nom.txt
-  cat: affiche le contenu d’un fichier 
 - nano/vim : permet de créer un fichier ou de modifier un fichier existant => nano fichier.txt
 
 
 ### executer un script
 
 - cd nom-du-repertoire 
 - chmod +x script.sh //permet de rendre le dossier executable
 - ./script.sh 
 

## Chercher qqch dans liste des dossiers
 
 - locate nomdufichier = chercher un fichier 
 - find / -type d -name www = chercher un type de fichier spécifique
 - grep -rn "It works" /var/www/ = rechercher un charactère spé
 -  	grep nomMot * = tous les fichiers qui contiennent un mot
 - grep nomcaractère = recherche dans tous les fichiers ou se trouvent les caractères
 - find nomFichierDossier

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


### Nom du domaine

-nessou.me


__Pour créer mon site il faut un virtual host__

/etc/apache2/sites-available sont les sites disponibles (available)
/etc/apache2/sites-enabled sont les sites actifs, activés (enabled)

## config virtual host

https://www.digitalocean.com/community/tutorials/how-to-set-up-apache-virtual-hosts-on-ubuntu-18-04-fr






