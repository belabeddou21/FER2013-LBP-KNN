# TD2 — Reconnaissance d'expressions faciales
## LBP + KNN sur FER-2013

**Cours :** Interface Homme Machine — National University of Science and Technology POLITEHNICA Bucharest  
**Auteur :** Walid BELABEDDOU  
**Date :** Avril 2026  

---

## Description

Implémentation d'un système de reconnaissance d'expressions faciales utilisant :
- **LBP (Local Binary Patterns)** pour l'extraction de features
- **KNN (K-Nearest Neighbors)** pour la classification

**Dataset :** FER-2013 (~35 000 images, 48×48 pixels, 7 émotions)  
**Accuracy obtenue : 44.66%**

---

## Émotions détectées

Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise

---

## Lancer le code

1. Télécharger FER-2013 depuis [Kaggle](https://www.kaggle.com/datasets/msambare/fer2013)
2. Extraire dans le dossier du projet
3. Installer les dépendances :
```bash
pip install scikit-image scikit-learn numpy matplotlib seaborn pillow
```
4. Ouvrir et exécuter `Reconnaissance_expressions_faciales.ipynb`

---

## Résultats

| Émotion  | F1-score |
|----------|----------|
| Happy    | 0.56     |
| Surprise | 0.57     |
| Fear     | 0.40     |
| Sad      | 0.33     |
