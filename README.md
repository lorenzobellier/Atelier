# Atelier

Atelier est un projet pédagogique pratique pour la gestion d’un **inventaire informatique** et le suivi d’**incidents IT** dans une entreprise fictive.  
Il est divisé en deux modules : 

1. **01_inventaire** – Création et analyse d’un inventaire numérique  
2. **02_incidents** – Gestion d’incidents via tickets et suivi de résolution

---

## Objectifs

- Développer des compétences pratiques en **gestion d’inventaire informatique**  
- Apprendre à **documenter et suivre des incidents IT**  
- Travailler en binômes pour simuler un environnement professionnel  
- Appliquer des mesures correctives et analyser la conformité des logiciels et équipements

---

## Structure du projet


Atelier/
├── 01_inventaire/   # Module de création d'inventaire
├── 02_incidents/    # Module de gestion d'incidents
└── README.md

## Prérequis

- Logiciel de tableur : **Excel**, **LibreOffice Calc**, ou **Google Sheets**  
- Éditeur de texte ou IDE (optionnel)  
- Connaissances de base en gestion d’actifs et résolution d’incidents IT  

---

## 01_inventaire

**Objectif :** Créer un inventaire numérique cohérent et durable du patrimoine informatique.

### Consignes

1. Constituer des binômes  
2. Créer une feuille `Inventaire informatique`  
3. Ajouter les colonnes suivantes :

| Colonne |
|---------|
| ID actif |
| Type d’équipement |
| Marque / Modèle |
| Numéro de série |
| Utilisateur |
| Localisation |
| Date d’achat |
| Fin de garantie |
| Logiciels installés |
| Licence (Oui/Non) |
| Fournisseur |
| Statut (actif, recyclé, en maintenance) |
| Commentaire libre |

4. Remplir le tableau pour **10 équipements fictifs**  
5. Indiquer **au moins un logiciel non conforme** et proposer une action corrective  
6. Exporter le fichier au format **CSV**

### Analyse et filtres

- Identifier les actifs dont la **licence est expirée**  
- Identifier ceux **hors garantie**  
- Calculer :  
  - Nombre total d’actifs par type  
  - Pourcentage d’actifs avec licences valides  

### Étapes supplémentaires

- Ajouter une nouvelle ligne pour un équipement fictif  
- Exporter le résultat final au format `.csv`  

---

## 02_incidents

**Objectif :** Simuler la gestion d’incidents IT via un système de tickets.

### Consignes

1. Chaque binôme choisit **deux incidents fictifs** parmi :

- Impossible de se connecter à la messagerie Outlook  
- L’imprimante du 3ᵉ étage ne répond plus  
- Un fichier partagé sur le réseau est inaccessible  
- Le poste d’un utilisateur affiche un message d’erreur au démarrage  
- Un utilisateur demande la création d’un nouveau compte  

2. Créer le ticket (GLPI ou tableur simulé) avec les champs :

| Champ |
|-------|
| ID du ticket |
| Date d’ouverture |
| Demandeur / Service concerné |
| Description du problème |
| Gravité (mineure / majeure / critique) |
| Diagnostic |
| Action corrective |
| Durée de résolution |
| Technicien responsable |
| Statut (ouvert / en cours / résolu / clos) |
| Commentaires utilisateur |

3. **Diagnostic et résolution :**  
- Identifier la cause probable  
- Proposer une solution (réinitialisation, mise à jour, redémarrage, support niveau 2…)  
- Documenter les étapes  

4. **Clôture du ticket :**  
- Confirmer avec l’utilisateur  
- Changer le statut à **Clos**  
- Évaluer la satisfaction utilisateur (note sur 5)  
