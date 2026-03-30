# Sales-analysis-report

Ce projet présente un tableau de bord Power BI permettant d’analyser les ventes d’une entreprise à l’échelle internationale.

## 📥 Téléchargement du fichier Power BI

Vous pouvez télécharger le fichier POWER BI et l'ouvrir sur Power BI desktop ici :
👉 https: https://drive.google.com/drive/u/0/folders/19yP4SZy8IvOuLNg1kRnv24dkBBs6Lq9W
En parallèle, je vous ai mis des photos et captures de mon travail.

##  Objectifs

L’objectif de ce dashboard est de :
- Suivre les performances commerciales globales
- Analyser le chiffre d’affaires et le profit
- Identifier les zones géographiques les plus performantes
- Comprendre la répartition des ventes par catégorie de produits
- Évaluer les performances logistiques (transporteurs)

---

##  Jeu de données

Les données proviennent de plusieurs sources (Excel, CSV, TXT) :

- Données géographiques (Geo data)
- Informations produits (Product information)
- Détails fabricants (Manufacturers)
- Ventes USA (USA Sales)
- Ventes internationales (Australia, Canada, France, Germany, Japan, Mexico, Nigeria…)

Les données ont été intégrées et transformées via **Power Query**.

---

## Préparation des données (Power Query)

- Import de plusieurs fichiers (multi-sources)
- Fusion des données de ventes internationales
- Nettoyage des colonnes
- Harmonisation des formats (dates, nombres)
- Création d’un modèle de données cohérent

---

##  Modèle de données

Le modèle est structuré en schéma en étoile :

- **Table de faits :**
  - `Sales`

- **Tables de dimensions :**
  - `Product`
  - `Location`
  - `Shipper`
  - `Calendar`

---

##  Mesures DAX

Les principaux indicateurs calculés :

- Total Revenue
- Total Profit
- Nombre de ventes
- Analyse temporelle (par année)
- KPI de performance

---

##  Visualisations

Le dashboard contient plusieurs analyses :

###  Répartition du chiffre d’affaires par catégorie
- Donut chart
- Identification des catégories dominantes

###  Nombre de ventes par transporteur
- Bar chart
- Analyse de la performance logistique

### Profit par pays
- Carte géographique
- Visualisation internationale des performances

###  Évolution du chiffre d’affaires et du profit
- Line chart
- Analyse des tendances dans le temps

---

##  Insights principaux

- Certaines catégories de produits génèrent une part importante du chiffre d’affaires
- Les performances varient fortement selon les pays
- Les transporteurs ont un impact sur le volume de ventes
- La croissance du chiffre d’affaires est corrélée à celle du profit

---

##  Outils utilisés

- Power BI Desktop
- Power Query
- DAX

---

##  Aperçu

![Dashboard](images/dashboard.png)


<img width="1347" height="746" alt="image" src="https://github.com/user-attachments/assets/b8a9a388-4d7f-4b63-93bf-d5efbf37b7d7" />

---

##  Auteur

Tamsir Dione
