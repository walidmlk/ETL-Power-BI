# Projet Business Intelligence - Northwind avec Power BI

##  Description
Projet de création d'un entrepôt de données (Data Warehouse) en modèle étoile 
à partir de la base Northwind, avec visualisations interactives dans Power BI.

##  Objectifs
- Créer un processus ETL avec Power Query
- Modéliser un Data Warehouse (3 dimensions + 1 table de faits)
- Développer des visualisations Python et Power BI natives

##  Technologies utilisées
- **Power BI Desktop** (version 2024)
- **SQL Server** / **Microsoft Access**
- **Python** (matplotlib, pandas)
- **Power Query M** (langage ETL)
- **DAX** (Data Analysis Expressions)

##  Structure du projet
Projet_BI_PowerBI/
├── Rapport/              # Documentation LaTeX et PDF
├── Donnees_Sources/      # Bases de données sources
├── Scripts_PowerQuery/   # Scripts M pour ETL
├── Scripts_Python/       # Visualisations Python
├── Fichiers_PowerBI/     # Fichiers .pbix
├── Video/                # Video explicative du projet 
└── Documentation/        # Ce dossier

##  Démarrage rapide

### Prérequis
- Power BI Desktop installé
- Python 3.8+ avec matplotlib et pandas
- SQL Server ou Microsoft Access

### Installation
1. Cloner/télécharger le projet
2. Ouvrir `Fichier_PowerBI/Projet_BI.pbix`
3. Configurer les sources de données (voir Guide_Installation.pdf)
4. Rafraîchir les données

### Utilisation
- **Vue Rapport** : Consulter les dashboards interactifs
- **Vue Données** : Explorer les tables (dimensions et faits)
- **Vue Modèle** : Voir les relations du modèle en étoile

##  Résultats
- **3 dimensions** : DimEmployee, DimClient, DimTemps
- **1 table de faits** : TF_Commande (~878 lignes)
- **6 visualisations** : 4 Python + 2 Power BI natives

##  Documentation complète
Voir le fichier `Rapport/Rapport.pdf` pour la documentation détaillée.

##  Auteur
** MALEK CHAKIB WALID **  

