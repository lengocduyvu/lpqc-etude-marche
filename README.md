![Title](gfx/lpqc_title.jpg)

# Etude de marché

## Description
**"La Poule Qui Chante"** 🐓, une entreprise française d'agroalimentaire dont l'activité principale est l'élevage et la vente de poulets sous le label "Poulet Agriculture Biologique", souhaite se développer à l'international.

L'objectif de cette étude est de proposer une **analyse des groupements de pays cibles pour l'export du poulet**.

## Structure du projet
- `data/` :         Contient les jeux de données utilisés pour le projet.
- `notebooks/` :    Contient les notebooks Jupyter utilisés pour l'analyse des données.
- `gfx/` :          Contient les graphiques utilisés.
- `reports/` :      Contient les rapports générés à partir des analyses.

## Première partie : Analyse exploratoire
- Vérification et nettoyage des jeux de données
- Fusion
- Sélection des pays suivant plusieurs critères
- Export du dataframe final

## Deuxième partie : Clustering et Visualisations
- Analyses descriptives
- Analyse en composantes principales
- Classification ascendante hiérarchique
- K-means
- Pays candidats

## Prérequis
- Python 3.x
- Jupyter Notebook
- Bibliothèques Python : pandas, numpy, matplotlib, seaborn, scikit-learn

## Installation
1. Clonez le dépôt :
    ```bash
    git clone https://github.com/lengocduyvu/lpqc-etude-marche.git
    ```
2. Installez les dépendances :
    ```bash
    pip install -r requirements.txt
    ```

## Utilisation
1. Lancez Jupyter Notebook :
    ```bash
    jupyter notebook
    ```
2. Ouvrez et exécutez les notebooks dans le dossier `notebooks/`.

## Auteur
- Ngoc LE (https://github.com/lengocduyvu)