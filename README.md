 # Application Web de Facturation Professionnelle
Ce projet propose une solution complète pour la gestion de factures, pensée pour les indépendants et les petites structures qui souhaitent automatiser et fluidifier leur processus de facturation. L’interface a été développée pour être simple, moderne et accessible sur tout type d’écran.

## Description Générale
L’utilisateur peut établir une facture de manière interactive : il choisit un client existant, ajoute les produits souhaités à la facture, et l’application effectue automatiquement les calculs nécessaires (montant hors taxes, taxe sur la valeur ajoutée à 20 %, et montant toutes taxes comprises).
Chaque modification effectuée dans le formulaire déclenche une mise à jour immédiate des totaux affichés. 
Les lignes produits peuvent être ajoutées ou supprimées sans recharger la page, ce qui rend l’expérience plus rapide et plus intuitive.
Une fonctionnalité essentielle incluse dans cette application est la génération directe de la facture au format PDF, permettant ainsi à l’utilisateur de la télécharger, l’imprimer ou l’envoyer par voie électronique. Cela favorise la digitalisation et l’organisation comptable.
## Technologies Employées
***Côté Client (Frontend)***
•	Angular (version 15 et plus)

•	TailwindCSS pour le style visuel

•	TypeScript

•	Reactive Forms pour une gestion robuste des formulaires

•	Animations Angular pour plus de fluidité

***Côté Serveur (Backend)***
•	Node.js

•	Express.js

•	MongoDB comme base de données

•	Mongoose pour l’abstraction des modèles
## Environnement et Outils
•	Visual Studio Code

•	npm

•	Git pour la gestion de version

•	Postman pour le test des routes API
## Fonctionnalités Clés
•	Création de factures avec sélection de client

•	Interface responsive avec transitions et messages utilisateurs

•	Ajout ou suppression de produits dynamiquement

•	Calcul en direct des montants HT, TVA, et TTC

•	Système de validation côté client avec messages d’erreur

•	Téléchargement de la facture générée sous forme de fichier PDF
## Pourquoi ce projet ?
Ce système a été imaginé pour rendre la gestion des factures plus accessible, sans logiciel compliqué ni processus long. Il est possible d’adapter cette solution à d’autres contextes métiers ou de l’étendre avec des modules supplémentaires (gestion des paiements, notifications, etc.).
Le backend assure la communication sécurisée avec la base de données et l’interface permet une expérience fluide, même sur mobile. Chaque composant du projet a été conçu pour être facilement maintenable et évolutif.
