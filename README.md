# Description du projet
Ce projet R a pour objectif de prédire si un patient est susceptible de faire un accident vasculaire cérébral (AVC) à partir de différentes caractéristiques médicales et démographiques.

Nous avons utilisé plusieurs modèles de machine learning pour comparer leurs performances et identifier celui qui prédit le mieux le risque.

# Données
- Les données contiennent des informations sur les patients : âge, sexe, antécédents médicaux, habitudes de vie, etc.

- Les variables sont à la fois numériques et catégorielles, et certaines ont été transformées ou normalisées pour les besoins des modèles.

# Modèles utilisés
-KNN (K-Nearest Neighbors)
- SVM linéaire et radial (Support Vector Machines)
- Random Forest (Forêt aléatoire)
- Arbres de décision
- Régression logistique
- Boosting

Chaque modèle a été évalué via des matrices de confusion, des taux de précision et des courbes ROC.

# Méthodologie
- Prétraitement des données : nettoyage, gestion des valeurs manquantes, encodage des variables catégorielles
- Séparation train/test : division des données en ensembles d’entraînement et de test
- Entraînement des modèles : utilisation de plusieurs algorithmes de machine learning
- Évaluation et comparaison : analyse des performances avec la matrice de confusion, précision, rappel et courbes ROC.

# Utiisations
- Packages : caret, randomForest, e1071, ggplot2


