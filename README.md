# StartSymfony
Commande Basique (Débutant) pour symfony


# Créer un nouveau projet Symfony
symfony new nom-du-projet

# Démarrer le serveur de développement
symfony server:start

# Générer un contrôleur
php bin/console make:controller NomDuController

# Générer une entité (si tu utilises Doctrine)
php bin/console make:entity

# Créer une base de données (si tu utilises Doctrine)
php bin/console doctrine:database:create

# Exécuter des migrations (si tu utilises Doctrine)
php bin/console doctrine:migrations:migrate

# Définir des routes dans config/routes.yaml, puis les lister
php bin/console debug:router

# Afficher la liste des commandes Symfony disponibles
php bin/console list

# Gérer les dépendances avec Composer
# Pour installer de nouvelles dépendances
composer require nom-du-paquet

# Pour mettre à jour les dépendances
composer update
