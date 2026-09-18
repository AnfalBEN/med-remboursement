# med-remboursement
Projet personnel visant à la fois à m'entraîner sur différentes technologies (C, Java, Web) et à répondre à un besoin concret du quotidien : savoir rapidement si un médicament est remboursé.

# 💊 Med-Remboursement

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
