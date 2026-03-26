# 🍕 PizzaRecipes App

## 📱 Description
PizzaRecipes est une application Android développée en Java qui permet d’afficher une liste de pizzas avec leurs informations (image, nom, durée, prix) et d’accéder à un écran de détails complet pour chaque recette.

---

## 🎯 Objectifs du TP
Ce projet permet de comprendre :

- L’architecture d’un projet Android (DAO / Service / Adapter / UI)
- L’utilisation d’une ListView avec un adapter personnalisé
- Le passage de données entre activités (Intent)
- La gestion d’un Splash Screen
- La modélisation orientée objet avec une classe Produit

---

## 🧱 Architecture du projet
```
com.example.pizzarecipes
│
├── classes
│ └── Produit.java
│
├── dao
│ └── IDao.java
│
├── service
│ └── ProduitService.java
│
├── adapter
│ └── PizzaAdapter.java
│
└── ui
├── SplashActivity.java
├── ListPizzaActivity.java
└── PizzaDetailActivity.java

```
---

## 🚀 Fonctionnalités

- Splash Screen au démarrage  
- Affichage d’une liste de pizzas  
- Design moderne avec CardView  
- Navigation vers un écran détail  
- Affichage des :
  - ingrédients  
  - description  
  - étapes  

---

## 🖼️ Screenshots

### 🔴 Splash Screen
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/6807990d-99e0-4390-bc5f-f847097d725c" />


### 📋 Liste des pizzas
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/575daeb1-74d5-4f1e-8979-b5ee0a9c18b4" />


### 📖 Détail d’une pizza
<img width="1080" height="2400" alt="image" src="https://github.com/user-attachments/assets/c5385dab-3863-4b54-bb2f-76a208828100" />



---

## ⚙️ Technologies utilisées

- Java
- Android SDK
- ListView
- Adapter personnalisé (BaseAdapter)
- CardView
- Intent

---

## 👨‍💻 Auteur
**Nom : SOUKAINA IMAGHRI**
**Encadré par : M. LACHGAR**
**Lab Android – PizzaRecipes**
