# Les Rendez-vous des Speakers

 

Site web pour *Les Rendez-vous des Speakers*.

  

## Prochain événement

[![Le Noël des Speakers 2020](./noel-2020/static/images/social-share.jpg)](https://rdv-speakers.fr/noel-2020/)



## Structure

Dans ce dépôt il y a plusieurs sites :

- Le site global de *Les Rendez-vous des Speakers* (`/rdv-speakers/`)
- Un site pour chacun de nos événements:
  - La Rentrée des Speakers 2020 (`/rentree-2020/`)
  - Le Halloween des Speakers 2020 (`/halloween-2020/`)
  - Le Noël des Speakers 2020 (`/noel-2020/`)

Chaque site est un projet Hugo, et le fichier `build.sh` à la racine du dépôt permet de construire tous les projets et les merger sur `/doc`, qui est le répertoire utilisé pour le GitHub pages.