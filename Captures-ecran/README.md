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
  
