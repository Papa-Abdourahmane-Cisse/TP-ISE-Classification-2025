

# TP-ISE – Classification avec Modèles Ensemblistes (2025)

## 🎯 Objectif

Ce TP a pour objectif de vous familiariser avec l’utilisation des **modèles ensemblistes** pour des tâches de classification. Vous serez amené à :

* Entraîner et optimiser deux modèles ensemblistes.
* Comparer leurs performances et sélectionner le meilleur.
* Interpréter les résultats à l’aide de **SHAP** (SHapley Additive exPlanations).
* Optimiser le modèle retenu et l’enregistrer pour une utilisation ultérieure.


## 🧭 Étapes du TP

### 1. Entraînement et Optimisation des Modèles

* **Sélection des modèles** : Choisissez deux algorithmes ensemblistes (ex. : Random Forest, Gradient Boosting).
* **Entraînement** : Utilisez les données préparées pour entraîner les modèles.
* **Optimisation** : Réalisez une recherche d'hyperparamètres (GridSearchCV, RandomizedSearchCV...) pour améliorer les performances.

### 2. Évaluation et Sélection du Meilleur Modèle

* **Évaluation** : Comparez les modèles à l’aide de métriques adaptées : *accuracy*, *precision*, *recall*, *F1-score*, *ROC AUC*, etc.
* **Sélection** : Retenez le modèle offrant les meilleurs compromis performance/interprétabilité.

### 3. Analyse de l’Importance des Caractéristiques

* **SHAP global** : Identifiez les variables les plus influentes sur l’ensemble des prédictions.
* **SHAP local** : Interprétez les contributions individuelles de certaines prédictions.

### 4. Finalisation et Enregistrement du Modèle

* **Optimisation finale** : Ajustez si besoin les hyperparamètres du modèle retenu.
* **Enregistrement** : Sauvegardez le modèle optimisé avec la bibliothèque `dill`.



## 🛠️ Instructions Techniques

* **Préparation des données** : Assurez-vous d’avoir nettoyé et prétraité les données avant l'entraînement.
* **Modélisation** : Utilisez `scikit-learn` pour l'entraînement, la validation et l'évaluation.
* **Analyse SHAP** : Installez et exploitez la bibliothèque `shap` pour interpréter le modèle.
* **Sauvegarde du modèle** : Utilisez `dill` pour enregistrer le modèle entraîné (`.dill`).



## 💼 Technologies recommandées

* Python 3.x
* scikit-learn
* pandas, numpy
* matplotlib, seaborn
* shap
* dill

