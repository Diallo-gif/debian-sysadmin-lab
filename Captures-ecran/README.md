# Captures d'écran

Ce dossier regroupe les preuves visuelles des différentes phases du laboratoire Debian 13.

## Phase 00 - Préparation du lab

### Identification des machines

Les deux machines virtuelles ont été différenciées afin d'avoir un serveur et un poste d'administration distincts.

- `debian-srv01` : serveur Linux
- `debian-cli01` : poste d'administration et de test

Les captures montrent la vérification du hostname sur chacune des machines.

## Phase 01 - Comprendre le système Debian

Exploration de plusieurs répertoires importants afin de comprendre l'organisation du système et de savoir où rechercher une information lors d'un diagnostic.

- `/etc` : configurations du système et des services
- `/dev` : périphériques du système
- `/proc` : informations sur le système et les processus
- `/var/log` : journaux du système et des services

L'objectif est de savoir où chercher selon le type de problème rencontré.

# Phase 02 - Manipulation des fichiers et répertoires

Cette phase consiste à manipuler des fichiers et des répertoires dans un environnement Debian à travers une arborescence de test située dans `/opt/nexatech`.

## Travaux réalisés

- Création de répertoires et de fichiers
- Navigation dans l'arborescence
- Copie, déplacement, renommage et suppression de fichiers
- Lecture du contenu avec `cat`, `head` et `tail`
- Modification de fichiers avec `nano`
- Utilisation de `sudo` lorsque les permissions l'exigent
- Utilisation de l'historique pour retrouver des commandes précédentes

## Objectif

Être capable de manipuler les fichiers et répertoires depuis le terminal et de comprendre les problèmes de permissions rencontrés lors des opérations d'administration.

## Recherche de fichiers

Objectif : retrouver rapidement un fichier sans parcourir manuellement l’arborescence.

- `find` : recherche directement dans l’arborescence.
- `locate` : recherche rapidement via une base de données indexée.
- `plocate` : paquet utilisé sur Debian 13 pour fournir la commande `locate`.
- tilisation de `find` pour rechercher des fichiers selon leur extension.

Commande utilisée :
`find / -type f -name "*.txt"`
Utilisation de `grep` et `less` pour rechercher une information précise dans un fichier texte.

`grep -i "sauvegarder" notes_data.txt`

`less notes_data.txt`
