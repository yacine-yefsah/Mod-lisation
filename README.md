# 📉 Travaux Pratiques : Recherche Opérationnelle (Master 1 SAAD)

Ce dépôt contient l'intégralité des modélisations et résolutions de problèmes d'optimisation (Programmation Linéaire).

---

### PROBLÈME 1 : Optimisation de la production d'une conserverie de confits
**Énoncé :**
Une conserverie produit des lots de confit "Supérieur" (vendu 3600€) et "Standard" (vendu 3000€). 
* Supérieur : 100kg viande, 6kg truffes.
* Standard : 100kg viande, 5kg truffes.
Stock initial : 500kg viande, 100kg truffes. Achats possibles : viande (12€/kg), truffes (2000€/kg).
**Objectif :** Maximiser le bénéfice net (Ventes - Achats).

---

### PROBLÈME 2 : Planification des effectifs de chauffeurs de bus
**Énoncé :**
Besoins en chauffeurs par créneau : 7h-8h (15), 8h-9h (25), 9h-10h (20), 10h-11h (15), 11h-12h (12).
Un chauffeur travaille 3h consécutives (2h conduite, 1h repos). Embauches possibles à 7h, 8h, 9h, 10h et 11h.
**Objectif :** Minimiser le nombre total de chauffeurs à embaucher.

---

### PROBLÈME 3 : Ordonnancement de chantiers sous contrainte de ressources
**Énoncé :**
Planification de 4 chantiers sur 6 semaines avec 9 ouvriers max. 
* Ch1 : 3 sem (2,3,4 ouvriers), fin souhaitée S3, pénalité 1000€.
* Ch2 : 4 sem (2,4,1,5 ouvriers), fin souhaitée S4, pénalité 2500€.
* Ch3 : 4 sem (3,4,2,2 ouvriers), fin souhaitée S4, pénalité 2000€.
* Ch4 : 3 sem (7,2,3 ouvriers), fin souhaitée S3, pénalité 1500€.
**Objectif :** Minimiser le coût total des pénalités de retard.

---

### PROBLÈME 4 : Localisation de centres de secours (Set Covering)
**Énoncé :**
Une agglomération est divisée en 7 secteurs. On veut implanter des centres de secours de façon à ce que chaque secteur soit à moins de 10 minutes d'un centre. 
* Une matrice de temps de trajet entre les secteurs est fournie.
* Il faut sélectionner un nombre minimum de secteurs où implanter un centre pour couvrir toute la ville.
**Objectif :** Minimiser le nombre de centres tout en garantissant la couverture de tous les secteurs.

---

### PROBLÈME 5 : Problème de Transport et Distribution
**Énoncé :**
Une entreprise possède 3 usines de production et doit livrer 4 centres de distribution.
* Chaque usine a une capacité maximale.
* Chaque centre a une demande spécifique.
* Les coûts de transport par unité entre chaque usine et chaque centre sont connus.
**Objectif :** Minimiser le coût total de transport tout en satisfaisant les demandes et en respectant les capacités.
