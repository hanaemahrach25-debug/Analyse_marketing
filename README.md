# Analyse de Campagne Marketing - Prédiction de Comportement

##  Présentation du Projet
Ce projet analyse un jeu de données de 2 240 clients pour comprendre les habitudes d'achat et optimiser les futures stratégies marketing. L'objectif est de segmenter la clientèle et d'identifier les facteurs clés qui influencent la réponse aux campagnes promotionnelles.

##  Outils & Environnement
* **Environnement : Kaggle Notebooks (GPU P100/T4)
* **Langage : Python 3.11
* **Bibliothèques : Pandas, Seaborn, Scikit-learn
* **Dataset : [Marketing Campaign Dataset](https://www.kaggle.com/code/hanaemahrach/marketing-project/))

##  Étapes du TP

### 1. Préparation des Données
* Chargement du fichier `marketing_campaign.csv` (séparateur `\t`).
* Nettoyage des valeurs manquantes dans la colonne `Income`.
* Conversion des types de données (dates et catégories).

### 2. Feature Engineering
Pour enrichir l'analyse, nous avons créé de nouvelles variables :
* **Age** : Calculé à partir de l'année de naissance.
* **Total_Spent** : Somme des dépenses sur les produits (Vin, Fruits, Viande, Poisson, etc.).
* **Living_With** : Simplification de l'état civil.

### 3. Visualisations Clés

* Distribution des revenus par niveau d'étude.
* Analyse de la corrélation entre l'âge et le montant total dépensé.
* Taux de réponse aux différentes campagnes marketing.

## 4.  Résultats
* Identification d'une corrélation positive entre le revenu et la consommation de vin.
* Les clients avec un niveau d'étude "Master" ou "PhD" représentent le segment le plus rentable.
* Le taux de conversion moyen identifié est de **14.9%**.
