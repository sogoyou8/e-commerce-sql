# E-commerce SQL Project

## Description
Ce projet consiste à développer une base de données pour un site e-commerce. Il inclut la génération de données fictives pour les utilisateurs, produits, commandes, factures, avis et paniers, à l'aide d'un script PHP. Ce projet est conçu pour gérer les aspects essentiels d'un site de commerce en ligne en utilisant une base de données SQL.

## Structure du projet
### Dossiers :
- **/images** : Contient les images.png de l'affichage et la gestion des tables de la base de données.
- **Ecommerce_db.sql** : Contient le fichier SQL pour la création et la gestion des tables de la base de données.
- **style.css** : Contient le fichier CSS pour le style de l'interface HTML.
- **index.php** : Contient le script de génération de données fictives.

### Tables de la base de données :
- `users` : Informations des utilisateurs (nom, email, mot de passe sécurisé, etc.).
- `adresses` : Adresses associées aux utilisateurs.
- `products` : Liste des produits avec prix et fournisseur.
- `photos` : Images associées aux produits.
- `rates` : Avis des utilisateurs sur les produits.
- `cart` : Produits ajoutés au panier des utilisateurs.
- `invoices` : Factures des utilisateurs pour leurs achats.
- `orders` : Commandes associées aux factures.

## Technologies utilisées
- **PHP** : Utilisé pour générer les données fictives et interagir avec la base de données.
- **MySQL** : Base de données pour stocker les informations des utilisateurs, produits, commandes, etc.
- **Faker** : Librairie PHP pour générer des données fictives.
- **Composer** : Gestionnaire de dépendances pour PHP, utilisé pour installer et gérer la librairie Faker.
- **CSS** : Utilisé pour styliser l'interface HTML affichant les données générées.
- **Git** : Gestion de versions.

## Installation
### Prérequis :
- **XAMPP** ou un autre serveur local pour exécuter PHP et MySQL.
- **Git** pour la gestion des versions.
- **Composer** pour gérer les dépendances PHP.


### Étapes :
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/sogoyou8/e-commerce-sql.git
