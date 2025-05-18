# Auteurs

- Kaouther MAKHLOUF
- Wajd MESKINI  

# Abstract

L’objectif de ce travail est de tester des méthodes de régressions robustes (Régression Logistique et Régression Lasso) dans un contexte de classification binaire :

- **Régression Logistique** comme modèle principal.  
- **Régression Lasso** pour prédire une variable quantitative influente dans le jeu de données, afin d’étudier l’impact de l’**imputation de valeurs manquantes avec des modèles** sur l’évaluation finale.  
- Toutes les évaluations intermédiaires sont réalisées par validation croisée dans le but de maximiser le **score F1**, l’évaluation finale se faisant sur un jeu de données d’évaluation indépendant.  
- Impact de l’**optimisation automatique des seuils** de décision (pour fixer la probabilité à partir de laquelle une prédiction est 1) et de l’**optimisation automatique des hyperparamètres** des modèles (y compris le choix des optimiseurs).  

# Keywords

Régression Logistique · Lasso · Imputation des valeurs manquantes · Optimisation automatique des hyperparamètres · Optimisation automatique des seuils de décision

# Fichiers

- Un pdf avec le rapport et les interprétations
- Un ipynb contenant le code Python exécutable sur Colab. Visualisable sur Github
- Un rmd contenant le code exécutable sur Rstudio
- Un html téléchargeable contenant la sortie du code rmd
- La donnée titanic.csv

# Instructions

- Si besoin de visualiser rapidement le code, ouvrez le code ipynb directement sur github, il s'affiche correctement
- Si besoin d'exécuter sur Rstudio, utilisez le rmd. Le knit télécharge Python, prépare un environnement et exécute le code 
- Si besoin de visualiser en local la sortie du rmd, téléchargez le html et ouvrez le sur votre navigateur
- Dans tous les cas, le code télécharge titanic.csv depuis github, et a donc besoin d'accéder à Internet
