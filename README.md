# MaCaisse - Contrôle de caisse

MaCaisse est une application de contrôle de caisse conçue pour permettre au personnel de la société qui gère la caisse de contrôler leur caisse le soir et d'effectuer le rapprochement du journal de la caisse enregistreuse avec leur encaissement réel.
Fonctionnalités

## Les principales fonctionnalités de l'application sont les suivantes :

    - Authentification pour le personnel et l'administrateur
    - Vérification de la caisse pour le personnel
    - Contrôle de la caisse pour l'administrateur
    - Enregistrement des paiements en espèces, par chèque, par carte bancaire, ticket loisir et bon cadeau
    - Saisie du journal de caisse pour le personnel
    - Rapprochement des sommes encaissées avec le journal de caisse pour le personnel
    - Impression d'un rapport de clôture de caisse pour le personnel
    - Notification de paiements nécessitant une facture pour le personnel
    - Indication des anomalies sur le rapport pour l'administrateur
    - Indication que la caisse a été contrôlée pour l'administrateur
    - Indication que les factures ont été envoyées suite à la demande du personnel pour l'administrateur

## Technologies

L'application a été développée en utilisant les technologies suivantes :

    - Vue.js pour le frontend
    - Vuetify pour le framework CSS
    - Vuex pour la gestion de l'état de l'application
    - Axios pour les requêtes à l'API
    - Laravel pour l'API

## Installation

    - Cloner le dépôt : git clone https://github.com/Gilles-boyer/macaisse
    - Installer les dépendances pour le frontend : cd frontend && npm install
    - Installer les dépendances pour l'API : cd backend && composer install
    - Configurer la base de données dans le fichier .env du dossier backend
    - Lancer les migrations pour créer les tables dans la base de données : cd backend && php artisan migrate
    - Lancer l'application : cd frontend && npm run serve pour le frontend et cd backend && php artisan serve pour l'API.

## Contribuer

Si vous souhaitez contribuer à l'application, vous pouvez ouvrir une nouvelle issue ou soumettre une pull request. Veuillez noter que toutes les pull requests doivent être testées et respecter les normes de codage définies dans le fichier .eslintrc du dossier frontend et dans le fichier phpcs.xml du dossier backend.
Licence

MaCaisse est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

## Auteurs

    - Gilles BOYER (g.boyer@cfg.re)
