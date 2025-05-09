# 📈 Modélisation Stochastique avec le Processus d'Ornstein-Uhlenbeck

Bienvenue dans ce projet de modélisation stochastique utilisant le **processus d'Ornstein-Uhlenbeck** (OU) 📊.  
Ce processus est largement utilisé en **physique**, **finance**, **biologie**, et dans d'autres disciplines pour modéliser des phénomènes aléatoires ayant un comportement de **réversion à la moyenne**.

---

## 🧠 Objectif du Projet

Ce notebook a pour but de :

- 🔍 Comprendre le fonctionnement théorique du processus OU  
- 🐍 Le simuler à l’aide de Python  
- 📊 Visualiser plusieurs trajectoires stochastiques  
- ⚙️ Étudier l’impact des différents paramètres sur son comportement

---

## 📚 Contexte Mathématique

Le **processus d'Ornstein-Uhlenbeck** est une solution d’une équation différentielle stochastique (EDS) de la forme :


### 🔢 Signification des paramètres

- **Xₜ** : valeur du processus à l’instant t  
- **θ (thêta)** : vitesse de réversion à la moyenne  
- **μ (mu)** : moyenne de long terme (valeur cible)  
- **σ (sigma)** : volatilité du processus (amplitude des perturbations aléatoires)  
- **Wₜ** : mouvement brownien standard (bruit blanc)

### ✨ Propriétés du processus

- **Gaussien** : la distribution de Xₜ est normale  
- **Stationnaire** : il atteint une distribution stable dans le temps  
- **Markovien** : il dépend uniquement de son état présent  

---

## 🛠️ Fichier Inclus

- 📄 `ORNSTEIN_UHLENBECK.ipynb` : notebook contenant :
  - ✅ Code Python complet  
  - 📈 Simulations du processus  
  - 🎨 Visualisations interactives  
  - 🧾 Explications détaillées et pédagogiques  

---

## 🚀 Comment Exécuter le Projet

### 📦 Prérequis

Assurez-vous d’avoir Python installé, ainsi que les bibliothèques suivantes :

```bash
pip install numpy matplotlib pandas seaborn yfinance
