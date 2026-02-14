# Introduction au framework Struts 2 par l’exemple (2012)

🔗 **Cours en ligne :**
[https://stahe.github.io/struts2-janv-2012/](https://stahe.github.io/struts2-janv-2012/)

---

## Présentation

Ce document propose une **introduction au framework Struts 2** à travers une approche progressive basée sur des exemples.

Struts 2 est un framework web Java qui fournit :

* un ensemble de bibliothèques distribuées sous forme de fichiers **JAR**
* un cadre de développement structurant la manière de concevoir une application web

L’objectif est de comprendre les notions fondamentales de Struts 2 par la pratique.

---

## Pré-requis

Pour suivre les exemples, il est nécessaire de disposer :

* de connaissances de base en **Java**
* de connaissances de base en **développement web**, notamment en **HTML**

Des ressources complémentaires sont disponibles sur :

* [http://developpez.com](http://developpez.com)
* [http://tahe.developpez.com](http://tahe.developpez.com)

---

## Code source des exemples

Les exemples présentés dans le document sont disponibles à l’adresse suivante :

[http://tahe.developpez.com/java/struts2](http://tahe.developpez.com/java/struts2)

---

## Références pour approfondir

Pour aller plus loin :

* **[ref1]** Documentation officielle de Struts 2 (site officiel du projet)
* **[ref2]** *Struts 2 in Action*
  Donald Brown – Chad Michael Davis – Scott Stanlick
  Éditions Manning

Le document fait ponctuellement référence à *Struts 2 in Action* pour approfondir certains aspects techniques.

---

## Objectif pédagogique

Le document a été rédigé de manière à pouvoir être lu sans ordinateur.
De nombreuses captures d’écran sont incluses afin de faciliter la compréhension.

---

## Positionnement de Struts 2 dans une application web

Struts 2 intervient **uniquement dans la couche web** d’une architecture multi-couches typique.

### Architecture générale

Une application web classique peut être structurée comme suit :

### 1️⃣ Couche Web

* Interface avec l’utilisateur (navigateur)
* Gestion des requêtes HTTP
* Génération des réponses
* **Struts 2 se situe exclusivement dans cette couche**

### 2️⃣ Couche Métier

* Implémente les règles de gestion
* Exemple : calcul d’un salaire, génération d’une facture
* Utilise :

  * les données issues de la couche web
  * les données provenant de la base via la couche DAO

### 3️⃣ Couche DAO / JPA / JDBC

* Gestion de l’accès aux données
* DAO : Data Access Objects
* JPA : Java Persistence API
* JDBC : accès bas niveau à la base de données
* JPA joue le rôle d’ORM (Object Relational Mapper)

### 4️⃣ Intégration des couches

Peut être assurée par :

* **Spring**
* **Ejb3 (Enterprise Java Bean)**

---

## Organisation des exemples

La majorité des exemples du document utilisent **uniquement la couche Web** afin de se concentrer sur Struts 2.

En fin de document, une **application web multi-couches complète** est construite :

* Couche Web
* Couche Métier
* Couche DAO
* Couche JPA / Hibernate
* Accès base via JDBC

Les couches métier et persistance sont fournies sous forme d’archive JAR afin que le lecteur se concentre principalement sur la couche Web.

---

## Public visé

* Développeurs Java souhaitant découvrir Struts 2
* Étudiants en développement web Java
* Toute personne désirant comprendre l’intégration de Struts 2 dans une architecture multi-couches

---

## Auteur

Cours initialement publié sur developpez.com
Version 2012

---
