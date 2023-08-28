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

# Créer une base de données (si tu utilises Doctrine) (
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

# Résumé Symfony 

Composants Réutilisables : Symfony est construit autour de nombreux composants réutilisables qui peuvent être utilisés pour gérer des tâches courantes telles que la gestion des formulaires, la sécurité, la gestion des sessions, etc.

Architecture MVC : Symfony suit le modèle de conception MVC (Modèle-Vue-Contrôleur), ce qui permet de séparer la logique métier de la présentation.

Doctrine : Symfony est souvent utilisé en combinaison avec Doctrine, qui est un ORM (Object-Relational Mapping) pour la gestion de la base de données. Cela facilite la manipulation des données de la base de données en utilisant des objets PHP.

Console : Symfony offre un composant console puissant pour créer des commandes en ligne, ce qui peut être très utile pour effectuer des tâches en arrière-plan ou pour des opérations de maintenance.

Flexibilité : Symfony est conçu pour être flexible. Vous pouvez choisir d'utiliser tous les composants ou uniquement ceux dont vous avez besoin, ce qui en fait une option polyvalente pour différents types de projets.

Communauté Active : Symfony dispose d'une grande communauté d'utilisateurs et de contributeurs actifs. Il est bien documenté, et il existe de nombreuses ressources, tutoriels et extensions disponibles.

Sécurité : Symfony prend en charge de nombreuses fonctionnalités de sécurité, telles que la protection contre les attaques CSRF et XSS, l'authentification, l'autorisation, etc.
