# Exercice 2 - VM Linux # 

## Partie 1 - Gestion des utilisateurs ##
### Q.2.1.1 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.1.1.png) 
### Q.2.1.2 ###   
          > Choisir un mot de passe fort 
          > Appliquer la politique de moindre privilèges
          > Effectuer les mises à jour et sauvegarder vos données.
          > Gestion et sécurisation des accès.
          
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
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.3.1.png)           
### Q.2.3.2 ###  
          Il y a du raid1 et du LVM  
 ![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.3.2.png)           
### Q.2.3.3 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.3.3A.png) 
### Q.2.3.4 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.3.4.png) 
### Q.2.3.5 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.3.5.png) 

## Partie 4 - Sauvegardes ##
### Q.2.4.1 ###  
        Bareos-dir (Director) est celui qui contrôle et organise l'ensemble des composants chargés de la sauvegarde.  
        Bareos-sd (Storage-Daemon) est celui qui est chargé de la gestion du stockage des sauvegardes,    
                  il s'occupe de la récupération des fichiers sauvegardés lorsqu'une restauration est demandée.
        Bareos-fd (File-Daemon) est l'agent de sauvegarde installé sur les machines à sauvegarder, il exécute les tâches demandés par le Bareos-Dir.

## Partie 5 - Filtrage et analyse réseau ##
### Q.2.5.1 ###  
        Tout trafic entrant est bloqué par défaut, sauf si une règle l'autorise.  
### Q.2.5.2 ###  
        Le trafic interne, la connection SSH sur le port 22, le ping et le protocoles ICMP en IP et aussi en IPV6 sont autorisés.
### Q.2.5.3 ###     
          Les types qui sont interdits sont tous les trafic entrant sauf qui bénéficie d'une règle paticulière.
### Q.2.5.4 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.5.4.png) 

## Partie 6 - Analyse de logs ##

### Q.2.6.1 ###   
![](https://github.com/AdeL448/Checkpoint3/blob/main/Ressources/Q.2.6.1.png) 

ok : /24  
nr :  
faux :   
