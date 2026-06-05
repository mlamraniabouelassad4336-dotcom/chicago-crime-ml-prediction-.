# Chicago Crime Arrest Prediction - Machine Learning Pipeline

##  Description du Projet ML
Ce projet a été réalisé dans le cadre d'un mini-projet d'apprentissage supervisé (classification binaire). L'objectif est de prédire si un incident criminel à Chicago aboutira à une arrestation (`arrest` : True/False) en se basant sur des caractéristiques clés telles que le type d'infraction, la zone géographique (police district) et la nature domestique de l'incident.

Le projet comprende l'ensemble du pipelin de Data Science :
1. Extraction et chargement des données réelles via l'API de la ville de Chicago.
2. Exploration, analyse de la distribution de la variable cible et visualisation (EDA).
3. Prétraitement des données (gestion des valeurs manquantes, encodage catégoriel, fractionnement Train/Test).
4. Entraînement et évaluation comparative de deux modèles de classification.

##    Données (Dataset)
Le dataset provient du portail de données publiques de la ville de Chicago (*Chicago Crime Dataset*). 
* **Dimensions de l'échantillon :** 1 000 lignes et 22 colonnes.
* **Variable Cible (`arrest`) :** Fortement déséquilibrée (Class Imbalance), reflétant la réalité du terrain :
  * **Pas d'arrestation (False) :** 848 cas (~84.8%)
  * **Arrestation (True) :** 152 cas (~15.2%)

##  Technologie Utilises
* **Langage :** Python 3
* **Environnement :** Google Colab
* **Librairies principales :** * `pandas` & `numpy` (Manipulation des données)
  * `matplotlib` & `seaborn` (Visualisation des données)
  * `scikit-learn` (Prétraitement et Machine Learning)

##  Struccture du Projet
```text
├── Chicago_Crime_ML.ipynb   # Notebook Google Colab contenant tout le code exécutable
└── README.md                # Documentation du projet
