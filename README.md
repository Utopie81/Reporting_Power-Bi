# Projet power bi : analyse de la consommation énergétique des habitations en France

---

## **Aperçu du projet**

Ce projet power bi analyse la consommation énergétique des habitations en France, en mettant l’accent sur des aspects clés tels que les étiquettes énergétiques (DPE), les types de logements, les régions et les usages énergétiques. Le rapport offre des visualisations interactives et des insights pour aider les décideurs à identifier les tendances et à optimiser l’efficacité énergétique.

---

## **Fonctionnalités**

- **Carte interactive** : visualise la répartition géographique des habitations par région, étiquette DPE et type.
- **Filtres dynamiques** : permet aux utilisateurs de filtrer dynamiquement les données par type de logement, étiquette DPE, région et commune.
- **Analyse comparative** : fournit des comparaisons détaillées des consommations énergétiques entre les communes.
- **Navigation dynamique** : inclut des boutons intuitifs pour naviguer entre les pages.
- **Sécurité basée sur les rôles** : restreint l’accès aux données par région grâce à la sécurité au niveau des lignes (RLS).

---

## **Pages du rapport**

1. **Page de filtre** :
   - **Objectif** : filtrer l’ensemble des données par type de logement, étiquette DPE et localisation géographique.
   - **Visualisation clé** : carte interactive avec des segments dynamiques.

2. **Analyse des logements** :
   - **Objectif** : résumer les répartitions des logements par étiquette DPE, type de chauffage et type de logement.
   - **Visualisations clés** : histogrammes, diagrammes circulaires et cartes récapitulatives.

3. **Consommation et confort énergétiques** :
   - **Objectif** : évaluer les coûts énergétiques et le confort des logements par étiquette DPE.
   - **Visualisations clés** : graphiques en barres montrant les coûts énergétiques moyens et la consommation.

4. **Comparaison des communes** :
   - **Objectif** : comparer les indicateurs de consommation énergétique entre différentes communes.
   - **Visualisations clés** : histogrammes, tableaux comparatifs et métriques récapitulatives.

---

## **Détails techniques**

- **Modèle de données** : schéma en étoile avec une table centrale des faits (`Base_Donnée`) et des dimensions pour les régions, communes, étiquettes DPE, types de logements et catégories de bâtiments.
- **Sécurité basée sur les rôles (RLS)** :
  - configurée pour restreindre l’accès aux données par région pour des rôles spécifiques.

---

## **Instructions d’utilisation**

1. ouvrez le fichier `.pbix` dans power bi desktop ou allez directement sur power bi online la où il est publié.
2. testez la sécurité RLS en visualisant le rapport sous différents rôles.
3. utilisez les segments et les boutons interactifs pour naviguer et filtrer les données.

---

## **Fichiers du projet**

- `Power_Bi_Final.pbix` : le fichier principal du rapport power bi.
- `README.md` : ce document.
- `Documentation_Fonctionnelle.pdf` : documentation fonctionnelle pour les utilisateurs finaux.
- `Documentation_Technique.pdf` : documentation technique pour les développeurs.
  
---
