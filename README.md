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

### Vérifier les pré-requis de Symfony
Pour vérifier que Symfony puisse fonctionner correctement, utilisez la commande suivante :

```bash
symfony check:req
```

Cette commande vous confirmera également la version de PHP que votre Symfony utilise. Dans le cas où vous avez plusieurs versions et que celui-ci n'utilise pas la bonne, j'ai trouvé cette solution :

- Sous Linux (Ubuntu pour ma part), dans votre dossier personnel, créer un fichier `.php-version` et écrire tout simplement la version que vous voulez utiliser (dans le cas du projet : 8.1).

### Lancement de l'environnement de développement
Une fois le projet cloné, pour lancer l'environnement de développement, il suffit de taper les commandes suivantes dans un terminal (tout en étant dans le dossier du projet, bien entendu):

```bash
composer install
npm run build
docker-comopse up -d
symfony serve -d
```