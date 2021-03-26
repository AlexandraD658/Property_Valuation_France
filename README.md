---
title: 'Demande de valeurs foncières'
disqus: hackmd
---

Demande de valeurs foncières
===
![downloads](https://img.shields.io/github/downloads/atom/atom/total.svg)

## Sommaire 

[TOC]

## Présentation du projet

Le but de ce projet est de **prédire la valeur d’un bien immobilier** au travers d'algortihmes de **Machine Learning**.
Plusieurs stratégies ont été mises en place afin de fournir une analyse approfondie et répondre aux problématiques métiers.

Pour la prédiction, nous étudierons uniquement les données des villes suivantes : 
- Paris
- Nantes
- Toulouse

Trouvez également  ci-dessous la liste des outils utilisés pour ce projet : 

- **Python** et ses librairies (sklearn, pandas, sns, matplot...)
- **Anaconda**
- **Power BI**  
    
Le jeu de données demande de valeurs foncières géolocalisées est disponible sur le site officiel [data.gouv](https://www.data.gouv.fr/fr/datasets/5c4ae55a634f4117716d5656/)





Pipeline 
---
* Collecte de données
```
La source de données est une dérivée du jeu de données diffusé par la DGFiP.
Il propose un format alternatif avec une géolocalisation.
```
* Nettoyage des données
```
1. Filtres sur le Dataset : Type de mutation, date de mutation, type de bien..
2. Gestion des valeurs manquantes et abbérantes
```
* Réduction des dimensions et labeling
```
1. Transformation des variables catégorielles 
2. Standardisation des données
```

* Model validation | Visualisation
```
1. Analyse du score 
2. Analyse de différentes métriques
```

Problématiques métiers
---
Liste des problématiques métiers traitées:

- Répartition des différents types de biens.
- Distributuon du nombre de biens vendus en fonction du nombre de pièces disponibles.
- Évolution du nombre de ventes en fonction des années .
- Répartition géographique du nombre de biens vendus.

```
Exemple de visualisation sur PowerBI
```

![](https://i.imgur.com/OuqJTWn.jpg)




Prédiction du prix au m²
---
```
Comparaison des modèles Machine Learning 
```
![](https://i.imgur.com/jdngQZS.png)

---
Merci! :+1: 
Trouvez moi sur:
- GitHub
- LinkedIn 
- Email
