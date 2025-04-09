

# Khadmalik  

Une application pour lister des missions/emplois  "[ 2025] 

![Alt text](/public/images/screen.png "Khadmalik")  

## Utilisation  

### Configuration de la base de données  
Cette application utilise MySQL. Pour utiliser un autre système, modifiez le pilote par défaut dans le fichier `config/Database.php`.  

Pour utiliser MySQL, assurez-vous de l'installer, de créer une base de données, puis ajoutez vos identifiants (nom de la base de données, utilisateur et mot de passe) dans le fichier `.env.example` et renommez-le en `.env`.  

### Migrations  
Pour créer toutes les tables et colonnes nécessaires, exécutez la commande suivante :  
```
php artisan migrate
```  

### Peuplement de la base de données  
Pour ajouter des annonces fictives avec un seul utilisateur, exécutez la commande suivante :  
```
php artisan db:seed
```  

### Téléchargement de fichiers  
Lors du téléchargement des fichiers des annonces, ceux-ci sont stockés dans `storage/app/public`. Créez un lien symbolique avec la commande suivante pour les rendre accessibles publiquement :  
```
php artisan storage:link
```  

### Exécution de l'application  
Transférez les fichiers vers la racine de votre document, le dossier Valet ou exécutez :  
```
php artisan serve
```  

## Licence  

L'application Khadmalik est un logiciel open-source sous licence


