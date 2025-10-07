# TP1 — Injection de Dépendances et Couplage faible en Java

##  Objectif du TP
L’objectif de ce TP est de comprendre le **principe d’injection de dépendances** (Dependency Injection) en Java, en s’appuyant sur la **programmation dynamique et la réflexion**.

Le but est de montrer comment relier des classes (DAO, Métier, Présentation) de manière **dynamique à l’exécution (run-time)** plutôt que statique à la compilation.

---

##  Concepts abordés
- **Injection de dépendances** : séparation entre la logique métier et l’accès aux données.  
- **Réflexion** : création dynamique d’objets à partir du nom de classe.  
- **Assemblage dynamique** des composants (DAO, Métier) au moment de l’exécution.  
- **Couplage faible** entre les classes.

---

##  Architecture du projet

TP1/
│src
├── dao/
│ ├── IDao.java
│ └── DaoImpl.java
│
├── metier/
│ ├── IMetier.java
│ └── MetierImpl.java
│
└── presentation/
└── Presentation2.java
└config.txt


##  Auteur

Douaa BOUSTANE
Étudiante en ingénierie informatique – EMSI Marrakech
TP réalisé dans le cadre du module Microservices.
