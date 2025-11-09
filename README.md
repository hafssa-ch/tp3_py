# TP3 – Héritage
### Objectif général

Ce TP a pour but d’approfondir les notions d’héritage, de spécialisation et de polymorphisme en Python.
Les exercices illustrent comment factoriser le code à l’aide d’une classe de base commune, puis personnaliser le comportement dans des sous-classes.

## Exercice 1 — Gestion des employés
### Objectif pédagogique
Mettre en œuvre l’héritage simple pour modéliser différents types d’employés au sein d’une entreprise, chacun ayant des caractéristiques spécifiques.

### Description
On souhaite gérer plusieurs types d’employés :
Employé standard : possède un salaire de base.
Manager : possède une prime en plus de son salaire de base.
Développeur : reçoit un bonus selon sa technologie principale.

### Fonctionnalités
Calcul du salaire total selon le rôle.
Redéfinition de méthodes (salaire_total) dans les sous-classes.
Utilisation de super() pour appeler le constructeur parent.
<img width="521" height="104" alt="image" src="https://github.com/user-attachments/assets/a05cb2b0-cc8b-422c-a4d6-62d4a617e84f" />


## Exercice 2 — Bibliothèque
### Objectif pédagogique
Illustrer la spécialisation de classes à partir d’un type de base commun, en appliquant la surcharge de méthodes.

### Description
On modélise une bibliothèque contenant différents types de documents 
Document (classe de base) : possède un titre et une année.
Livre : ajoute un auteur.
Magazine : ajoute un numéro d’édition.
Chaque type de document sait s’afficher différemment grâce à la redéfinition de la méthode afficher().

### Fonctionnalités
Classe de base commune (Document) avec méthode générique afficher().
Surcharge dans les classes filles pour un affichage personnalisé.
Utilisation du polymorphisme pour traiter une liste mixte de documents.
<img width="490" height="101" alt="image" src="https://github.com/user-attachments/assets/6ad02561-6414-4e80-89c5-b0758d98cad0" />


