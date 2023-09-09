# Projet agile Master 2 BI&A


## Documentation technique du projet Etudiant comprenant les differentes étapes de mise en place du projet.




## Table des matières

- [Composantes du projet](#composantes-du-projet)
- [Prérequis](#prérequis)
- [Installation de docker Windows et Distribution Linux](#installation-de-docker-windows-et-distribution-linux)
- [Installation de docker-compose](#installation-de-docker-compose)
- [Installation du projet](#installation-du-projet)
- [Accès à l'application](#accès-à-lapplication)
  - [Credentials Metabase dans le fichier .env nom d'utilisateur et mot de passe par défaut sur les deux variables suivantes :](#credentials-metabase-dans-le-fichier-env-nom-dutilisateur-et-mot-de-passe-par-défaut-sur-les-deux-variables-suivantes-)
  - [Credentials MySQL dans le fichier .env nom d'utilisateur et mot de passe par défaut sur les deux variables suivantes :](#credentials-mysql-dans-le-fichier-env-nom-dutilisateur-et-mot-de-passe-par-défaut-sur-les-deux-variables-suivantes-)

# Composantes du projet

- Metabase
- MySQL

## Prérequis



* Docker

## Installation de docker Windows et Distribution Linux

* [Docker Windows](https://docs.docker.com/docker-for-windows/install/)

* [Docker Linux](https://docs.docker.com/install/linux/docker-ce/ubuntu/)

## Installation de docker-compose

* [Docker-compose](https://docs.docker.com/compose/install/)

## Installation du projet

```bash
git clone https://github.com/MASTER2-BI-A/project.git
cd projet_agile
cd docker-sources
cp .env_exemple .env
docker-compose up -d
```


## Accès à l'application

* [Metabase](http://localhost:3000)

### Credentials Metabase dans le fichier .env nom d'utilisateur et mot de passe par défaut sur les deux variables suivantes :

- Utilisateur : LOGIN
- Mot de passe : PASSWORD

### Credentials MySQL dans le fichier .env nom d'utilisateur et mot de passe par défaut sur les deux variables suivantes :

- Utilisateur : MYSQL_USER
- Mot de passe : MYSQL_PASSWORD