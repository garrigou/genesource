# Project name
***
Gestion des sources en généalogie.

## Table des matières
1. [Installation](#installation)

## Installation

Il faut tout d'abord cloner le projet :

```
$ git clone git@github.com:garrigou/symfony_docker.git
```

Puis lancer les conteneurs :

```
$ make docker-up-build
```

Cette commande va lancer :

- Un conteneur nginx : 1.20-alpine
- Un conteneur php-fpm : 8.0
- Un conteneur MySQL : 5.7
- Un conteneur phpMyAdmin : 5.1

Le site est accessible [ici](http://localhost:7000) et le phpMyAdmin [là](http://localhost:8080).