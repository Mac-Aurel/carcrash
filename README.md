# Prédiction de la gravité des accidents de circulation avec AutoML

## Description du projet
Ce projet vise à prédire la gravité des accidents de circulation à partir de données réelles fournies par le **Ministère de la Sécurité Routière** pour l'année 2023. L'objectif principal est de développer un système **AutoML** capable de sélectionner, d'entraîner et d'évaluer différents modèles de machine learning afin de fournir des prédictions précises.

## Fonctionnalités
- Prétraitement des données réelles pour extraire les caractéristiques pertinentes.
- Implémentation de plusieurs algorithmes d'apprentissage automatique :
  - **Logistic Regression**
  - **Neural Network**
  - **MLP (Multi-Layer Perceptron)**
  - **XGBoost**
- Automatisation du pipeline de machine learning avec des critères d'arrêt basés sur la stabilité de la perte (**loss**).
- Visualisation et évaluation des performances des modèles.

## Données
Les données utilisées dans ce projet proviennent du **Ministère de la Sécurité Routière** et comprennent des informations sur les accidents de la route en 2023. Ces données incluent des variables telles que :
- Conditions météorologiques
- Types de routes
- Heures de la journée
- Gravitsé des accidents (classée en plusieurs catégories)

## Installation
1. Clonez ce répertoire :
   ```bash
   git clone https://github.com/votre-utilisateur/nom-du-projet.git
   ```
2. Accédez au répertoire :
   ```bash
   cd nom-du-projet
   ```
3. Créez un environnement virtuel et activez-le :
   ```bash
   python -m venv env
   source env/bin/activate # Sous Windows : env\Scripts\activate
   ```

## Utilisation
1. Placez les fichiers de données dans le dossier `data/`.
2. Lancez le script principal :
   ```bash
   python main.py
   ```


## Modèles implémentés
### Logistic Regression
Un modèle statistique de base pour comprendre les relations entre les variables indépendantes et la gravité des accidents.

### Neural Network et MLP
Des réseaux de neurones pour capturer les relations complexes dans les données.

### XGBoost
Un algorithme puissant basé sur les arbres de décision, optimisé pour la précision et la vitesse.

## Prochaines étapes
- Intégration des données de nouvelles années pour enrichir le modèle.
- Déploiement du modèle sous forme d'API.
- Collaboration avec des experts en sécurité routière pour des retours pratiques.
