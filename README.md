# ❤️ Prédiction des maladies cardiaques avec Random Forest

## 📌 Présentation du projet

Ce projet utilise l'algorithme **Random Forest** afin de prédire si un patient est atteint d'une maladie cardiaque à partir de plusieurs caractéristiques médicales.

Le projet couvre toutes les étapes d'un workflow de Machine Learning, depuis l'exploration et le prétraitement des données jusqu'à l'entraînement du modèle et l'évaluation de ses performances.

---

## 🎯 Objectifs

- Explorer le jeu de données.
- Nettoyer les données.
- Supprimer les enregistrements en double.
- Analyser les corrélations entre les variables.
- Détecter les valeurs aberrantes.
- Diviser les données en ensembles d'entraînement et de test.
- Entraîner un modèle **Random Forest**.
- Évaluer les performances du modèle.

---

## 📊 Informations sur le jeu de données

**Nom :** Heart Disease Dataset

- Nombre d'observations : **302**
- Nombre de variables : **13**

### Variable cible

- **0 :** Absence de maladie cardiaque
- **1 :** Présence d'une maladie cardiaque

---

## 🛠️ Technologies et bibliothèques utilisées

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## ⚙️ Processus de Machine Learning

1. Chargement du jeu de données
2. Analyse exploratoire des données (EDA)
3. Suppression des doublons
4. Vérification des valeurs manquantes
5. Détection des valeurs aberrantes
6. Analyse des corrélations
7. Division des données en ensembles d'entraînement et de test
8. Entraînement du modèle **Random Forest**
9. Évaluation des performances

---

## 📈 Résultats

| Indicateur | Valeur |
|------------|--------:|
| Accuracy | **79 %** |
| Precision | **0.80** |
| Recall | **0.79** |
| F1-score | **0.79** |

---

##📉 Visualisations

### Détection des valeurs aberrantes (Boxplot)

  <img width="1081" height="570" alt="image" src="https://github.com/user-attachments/assets/244feb0e-2fcd-4548-bd6e-af6f8f5161f2" />

### Matrice de corrélation

<img width="996" height="688" alt="image" src="https://github.com/user-attachments/assets/47c7b778-5ce9-471c-97ba-6f8dc91a1ead" />

### Matrice de confusion

<img width="482" height="202" alt="image" src="https://github.com/user-attachments/assets/6794df47-e4e4-48a9-b1e0-0f184a348f0a" />

---

## 📁 Structure du projet

```text
Heart-Disease-Prediction-Random-Forest/
│
├── Heart_Disease.ipynb
├── heart.csv
├── README.md
├── requirements.txt
└── images/
    ├── boxplot.png
    ├── correlation_matrix.png
    └── confusion_matrix.png
```

---

## 🚀 Améliorations futures

- Optimiser les hyperparamètres avec **GridSearchCV**.
- Comparer les performances avec d'autres algorithmes de classification (SVM, Logistic Regression, XGBoost...).
- Réaliser une sélection des variables (**Feature Selection**).
- Déployer le modèle sous forme d'application web avec **Streamlit**.

---

## 👩‍💻 Auteur

**Amal El Mouatamad**

Étudiante en Intelligence Artificielle | Data Analyst

ISTA NTIC Rabat
