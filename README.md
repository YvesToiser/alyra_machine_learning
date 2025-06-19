# Formation Alyra - Développeur Intelligence Artificielle
# Projet de Machine Learning

## Sujet : Estimation du prix de mise à la vente d'un logement (Italie 2022)
## Dataset : https://www.kaggle.com/datasets/tangelus/housing-data-in-italy-august-2022/data
## Type : Prédiction de variables continues à partir d'un apprentissage supervisé
## Date : Juin / Juillet 2025
## Auteur : Yves Toiser
## Modèles potentiellement utilisés : 
Différents modèles de Machine Learning peuvent être utilisés pour ce type de prédictions : 
- Régression Linéaire (Linear Regression)
- Régression pénalisée (Ridge, Lasso, Elastic net)
- Support Vecteur Machine (SVM)
- Forêts aléatoires (Random Forests)
- Boosting (Ada Boost, Gradient Boosting, XG Boost)
- K-NN (K nearest neighbors)

## Process : 
1. Exploration des données.  
2. Traitement des données.  
A l'issue du traitement des données, on sélectionnera plusieurs jeux de données ainsi subit différents traitements pour en comparer les résultats avec les différents modèles.
3. Création, et entraînements des modèles.
4. Evaluation des modèles.  
Avec les résultats des différents modèles couplés avec les différents jeux de données, on sélectionnera les stratégies d'optimisations.

## 1. Exploration des Données :


## 2. Traitement des Données : 
### Nettoyage des Données
- Suppression des données inutiles  
- Suppression des lignes et colonnes avec trop de valeurs manquantes (ou valeurs clés)
- Traitement des outliers
- Imputation de données manquantes
### Séparation des Données
- Séparation des données x (features) & y (cibles)
- Séparation du jeu d'entrainement et du jeu de validation
### Pipeline de preprocessing
- One Hot Encoding des variables catégorielles
- Scaling des valeurs numériques
- Feature Engineering
- Discrétisation (Binning)

## 3. Création et entraînement des Modèles :


## 4. Evaluation des Modèles :