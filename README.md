# Projet GPS - Algorithmes et Structures de Données

## Description

Ce projet consiste en une implémentation en langage C de différents algorithmes et structures de données visant à résoudre des problèmes typiques tels que celui du loup, de la chèvre et du chou, ainsi que des exemples spécifiques fournis (blocks, monkey, school). Il intègre plusieurs fichiers sources, d'en-têtes et des fichiers textes de tests.

## Structure du Projet

La structure du projet est organisée comme suit :

```
fwdprojetsael1/
├── main.c                     # Fichier principal contenant la fonction main
├── functions.c                # Fichier source contenant les fonctions principales
├── functions.h                # Fichier d'en-tête définissant les fonctions principales
├── parseFunctions.c           # Fonctions de parsing de données depuis fichiers
├── parseFunctions.h           # Déclarations des fonctions de parsing
├── structures.h               # Déclarations des structures de données
├── blocks.txt                 # Fichier texte d'exemple "blocks"
├── monkey.txt                 # Fichier texte d'exemple "monkey"
├── wolf&goat&cabbage.txt      # Exemple classique du problème du loup, chèvre et chou
├── school.txt                 # Fichier texte d'exemple "school"
└── Rapport de fin de projet GPS, MEDJANI Elyes & KECHIR Amine.pdf # Rapport détaillé
```

## Fonctionnalités

* **Algorithmes de résolution de problèmes classiques**
* **Lecture et parsing de fichiers texte pour initialiser les données**
* **Structures de données optimisées pour la gestion d'états**
* **Rapport détaillé décrivant les choix techniques et les résultats obtenus**

## Instructions d'utilisation

### Compilation

Compilez le projet avec la commande suivante :

```bash
gcc -o projet main.c functions.c parseFunctions.c
```

### Exécution

Lancez l'exécutable avec l'un des fichiers d'exemple en paramètre :

```bash
./projet blocks.txt
```

ou

```bash
./projet wolf&goat&cabbage.txt
```

### Fichiers de test disponibles

* `blocks.txt`
* `monkey.txt`
* `wolf&goat&cabbage.txt`
* `school.txt`

## Prérequis

* Compilateur `gcc`
* Environnement Unix/Linux

## Auteurs

* Amine KECHIR

## Licence

Ce projet est soumis à une licence 1 informatoque.

---

**Bon courage dans l'utilisation et l'exploitation de ce projet !**
