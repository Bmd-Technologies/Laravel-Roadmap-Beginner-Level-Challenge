# Laravel-Roadmap-Beginner-Level-Challenge


# Feuille de route Laravel :
Défi du niveau débutant

Ceci est une tâche pour le [Niveau débutant de la feuille de route Laravel] (https://github.com/Bmd-Technologies/Laravel-Roadmap-Learning-Path#beginner-level), avec l'objectif d'implémenter autant de sujets que possible.Ce dépôt est intentionnellement vide, avec seulement un fichier Readme.Votre tâche est de soumettre une Pull Request avec votre version de l'implémentation de la tâche, et votre PR peut être revue par quelqu'un de notre équipe, ou d'autres volontaires.## La tâche :Blog personnel simple

Vous devez créer un blog personnel avec seulement trois pages :- Page d'accueil :Liste d'articles- Page d'article- Une page de texte statique comme "À propos de moi"


Il doit également y avoir un mécanisme de connexion (mais pas de registre) permettant à l'auteur d'écrire des articles :- Gérer (c'est-à-dire créer/mettre à jour/supprimer) les catégories- Gérer les tags- Gérer les articles 
- Pour le kit de démarrage Auth, utilisez [Laravel Breeze](https://github.com/laravel/breeze) (Tailwind) ou [Laravel UI](https://github.com/laravel/ui) (Bootstrap) - ce kit de démarrage aura un certain design, ce qui est suffisant : le design n'est pas pertinent pour accomplir la tâche.


**Structure de la base de données:**- L'article a un titre (obligatoire), un texte complet (obligatoire) et une image à télécharger (facultative).- L'article ne peut avoir qu'une seule catégorie, mais peut avoir plusieurs balises


-----

## Fonctionnalités à mettre en œuvreVoici la [liste des fonctionnalités de la feuille de route](https://github.com/Bmd-Technologies/Laravel-Roadmap-Learning-Path#beginner-level) que vous devez essayer d'implémenter dans votre code :

**Routage et contrôleurs :
Notions de base**	


- Fonctions de rappel et Route::view()
- Routage vers une seule méthode de contrôleur	
- Paramètres de l'itinéraire
- Nommage des routes	
- Groupes d'itinéraires	




**Notions de base sur Blade


- Affichage des variables dans Blade
- Structures If-Else et boucles de Blade- Boucles de Blade- Mise en page : @include, @extends, @section, @yield
- Composants de Blade




**Les bases de l'authentification	


- Modèle d'authentification par défaut et accès à ses champs depuis n'importe où
- Vérifier l'authentification dans le contrôleur / la lame
- Middleware Auth




**Les bases de la base de données	


- Migrations de bases de données
- Modèle Eloquent de base et MVC : Contrôleur -> Modèle -> Vue
- Relations Eloquent : belongsTo / hasMany / belongsToMany
- Chargement rapide et problème de requête N+1




**CRUD simple et complet	


- Ressources de routes et contrôleurs ingénieux
- Formulaires, validation et requêtes de formulaire
- Téléchargements de fichiers et bases des dossiers de stockage
- Pagination des tableaux




----- 


## Exemples de solutions


Si vous avez besoin d'aide, ou si vous voulez comparer votre version avec notre version simple, voici deux dépôts publics avec la solution :


- [Laravel Roadmap Beginner : Breeze](https://github.com/Bmd-Technologies/Laravel-Roadmap-Beginner-Roadmap-Breeze)
- [Laravel Roadmap Beginner : UI](https://github.com/Bmd-Technologies/Laravel-Roadmap-Beginner-Blog-UI)




**Notice** : veuillez consulter ces dépôts seulement APRES avoir accompli la tâche vous-même, ou si vous êtes confiant dans vos compétences de débutant Laravel et que vous pensez que vous n'avez pas besoin de vous entraîner à cette tâche.
