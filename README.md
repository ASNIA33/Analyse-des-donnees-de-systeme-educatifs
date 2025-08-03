# 🌍 Expansion Internationale via Analyse Éducative
Projet Data Science

---

## 📑 Contexte

Academy, une start-up spécialisée dans la formation en ligne pour lycéens et étudiants universitaires, envisage une expansion à l'international. En tant que Data Scientist, vous êtes chargé d’exploiter les données de la Banque Mondiale pour :
- Identifier les pays les plus prometteurs pour s’implanter
- Analyser les besoins éducatifs par pays
- Appuyer les décisions stratégiques par des données concrètes

---

## 🧰 Données utilisées

Les fichiers de la Banque Mondiale utilisés sont :
- `EdStatsCountry.csv`
- `EdStatsCountry-Series.csv`
- `EdStatsData.csv`
- `EdStatsFootNote.csv`
- `EdStatsSeries.csv`

---

## 🧠 Objectifs du projet

- Mener une **analyse exploratoire** des données mondiales sur l’éducation
- **Filtrer et nettoyer** les données (faux pays, valeurs manquantes, redondances)
- **Sélectionner les indicateurs** les plus pertinents pour le secteur EdTech
- Construire un **dataframe agrégé par pays**
- Identifier les **pays avec le plus fort potentiel**
- **Éliminer les indicateurs fortement corrélés**
- Proposer des **visualisations interactives et esthétiques**

---

## 🔎 Étapes clés

### 1. Nettoyage initial
- Suppression des doublons
- Identification et retrait des faux pays
- Traitement des valeurs manquantes

### 2. Réduction par approche métier
- Sélection des catégories : *Education*, *Population*, *Science & Tech*, etc.
- Restriction temporelle : années 2000–2025
- Filtrage des indicateurs non pertinents

### 3. Réduction par approche data
- Calcul de la couverture des données par année et indicateur
- Sélection des indicateurs les plus riches et pertinents (20 max)

### 4. Agrégation des données
- Pivot des données à la maille pays × indicateur
- Calcul de scores moyens par pays

### 5. Analyse de corrélation
- Matrice de corrélation (Pearson & Spearman)
- Suppression des indicateurs trop fortement corrélés (> 70%)

---

## 📊 Visualisations proposées

- Distribution des indicateurs par pays
- Top/Flop des pays en fonction du nombre d’indicateurs renseignés
- Heatmap des corrélations entre indicateurs
- Répartition des scores moyens par pays

---

## 🏁 Résultats clés

- Sélection finale d’environ **20 indicateurs faiblement corrélés**
- Détection de pays à **fort potentiel éducatif** (Inde, Indonésie, Brésil…)
- Données prêtes à être utilisées pour une **modélisation avancée ou segmentation marché**

---

## 💡 Pistes d'amélioration

- Intégration de données économiques complémentaires (revenus, internet, dépenses publiques)
- Construction d’un **score d’opportunité** composite
- Visualisations interactives avec Plotly / Dash / Tableau

---

## 🧪 Environnement technique

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook
- Git / GitHub

---

## 🧑‍💻 Abd Selam M'BODJ

Ce projet a été réalisé dans le cadre d’une formation en Data Science – spécialisation Data Engineer.

