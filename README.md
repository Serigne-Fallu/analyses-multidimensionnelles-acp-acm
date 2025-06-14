# 📊 Analyse des Correspondances Multiples (ACM)

Ce projet applique l’**Analyse des Correspondances Multiples (ACM)** pour explorer un tableau de données où les individus sont décrits par des **variables qualitatives**.

L’objectif est de résumer l'information, d'identifier des profils d'individus similaires, et de mettre en évidence les liaisons entre modalités des variables.

---

## 🎯 Objectifs

- Étudier les **ressemblances entre individus** en fonction de plusieurs variables qualitatives.
- Détecter et visualiser les **associations entre modalités**.
- Réduire la complexité des données tout en conservant l’essentiel de l’information.
- Dégager des **profils d’individus** ou des structures latentes dans les données.

---

## 🧪 Données

- **Type** : Données d’enquête ou d’observation (qualitatives)
- **Format** : Tableau croisé individus × variables qualitatives
- **Prétraitement** : Encodage des modalités, gestion des valeurs manquantes

---

## 🧭 Méthodologie

1. **Chargement des données**
2. **Encodage des variables qualitatives**
3. **Application de l’ACM** avec `FactoMineR`
4. **Visualisation** :
   - Graphiques des individus
   - Graphiques des modalités
   - Contributions aux axes

---

## 🛠️ Outils utilisés

- `R`
- Packages : `FactoMineR`, `factoextra`, `ggplot2`, `tidyverse`

---
