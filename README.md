
# SmartRH
Le projet Smart RH est une application de gestion des ressources humaines utilisant l'intelligence artificielle pour simplifier et améliorer le processus de recrutement. Cette plateforme offre aux recruteurs des outils avancés pour publier des offres d'emploi, évaluer les candidatures, planifier des entretiens et suivre le processus de recrutement de manière efficace. De même, les candidats bénéficient d'une expérience utilisateur optimisée, leur permettant de rechercher des emplois, postuler en ligne, suivre l'état de leurs candidatures et communiquer avec les recruteurs. Grâce à son interface conviviale et à ses fonctionnalités intelligentes, Smart RH vise à simplifier et à rationaliser les processus de recrutement, offrant ainsi des avantages tant aux recruteurs qu'aux candidats.

# Installation

1. Cloner le dépôt :
   
    git clone [https://github.com/votre-utilisateur/votre-projet.git](https://github.com/mzerroug/smartRH.git)
    cd votre-projet

2. Créer et activer l'environnement virtuel :

    python -m venv VirtualEnv
    # Sur Windows
    VirtualEnv\Scripts\activate
   

3. Installer les dépendances :

    pip install -r requirements.txt

## Configuration

1. Google Client ID :

    Remplacez `GOOGLE_CLIENT_ID` dans `app.py` par votre identifiant client Google.

2. Client Secret JSON :

    Ajoutez le fichier `client_secret.json` dans le répertoire racine du projet.

3. URI MongoDB :

    Remplacez `MONGO_URI` dans `app.py` par l'URI de votre base de données MongoDB.

## Utilisation

1. Lancer l'application :

    flask run

2. Accéder à l'application :

    Ouvrez un navigateur web et allez à l'adresse `http://localhost:5000`.

#  Check out this video for overall guide:
https://youtu.be/CphVOnBUkg4
