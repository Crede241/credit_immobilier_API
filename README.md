# 🏡 Credit Immobilier API

Ce projet est une API de prédiction de l'éligibilité à un crédit immobilier basée sur un modèle de machine learning entraîné à partir de données structurées.

## 🚀 Fonctionnalités

- API REST construite avec Flask
- Prédiction à partir de données clients (revenus, historique, statut familial, etc.)
- Modèle de classification entraîné avec des données réelles (fichier `train_u6lujuX_CVtuZ9i.csv`)
- Interface web simple avec `Flask`, `Jinja`, et `Bootstrap`

## 📁 Structure du projet

credit_immobilier_API/
├── app.py # Fichier principal Flask
├── model.pkl # Modèle ML sauvegardé
├── requirements.txt # Dépendances du projet
├── templates/ # Fichiers HTML (interface utilisateur)
├── static/ # CSS, JS, images
├── credit_model.ipynb # Notebook de création et test du modèle
└── train_u6lujuX_CVtuZ9i.csv # Données d'entraînement

## 📦 Installation

```bash
# Créer un environnement virtuel (optionnel mais recommandé)
python -m venv venv
venv\Scripts\activate  # Windows

# Installer les dépendances
pip install -r requirements.txt

# Lancer l'API
python app.py
🧪 Exemple d'utilisation
Rendez-vous sur http://127.0.0.1:5000 pour utiliser l'interface et soumettre des données à l'API.

📚 Modèle ML
Le modèle a été entraîné à partir d’un dataset Kaggle (Loan Prediction), en utilisant des techniques de preprocessing, d'encodage, et un algorithme de classification (comme Logistic Regression, Random Forest...).

🛡️ Avertissement
Ce projet est à but éducatif. Il ne doit pas être utilisé pour des décisions réelles liées au crédit sans validation professionnelle.

👤 Auteur
Farel Pambo
Data Analyst & MSc Data Management (Aivancity)
LinkedIn
