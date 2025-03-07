# Exercice 2 - VM Linux # 

## Partie 1 - Gestion des utilisateurs ##
### Q.2.1.1 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.1.1.png) 
### Q.2.1.2 ###   
          Selon l'ANSSI, les préconisations sont multiples :  
          > Choisir un mot de passe fort 
          > Appliquer la politique de moindre privilèges
          > Effectuer les mises à jour et sauvegarder vos données.
          
## Partie 2 - Configuration de SSH ##
### Q.2.2.1 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.2.1.png) 
### Q.2.2.2 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.2.2.png) 
### Q.2.2.3 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.2.3.png) 

## Partie 3 - Analyse du stockage ##
### Q.2.3.1 ###   
          Il y a du ext2, ext4, swap  
### Q.2.3.2 ###  
          Il y a du raid1 et du LVM  
### Q.2.3.3 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.2.3.png) 

### Q.2.3.4 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.3.4.png) 
### Q.2.3.5 ###   

## Partie 4 - Sauvegardes ##
### Q.2.4.1 ###  
        Bareos-dir (Director) est celui qui contrôle et organise l'ensemble des composants chargés de la sauvegarde
        Bareos-sd (Storage-Daemon) est celui qui est chargé de la gestion du stockage des sauvegardes.
        Bareos-fd (File-Daemon) est l'agent de sauvegarde installé sur les machines à sauvegarder.

## Partie 5 - Filtrage et analyse réseau ##

### Q.2.5.1 ###  
        Tout trafic entrant est bloqué par défaut, sauf si une règle l'autorise.  
### Q.2.5.2 ###  
        Le trafic interne est autorisé, la connection SSH sur le port 22, le ping et le protocoles ICMP en IP et aussi en IPV6.
### Q.2.5.3 ###     
          Les types qui sont interdits sont 
### Q.2.5.4 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.5.4.png) 

## Partie 6 - Analyse de logs ##

### Q.2.6.1 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.6.1.png) 

ok : /24  
nr :  
faux :   
