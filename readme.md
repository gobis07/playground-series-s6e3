📊 Prédiction du Churn des Clients
🚀 Objectif du projet
Le but de ce projet est de construire un modèle de Machine Learning capable de prédire si un client va quitter un service de télécommunication.
Prédire le churn permet aux entreprises de :
- réduire la perte de clients
- améliorer la fidélisation
- optimiser les stratégies marketing
---
📂 Dataset
Dataset utilisé : Telco Customer Churn
Il contient :
- services utilisés par les clients
- informations de facturation
- durée d'abonnement
- statut de churn
---
🔎 Analyse exploratoire des données (EDA)
L’analyse exploratoire a permis d’identifier :
- les variables fortement corrélées avec le churn
- les distributions des variables
- les relations entre les variables démographiques et le churn
Exemples d’analyses réalisées :
- distribution des charges mensuelles
- relation entre contrat et churn
- influence de l’ancienneté du client
---
⚙️ Feature Engineering
Les nouvelles variables créées :
- chargesPerDay
- chargesPerHour
- SeniorCitizenWithPartner
Ces variables permettent d'améliorer la capacité prédictive du modèle.
---
🤖 Modèles de Machine Learning
Les modèles testés :
- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost
---
📈 Performance du modèle
Métriques utilisées :
- ROC-AUC

Score Kaggle obtenu : 0.85
---
📁 Structure du projet
project/
│
├── data/
|   ├── test.csv
|   ├── train.csv
|   ├── sample_submission.csv
|   ├── Submission.csv
│
├── EDA rapport/
|   ├── rapport_test.html
|   ├── rapport_train.html
|   ├── rapport_Trainset_preprocessing.html
|
|
├── notebooks/
│   └── notebook.ipynb
│
│
├── README.md
├── requirements.txt
└── .gitignore
---
🛠️ Technologies utilisées
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- XGBoost
---
📌 Améliorations futures
- Optimisation des hyperparamètres
- Utilisation de techniques d’ensemble (stacking)
- Déploiement du modèle
---
👨‍💻 Auteur :
Cirhuza Bisimwa Gloire
Projet réalisé dans le cadre de l’apprentissage du Machine Learning et de la pratique sur Kaggle.
