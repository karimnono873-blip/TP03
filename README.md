# 🐸 Jeu de Saute-Mouton - TP POO (Java)

![Java Version](https://img.shields.io/badge/Java-11%2B-blue?style=for-the-badge&logo=java)
![Status](https://img.shields.io/badge/Status-Complété-success?style=for-the-badge)
![USTHB](https://img.shields.io/badge/USTHB-FGE-violet?style=for-the-badge)

Ce dépôt contient la solution en Java pour le **TP N°3 : Programmation des systèmes par les méthodes de POO**, réalisé dans le cadre du module de Programmation Orientée Objet (M1 AII - Automatique). 

Le projet implémente l'algorithme classique du casse-tête **Saute-Mouton**, permettant d'interagir via la console en respectant des règles de déplacement strictes.

---

## 📋 Table des matières
1. [À propos du projet](#-à-propos-du-projet)
2. [Règles du jeu](#-règles-du-jeu)
3. [Fonctionnalités](#-fonctionnalités)
4. [Installation et Exécution](#-installation-et-exécution)
5. [Structure du Code](#-structure-du-code)
6. [Auteur](#-auteur)

---

## 💡 À propos du projet

L'objectif de ce TP est d'appliquer les concepts de la Programmation Orientée Objet (POO) en Java à travers la modélisation et la résolution d'un problème algorithmique.

**Contexte académique :**
* **Université :** USTHB (Université des Sciences et de la Technologie Houari Boumediene)
* **Faculté :** FGE (Génie Électrique) - Département d'Automatique
* **Niveau :** Master 1 AII
* **Enseignant :** M. MENANI

---

## 🎯 Règles du jeu

Sur un plateau d'une dimension définie par l'utilisateur, des pions **Noirs (N)** sont placés à gauche et des pions **Rouges (R)** à droite, séparés par une **case vide ( )**. 

* **But :** Déplacer tous les pions Rouges vers la gauche et tous les pions Noirs vers la droite. La case vide doit revenir au centre à la fin de la partie.
* **Déplacements autorisés :**
  * Les pions **Noirs** se déplacent uniquement vers la **droite**.
  * Les pions **Rouges** se déplacent uniquement vers la **gauche**.
  * Un pion peut avancer d'une case si la case adjacente est vide.
  * Un pion peut "sauter" par-dessus **un seul** pion de couleur opposée si la case suivante est vide.

---

## ✨ Fonctionnalités

* **Initialisation dynamique :** L'utilisateur définit le nombre de pions par équipe (Maximum 10).
* **Interface console interactive :** Affichage en temps réel de l'état du plateau et des index.
* **Moteur de validation :** Vérification stricte de chaque coup joué (coups permis vs coups interdits).
* **Détection de fin de partie :** * Algorithme de détection de victoire (configuration finale atteinte).
  * Algorithme de détection de situation de blocage (aucun mouvement possible).
* **Boucle de jeu :** Possibilité de relancer une nouvelle partie sans redémarrer le programme.

---

## 🚀 Installation et Exécution

### Prérequis
Assurez-vous d'avoir le [JDK (Java Development Kit)](https://www.oracle.com/java/technologies/downloads/) installé sur votre machine.

### Instructions

1. **Cloner le dépôt** (ou télécharger le fichier `SauteMouton.java`) :
   ```bash
   git clone <votre-lien-github>
   cd <nom-du-dossier>
