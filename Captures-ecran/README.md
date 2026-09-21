# Captures d'écran

Ce dossier regroupe les captures des différentes phases du laboratoire Debian 13.

## Phase 00 - Préparation du lab

Deux machines virtuelles :
- `debian-srv01` : serveur Linux
- `debian-cli01` : poste d'administration et de test

## Phase 01 - Comprendre le système Debian

Exploration des principaux répertoires :
- `/etc` : configurations
- `/dev` : périphériques
- `/proc` : système et processus
- `/var/log` : journaux

## Phase 02 - Manipulation des fichiers

Travail dans `/opt/nexatech` :
- Création, copie, déplacement et suppression
- Lecture avec `cat`, `head`, `tail`
- Modification avec `nano`
- Gestion des permissions avec `sudo`
- Utilisation de l'historique

## Phase 03 - Recherche et traitement de texte

Recherche de fichiers :
`find`, `locate`

Recherche dans un fichier :
`grep`, `less`

Filtrage d'une sortie :
`grep`, `awk`

Extraction de colonnes CSV :
`cut`, `awk`
## Phase 04 - Utilisateurs et groupes

- Création et gestion des utilisateurs et groupes
- Attribution des utilisateurs aux groupes métiers
- Vérification des appartenances et des rôles
- Gestion des mots de passe et des comptes
- Verrouillage, désactivation et réactivation de comptes
- Gestion et test des permissions d'accès
## Phase 05 - Permissions et moindre privilège
- Gestion des permissions sur les dossiers métiers
- Tests d'accès autorisés et refusés
- Gestion des droits avec `chmod`, `chown` et `chgrp`
- Tests de création et modification de fichiers
- Utilisation de `umask`, `setgid` et du sticky bit
- Gestion avancée des permissions avec les ACL
## Phase 06 - Gestion des paquets et maintenance
- Identification des dépôts APT configurés
- Actualisation et mise à jour des paquets
- Recherche et installation de paquets
- Vérification des paquets et de leurs versions
- Identification du paquet associé à un fichier
- Suppression, purge et réinstallation de paquets
- Maintenance contrôlée du système avec `apt` et `dpkg`
## Phase 07 - Réseau Linux et diagnostic
- Identification des interfaces réseau et des adresses IPv4
- Vérification du préfixe, de la passerelle, des DNS et de la route par défaut
- Tests de communication entre `debian-srv01` et `debian-cli01`
- Tests IP, Internet et résolution DNS
- Identification des ports et sockets en écoute
- Comparaison des modes VMware : NAT, Bridged et Host-only
- Méthode de diagnostic réseau en 5 étapes
## Phase 08 - Configuration réseau statique avec Netplan
- Configuration d'adresses IP statiques
- Configuration du réseau avec `Netplan`
- Gestion de la route par défaut et du DNS
- Vérification de la connectivité entre les VM
- Tests réseau après application de la configuration
- Vérification de la persistance après redémarrage
- Diagnostic d'une erreur de configuration réseau
  ## Phase 09 - Stockage, partitions et montage
- Ajout et identification d'un second disque
- Création d'une partition et d'un système de fichiers
- Identification de l'UUID
- Montage et démontage du disque
- Configuration du montage permanent avec `/etc/fstab`
- Vérification du montage après redémarrage
  ## Phase 10 - Processus, services, logs et monitoring
- Identification et surveillance des processus
- Surveillance CPU et mémoire
- Gestion et arrêt des processus
- Vérification et gestion des services avec `systemctl`
- Consultation des journaux système avec `journalctl`
- Filtrage des logs par service
- Suivi des événements en temps réel
- Analyse des événements d'authentification
## Phase 11 - Archivage, compression et restauration
- Création et compression d'une archive avec `tar`
- Stockage de la sauvegarde dans un emplacement dédié
- Création d'un répertoire de restauration
- Restauration des données depuis l'archive
- Vérification des données restaurées
- Contrôle de la taille et de la date de la sauvegarde
## Phase 12 - Sécurité Linux de base
- Gestion des comptes et privilèges
- Administration avec `sudo` et `visudo`
- Contrôle des permissions
- Configuration du pare-feu
- Vérification des ports et services exposés
- Surveillance des connexions
- Sécurisation SSH
- Mise en place de règles de sécurité
## Phase 13 - Administration distante avec SSH
- Installation et démarrage du service SSH
- Vérification du port d'écoute SSH
- Première connexion SSH depuis le poste client
- Vérification des journaux SSH
- Transfert de fichier avec SCP
- Création d'une paire de clés SSH
- Authentification SSH par clé
- Vérification de la clé publique et de la clé privée
- Sécurisation de la configuration SSH
  
  
  
  
