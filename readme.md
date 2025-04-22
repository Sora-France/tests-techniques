# Test Technique : Développement Web avec Angular

## Objectif

Évaluer votre capacité à vous adapter à un framework JavaScript moderne (Angular) tout en utilisant vos connaissances en développement web. Ce test vise à examiner votre potentiel en termes de structuration d’application, compréhension de composants, services et gestion d’état.

## Contexte

Vous allez développer une petite application web front-end pour gérer une liste de tâches. Cette application vous permettra de créer, visualiser, modifier et supprimer des tâches. Chaque tâche comportera un titre, une description et un état (à faire, en cours, terminée).

## Étapes à suivre
1.	Installation et Configuration d’Angular
 *	Installez Angular CLI en suivant la documentation officielle.
 *	Créez une nouvelle application Angular.
2.	Création du Modèle Task
 *	Créez une interface Task avec les propriétés suivantes :
 *	id (number, auto-incrémenté dans le front)
 *	title (string)
 *	description (string)
 *	status (string, valeurs possibles : “à faire”, “en cours”, “terminée”)
3.	Création du Service TaskService
 *	Créez un service Angular qui permettra de gérer les tâches en mémoire.
 *	Ce service doit inclure des méthodes pour :
 *	récupérer la liste des tâches,
 *	récupérer une tâche par son id,
 *	créer une nouvelle tâche,
 *	mettre à jour une tâche existante,
 *	supprimer une tâche.
4.	Création des Composants
 *	Créez les composants suivants :
 *	TaskListComponent : afficher la liste des tâches.
 *	TaskDetailComponent : afficher les détails d’une tâche.
 *	TaskFormComponent : formulaire pour créer et modifier une tâche.
 *	Chaque composant doit avoir une interface claire et fonctionnelle.
5.	Routing
 *	Configurez le routing Angular avec les routes suivantes :
 *	/tasks : liste des tâches.
 *	/tasks/new : formulaire de création.
 *	/tasks/:id : détails d’une tâche.
 *	/tasks/:id/edit : modification d’une tâche.
6.	Validation et UX
 *	Ajoutez des règles de validation dans les formulaires (par exemple : champs obligatoires).
 *	Affichez des messages d’erreur clairs en cas de saisie incorrecte.
7.	Bonus
 *	Stylisez l’application pour qu’elle soit agréable à utiliser.
 *	Implémentez une petite confirmation avant suppression.

## Instructions
1.	Documentation : Appuyez-vous sur la documentation officielle d’Angular.
2.	Dépôt Git : Versionnez correctement votre code sur un dépôt GitHub public.
3.	Livrables (dépôt GitHub) :
* Le code source complet de l’application Angular.
*	Un fichier README.md expliquant comment installer, lancer et utiliser l’application.

## Critères d’évaluation
*	Fonctionnalités : Toutes les fonctionnalités demandées sont-elles présentes et fonctionnelles ?
*	Code : Le code est-il propre, modulaire, bien structuré et commenté ?
*	Adaptation : Le candidat a-t-il su s’adapter et utiliser Angular efficacement ?
*	Documentation : Les instructions pour installer et utiliser l’application sont-elles claires et complètes ?

Bonne chance !
