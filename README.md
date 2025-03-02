## Introduction

Ce projet contient plusieurs exercices en JavaScript. Ces exercices ont été conçus pour pratiquer les différents concepts en HTML,Css et JavaScript et interaction avec l'utilisateur.

---

## **Exercice 1 : Échanger les Valeurs de Deux Champs de Texte**

**Objectif** :  
Créer une page web simple avec deux champs de texte et un bouton pour échanger les valeurs saisies dans les deux champs de texte.

### Fonctionnalités principales :
- Deux champs de texte (`t1`, `t2`).
- Un bouton qui, lorsqu'il est cliqué, échange les valeurs des deux champs.
- Utilisation de JavaScript pour gérer la logique d'échange des valeurs.

### Fonctionnement :
1. L'utilisateur saisit des valeurs dans les deux champs de texte.
2. En cliquant sur le bouton "Permuter", une fonction JavaScript échange les valeurs des deux champs.

---

## **Exercice 2 : Calculatrice Simple**

**Objectif** :  
Créer une calculatrice de base permettant d'effectuer des opérations arithmétiques (addition, soustraction, multiplication, division) sur deux valeurs saisies.

### Fonctionnalités principales :
- Deux champs de texte pour saisir des nombres.
- Quatre boutons (`+`, `-`, `*`, `/`) pour les opérations arithmétiques de base.
- Un champ de résultat pour afficher le résultat de l'opération.
- Utilisation de JavaScript pour effectuer les calculs et mettre à jour le résultat en fonction de l'opération sélectionnée.

### Fonctionnement :
1. L'utilisateur entre deux nombres.
2. L'utilisateur peut choisir une opération (`+`, `-`, `*`, `/`).
3. Lorsque l'utilisateur clique sur un bouton d'opération, la fonction JavaScript effectue le calcul correspondant et affiche le résultat.
4. Un contrôle des erreurs est inclus, comme la gestion des entrées invalides et la division par zéro.

---

## **Exercice 3 : Calculateur de l'IMC (Indice de Masse Corporelle)**

**Objectif** :  
Construire un calculateur d'Indice de Masse Corporelle (IMC) qui calcule et affiche l'IMC en fonction du poids et de la taille de l'utilisateur, avec une interprétation du résultat.

### Fonctionnalités principales :
- Deux champs de texte (`t1` pour le poids en kg, `t2` pour la taille en mètres).
- Un bouton qui déclenche le calcul de l'IMC.
- Un champ de résultat affichant l'IMC calculé et une interprétation du résultat en fonction des plages de l'IMC (insuffisance pondérale, poids normal, surpoids, etc.).
- Utilisation de JavaScript pour effectuer le calcul de l'IMC et fournir une interprétation du résultat.

### Fonctionnement :
1. L'utilisateur entre son poids et sa taille.
2. En cliquant sur le bouton "Calculer", l'IMC est calculé en utilisant la formule :  
   \[ \text{IMC} = \frac{\text{Poids (kg)}}{\text{Taille}^2 (\text{m}^2)} \]
3. L'IMC calculé est affiché avec un message indiquant la catégorie de l'IMC (par exemple : insuffisance pondérale, normal, surpoids).
4. Un contrôle des erreurs pour les entrées non numériques est inclus.

---

## **Exercice 4 : Calculatrice Scientifique**

**Objectif** :  
Créer une calculatrice scientifique avancée avec diverses fonctions, y compris des fonctions trigonométriques, logarithmiques, et des opérations arithmétiques de base.

### Fonctionnalités principales :
- Une zone d'affichage qui montre l'entrée actuelle ou le résultat.
- Des boutons pour diverses fonctions mathématiques, y compris :
  - Opérateurs de base : `+`, `-`, `×`, `÷`.
  - Fonctions trigonométriques : `sin`, `cos`, `tan`.
  - Fonctions logarithmiques : `log`, `ln`.
  - Constantes : `π`, `e`.
  - Opérations de puissance : `x²`, `xⁿ`.
  - Fonction racine carrée : `√`.
  - Autres fonctions : `EXP`, `Inv`, et `π`.
  - Un bouton égal pour effectuer le calcul et afficher le résultat.
- Un bouton de réinitialisation (`CE`) pour effacer l'entrée.

### Fonctionnement :
1. L'utilisateur peut saisir des nombres et des opérations mathématiques en utilisant les boutons de la calculatrice.
2. En cliquant sur le bouton "=" le résultat du calcul est effectué, avec la gestion des diverses opérations comme l'exponentiation, les fonctions trigonométriques, et les logarithmes.
3. Si l'utilisateur entre des valeurs invalides ou si l'opération provoque une erreur, la calculatrice affiche "Erreur".
4. JavaScript est utilisé pour traiter les entrées utilisateur et effectuer les calculs, y compris la gestion des constantes mathématiques et des fonctions.

---

## **Comment Exécuter les Exercices :**

Pour exécuter ces exercices :
1. Sauvegardez le code HTML de chaque exercice dans des fichiers `.html` séparés (par exemple `exercice1.html`, `exercice2.html`, etc.).
2. Ouvrez les fichiers HTML dans un navigateur web pour tester leur fonctionnement.

---

## **Technologies Utilisées :**
- **HTML** : Structure et mise en page de la page.
- **CSS** : Stylisation de l'interface utilisateur.
- **JavaScript** : Logique pour le fonctionnement des champs de saisie, des calculs et de l'interaction utilisateur.

---



