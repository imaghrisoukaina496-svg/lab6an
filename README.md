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
<img width="391" height="797" alt="image" src="https://github.com/user-attachments/assets/97e65456-92ac-4052-ab92-8f6dfaca10d8" />


### 📋 Liste des pizzas
<img width="379" height="791" alt="image" src="https://github.com/user-attachments/assets/f3a231a3-dcc6-4664-a22d-30cd118caf92" />


### 📖 Détail d’une pizza
<img width="373" height="793" alt="image" src="https://github.com/user-attachments/assets/62c87a4f-58c8-4681-88f9-3d057b4332e3" />


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
