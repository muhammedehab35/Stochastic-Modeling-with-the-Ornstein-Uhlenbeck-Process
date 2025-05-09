# 📈 Modélisation Stochastique avec le Processus d'Ornstein-Uhlenbeck

Bienvenue dans ce projet de modélisation stochastique utilisant le **processus d'Ornstein-Uhlenbeck** (OU) 📊. Ce processus est largement utilisé en physique, en finance, en biologie et dans de nombreux autres domaines pour modéliser des phénomènes aléatoires avec un comportement de **réversion à la moyenne**.

---

## 🧠 Objectif du Projet

L'objectif de ce notebook est de :

- Comprendre le fonctionnement théorique du processus OU 🔍
- Simuler le processus à l’aide de Python 🐍
- Visualiser plusieurs trajectoires possibles 🧮
- Étudier l’impact des différents paramètres du modèle 📉

---

## 📚 Contexte Mathématique

Le **processus d'Ornstein-Uhlenbeck** est une solution d'une **équation différentielle stochastique (EDS)** de la forme :

```math
dXₜ = θ(μ - Xₜ)dt + σdWₜ

Signification des paramètres :
Xₜ : variable aléatoire du processus à l'instant t

θ (thêta) : vitesse de réversion à la moyenne

μ (mu) : moyenne de long terme vers laquelle le processus revient

σ (sigma) : volatilité du processus (amplitude des variations aléatoires)

Wₜ : mouvement brownien standard (bruit aléatoire continu)

💡 Ce processus est gaussien, stationnaire et markovien. Il est souvent considéré comme une généralisation du mouvement brownien, avec un terme de réversion.

🛠️ Fichiers Disponibles
ORNSTEIN_UHLENBECK.ipynb : le notebook principal contenant le code, les visualisations et les commentaires explicatifs.


🔬 Applications du Processus OU
Voici quelques domaines où le processus d'Ornstein-Uhlenbeck est utilisé :

💸 Finance : Modélisation des taux d’intérêt (modèle de Vasicek), volatilité, etc.

🧪 Physique : Mouvement brownien avec frottement (équation de Langevin)

🧬 Biologie : Évolution de caractères (phylogénie), signaux neuronaux

🌡️ Thermodynamique : Comportement des particules dans un fluide visqueux

