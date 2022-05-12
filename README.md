# Système Réseau



- RTFM : read the fucking manual
 - STFW: search the fucking web
 - ATFG: ask the fucking google

SSH (Secure Shell) est un protocole de communication sécurisé qui permet de se connecter à un ordinateur distant de façon sécurisée, au sein d’un réseau potentiellement non sécurisé comme Internet.

## Schéma routage 

https://pixees.fr/informatiquelycee/n_site/snt_internet_routage.html

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
 - find = trouver le chemin du fichier ou dossier
 -  grep nomMot * = tous les fichiers qui contiennent nomMot
  - grep nomcaractère = recherche dans tous les fichiers ou se trouvent les caractères
 
 - find / -type d -name www = chercher un type de fichier spécifique
 - grep -rn "charactère" /chemin/ = rechercher un charactère spé
 

 

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
 
 
 ## Failles
 
 XSS(Cross-Site Scripting) = faille de sécurité d'un site web qui consiste à injecter du contenu malveillant en langage script. Il peut rediriger les internautes vers un autre site web, bloquer l'accès au site, prendre le contrôle d'un site web pour ajouter ou supprimer du contenu, récupérer des données transmises par les utilisateurs.
 
  Injections SQL(SQLi) = modification d'une requête envoyée à la base de donnée pour en détourner l'utilisation. On peut se connecter à un site en tant qu'administrateur,  modifier des données.



## DNS (domaine name system)
 la principale fonction est de traduire un nom de domaine en adresse IP.
 


