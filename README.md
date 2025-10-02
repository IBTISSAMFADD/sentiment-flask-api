# sentiment-flask-api
Application Flask pour analyser le sentiment des tweets en ligne
Voici comment tu peux le compléter pour ton projet sentiment-flask-api :

# sentiment-flask-api
Application Flask pour analyser le sentiment des tweets en ligne.

## Description
Cette application permet de saisir un texte ou un tweet et d'obtenir une analyse de sentiment (Positif ou Négatif) grâce à un modèle NLP entraîné.

## Fonctionnalités
- Saisie de texte via un formulaire web.
- Nettoyage automatique du texte.
- Prédiction du sentiment avec un modèle TF-IDF + Logistic Regression.
- Interface web simple avec Bootstrap.

## Installation
1. Cloner le dépôt :
```bash
git clone https://github.com/ton_nom_utilisateur/sentiment-flask-api.git


Installer les dépendances :

pip install -r requirements.txt


Lancer l'application :

python app.py


Ouvrir dans le navigateur :

http://127.0.0.1:5000

Fichiers principaux

app.py : code Flask de l'application.

templates/index.html : interface web.

sentiment_model.pkl : modèle pré-entraîné.

tfidf_vectorizer.pkl : vectoriseur TF-IDF.

Auteur

Créé par Ibtissam, 2025.
