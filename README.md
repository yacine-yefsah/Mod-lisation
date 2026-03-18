# Travaux Pratiques — Recherche Operationnelle (Master 1 SAAD)

## Contexte

Ce depot contient les resolutions de 5 problemes d'optimisation par Programmation Lineaire, realises dans le cadre du Master 1 Statistique Appliquee (SAAD) a l'Universite de Caen Normandie.

## Objectifs

- Modeliser des problemes reels sous forme de programmes lineaires
- Identifier les variables de decision, la fonction objectif et les contraintes
- Resoudre les problemes d'optimisation (maximisation et minimisation)
- Interpreter les solutions optimales dans leur contexte metier

## Stack Technique

| Outil | Usage |
|---|---|
| LibreOffice Calc / Excel | Modelisation et resolution des PL |
| Solver | Resolution des programmes lineaires |

## Structure du Projet
```
Mod-lisation/
├── README.md
└── Revision.ods   # Fichier contenant les 5 problemes modelises et resolus
```

## Problemes Traites

**Probleme 1 — Optimisation de la production d'une conserverie**
Maximisation du benefice net d'une conserverie produisant deux types de confits (Superieur et Standard) sous contraintes de stocks de viande et de truffes.

**Probleme 2 — Planification des effectifs de chauffeurs de bus**
Minimisation du nombre total de chauffeurs a embaucher pour couvrir les besoins en conducteurs sur 5 creneaux horaires consecutifs, avec contrainte de 3h de travail consecutif par chauffeur.

**Probleme 3 — Ordonnancement de chantiers sous contrainte de ressources**
Planification de 4 chantiers sur 6 semaines avec un maximum de 9 ouvriers disponibles. Minimisation du cout total des penalites de retard (entre 1000 et 2500 euros par chantier).

**Probleme 4 — Localisation de centres de secours (Set Covering)**
Selection du nombre minimum de centres de secours a implanter dans 7 secteurs urbains pour garantir qu'aucun secteur ne soit a plus de 10 minutes d'un centre.

**Probleme 5 — Probleme de Transport et Distribution**
Minimisation du cout total de transport entre 3 usines et 4 centres de distribution, sous contraintes de capacite de production et de demande des centres.

## Competences Mobilisees

- Formulation mathematique de problemes d'optimisation
- Programmation lineaire en variables entieres et continues
- Problemes de couverture (Set Covering)
- Problemes de transport et de flux
- Ordonnancement sous contraintes de ressources

## Auteur

Yacine Yefsah — Master 1 Statistique Appliquee, Universite de Caen Normandie
