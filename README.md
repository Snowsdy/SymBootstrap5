# SymBootstrap5

Site Web réalisé avec le framework PHP Symfony 5 couplé à Bootstrap 5.2.0-beta1

## Pré-requis
Afin de pouvoir exploiter ce projet, il est nécessaire d'avoir :
* Composer
* PHP 8.1.7
* Symfony CLI
* Docker
* docker-compose
* NodeJS & Npm

### Lancement de l'environnement de développement
Une fois le projet cloné, pour lancer l'environnement de développement, il suffit de taper les commandes suivantes dans un terminal (tout en étant dans le dossier du projett, bien entendu):

```bash
$ composer install
$ npm run build
$ docker-comopse up -d
$ symfony serve -d
```