"# Projet Dragon Ball" 
# 🐉 Dashboard Dragon Ball – Analyse des personnages et planètes via API

Ce projet permet d’explorer l’univers de **Dragon Ball** à travers un tableau de bord interactif basé sur des données collectées automatiquement depuis une **API dédiée**. Il met en avant les personnages emblématiques, les planètes connues de l’anime, ainsi que des statistiques visuelles sur leurs caractéristiques, espèces, affiliations et lieux d’origine.

---

## 🎯 Objectifs

- Utiliser une **API Dragon Ball** pour récupérer dynamiquement les données des personnages, planètes et races
- Structurer et nettoyer les données avec **Python**
- Créer un **modèle de données cohérent** pour la visualisation
- Développer un **tableau de bord interactif** pour l’exploration de l’univers Dragon Ball

---

## 🔄 Pipeline de traitement

1. **Extraction** : 
   - Connexion à l’API (ex. : `https://dragonball-api.com/api`) via des requêtes Python
   - Récupération des entités principales : personnages (`/characters`), planètes (`/planets`), races (`/races`)
   - Traduire la description des personnages
2. **Transformation** :
   - Nettoyage des données (valeurs manquantes, doublons)
   - Standardisation des noms, types, affiliations
   - Formatage en structures tabulaires (DataFrames)
3. **Chargement** :
   - Export en CSV ou liaison directe à Power BI
   - Modélisation dans Power BI (relations, mesures DAX)

---

## 🧰 Technologies utilisées

| Outil / Langage         | Rôle                                                    |
|--------------------------|----------------------------------------------------------|
| **Python (requests, pandas)** | Extraction, transformation, structuration des données   |
| **API Dragon Ball**      | Source des données publiques sur l’univers de la série |
| **Power BI Desktop**     | Modélisation sémantique et visualisation                |
| **Git**                  | Suivi de version et collaboration                       |

---

## 📊 Contenu du tableau de bord

- Liste interactive des **personnages** avec filtres : race, affiliation, planète d’origine
- Fiches synthétiques : **puissance, transformation, statuts (vivant/mort), genre**
- Vue planétaire : **répartition des personnages par planète**
- Graphiques sur les **races les plus fréquentes**, affiliations, genres
- Possibilité de rechercher un personnage précis

---
