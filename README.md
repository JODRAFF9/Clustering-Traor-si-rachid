<p align="center">
  <img src="docs/ansd.jpg" alt="Image 1" width="45%" />
  <img src="docs/ensae.png" alt="Image 2" width="45%" />
</p>

![Demo GIF](docs/TRAORE-SIE-RACHID-TP-clustering.ipynb-Visual-Studio-Code-2025-05-22-15-27-03.gif)

### 🧠 Objectif du notebook

Le notebook effectue une **analyse de clustering** sur le jeu de données `digits` de `sklearn`, qui contient des images de chiffres manuscrits (0 à 9) représentées par 64 caractéristiques (pixels). Il utilise principalement **KMeans**, diverses techniques de visualisation, et des métriques pour évaluer la qualité du clustering.

---

Voici un exemple de `README.md` que tu peux utiliser :

---

## 🧮 TP Clustering sur le Jeu de Données Digits

### 👤 Auteur

TRAORÉ Sié Rachid

### 📘 Description

Ce notebook explore différentes techniques de **clustering non supervisé** pour regrouper des images de chiffres manuscrits en fonction de leurs caractéristiques. Il s'appuie sur le jeu de données `digits` de `scikit-learn` et applique le clustering `KMeans`, tout en utilisant des visualisations et des métriques pour évaluer la performance.

---

### 📦 Bibliothèques utilisées

* `numpy`, `pandas`, `matplotlib`, `seaborn`
* `scikit-learn` (datasets, KMeans, PCA, TSNE, etc.)
* `yellowbrick` pour la visualisation (silhouette, distance inter-cluster, elbow)
* `warnings` pour masquer les alertes

---

### 🔍 Étapes principales

1. **Chargement des données**

   * Chargement du dataset `digits` via `load_digits()`
   * Construction d’un DataFrame avec 64 colonnes + label

2. **Exploration des données**

   * Visualisation de la distribution des chiffres
   * Affichage des moyennes des chiffres sous forme d'images

3. **Prétraitement**

   * Normalisation des données (StandardScaler, MinMaxScaler, etc.)

4. **Clustering avec KMeans**

   * Application de `KMeans` avec différents `k`
   * Évaluation avec le score de silhouette et d'autres métriques

5. **Réduction de dimension**

   * Utilisation de `PCA` et `TSNE` pour visualiser les clusters

6. **Visualisation**

   * Diagrammes Elbow
   * Visualisation des distances inter-clusters
   * Visualisation des clusters avec PCA/TSNE

---

### 📊 Résultats

* Bon alignement des clusters avec les vraies classes.
* KMeans parvient à distinguer efficacement certains chiffres.
* Utilisation des métriques pour évaluer la cohérence des clusters.

---

### 🚀 Lancer le notebook

1. Cloner le dépôt ou télécharger le fichier `.ipynb`
2. Installer les dépendances (via `pip` ou `conda`)
3. Ouvrir le notebook avec Jupyter :

```bash
jupyter notebook "TRAORE SIE RACHID TP clustering.ipynb"
```
---
