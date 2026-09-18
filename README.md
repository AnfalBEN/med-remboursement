# Med-Remboursement

Application web simple permettant de rechercher un médicament et de savoir 
s'il est remboursé par la Sécurité sociale, et à quel taux.

## Contexte
Projet personnel réalisé en autonomie (avec relecture/validation des données 
par , étudiante en pharmacie), dans le but de proposer 
un outil simple d'accès à une information peu lisible pour le grand public.

## Objectif
Permettre à un utilisateur de taper le nom d'un médicament et d'obtenir 
instantanément :
- son statut de remboursement (oui/non)
- le taux de remboursement (100%, 65%, 30%, 15%)
- sa forme pharmaceutique

## Fonctionnalités (MVP)
- [ ] Recherche d'un médicament par nom (avec autocomplétion si possible)
- [ ] Affichage du taux de remboursement
- [ ] Gestion des cas "médicament non trouvé"

## Fonctionnalités futures (bonus)
- [ ] Recherche par substance active
- [ ] Historique des recherches (local storage)
- [ ] Comparaison de plusieurs médicaments génériques

## Source des données
Base de Données Publique des Médicaments (BDPM) — ANSM / HAS / Assurance Maladie
https://base-donnees-publique.medicaments.gouv.fr
(données réutilisables librement, source à citer)

## Stack technique
- Backend : [Node.js/Express ou Python/FastAPI]
- Frontend : [Angular ou HTML/CSS/JS]
- Base de données : SQLite
- Conteneurisation : Docker

## Installation
[à compléter]

## Auteur
Anfal Bensaou — étudiante ingénieure, Polytech Nice Sophia (Systèmes Informatiques)


---------------------------------------------------------------------------------------------------------

# Med-Reimbursement

Simple web application that allows users to search for a medication and find out whether it is reimbursed by the French Social Security system, and at what rate.

##Context
Personal project developed independently (with data review/validation by a pharmacy student), with the goal of providing an easy-to-use tool for accessing information that can be difficult for the general public to understand.

##Objective
Allow users to enter the name of a medication and instantly obtain:
its reimbursement status (yes/no)
the reimbursement rate (100%, 65%, 30%, 15%)
its pharmaceutical form

##Features (MVP)
 -Search for a medication by name (with autocomplete if possible)
 -Display the reimbursement rate
 -Handle "medication not found" cases
 
##Future Features (Bonus)
 -Search by active ingredient
 -Search history (local storage)
 -Compare several generic medications
 
##Data Source
Public Database of Medicines (BDPM) — ANSM / HAS / Assurance Maladie
https://base-donnees-publique.medicaments.gouv.fr
(Data can be freely reused; source must be cited)

##Tech Stack
  -Backend: [Node.js/Express or Python/FastAPI]
  -Frontend: [Angular or HTML/CSS/JS]
  -Database: SQLite
  -Containerization: Docker
  
##Installation
  [To be completed]
  
##Author
Anfal Bensaou — Engineering student, Polytech Nice Sophia (Computer Systems)
