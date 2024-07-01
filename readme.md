# Test Technique : Développement Web avec Symfony

## Objectif

Évaluer votre capacité à vous adapter à un nouveau framework PHP (Symfony) tout en utilisant vos connaissances en PHP. Ce test vise à examiner votre potentiel en termes de développement web et d'adaptation technique.

## Contexte

Vous allez développer une petite application web pour gérer une liste de tâches. Cette application vous permettra de créer, visualiser, modifier et supprimer des tâches. Chaque tâche comporte un titre, une description, et un état (à faire, en cours, terminée).

## Étapes à suivre

1. Installation et Configuration de Symfony
    - Installez Symfony en suivant les instructions sur le site officiel.
    - Créez un nouveau projet Symfony.
2. Création d'une Entité Tâche

- Créez une entité Task avec les propriétés suivantes :
    - id (auto-incrémenté)
    - title (string)
    - description (text)
    - status (string, valeurs possibles : "à faire", "en cours", "terminée")
- Utilisez Doctrine pour générer la base de données à partir de cette entité.

3. Création des Formulaires

- Créez un formulaire pour la création et la modification des tâches.

4. Création des Contrôleurs

- Créez un contrôleur pour gérer les routes suivantes :
    - /tasks : afficher la liste des tâches
    - /task/new : formulaire pour créer une nouvelle tâche
    - /task/{id} : afficher les détails d'une tâche
    - /task/{id}/edit : formulaire pour modifier une tâche existante
    - /task/{id}/delete : supprimer une tâche

5. Création des Vues

- Créez des vues Twig pour chacune des routes définies ci-dessus. Assurez-vous que les vues soient claires et faciles à naviguer.

6. Validation et Sécurité

- Ajoutez des règles de validation aux formulaires.
- Implémentez une sécurité basique pour éviter la soumission de formulaires vides ou incorrects.

## Instructions

1. Documentation : Utilisez la documentation officielle de Symfony pour vous aider.
2. Durée : Vous avez 3 heures pour réaliser ce test.
3. Livrables :
- Le code source complet de l'application Symfony.
- Une base de données SQLite ou MySQL contenant quelques exemples de tâches.
- Un fichier README.md expliquant comment installer et lancer l'application.

## Critères d'évaluation

- Fonctionnalités : Toutes les fonctionnalités demandées sont-elles présentes et fonctionnelles ?
- Code : Le code est-il propre, bien structuré et commenté ?
- Adaptation : Le candidat a-t-il su s'adapter et utiliser Symfony efficacement ?
- Documentation : Les instructions pour installer et utiliser l'application sont-elles claires ?


Bonne chance !
