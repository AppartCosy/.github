# AppartCosy

Bienvenue dans le dépôt GitHub de AppartCosy. Chez AppartCosy, nous voyons un immense potentiel dans la location courte durée au Congo, encore peu exploité. Notre mission est de moderniser les courts séjours avec des solutions sur mesure pour voyageurs et propriétaires. Nous nous engageons à promouvoir les richesses culturelles congolaises tout en offrant un service de qualité supérieure.

## Table des Matières

- [Aperçu](#aperçu)
- [Technologies Utilisées](#technologies-utilisées)
- [Installation](#installation)
- [Contribution](#contribution)
- [Git Flow](#git-flow)
- [Règles de Commit](#règles-de-commit)
- [Support](#support)
- [Licence](#licence)

## Aperçu

AppartCosy est une application dédiée à la location de courte durée, offrant des solutions innovantes pour les voyageurs et les propriétaires au Congo. Notre objectif est de rendre les séjours plus confortables et enrichissants tout en valorisant la culture congolaise.

## Technologies Utilisées

- **Frontend**: Next.js, CSS
- **Backend**: Laravel
- **Base de données**: MySQL
- **Contrôle de version**: Git, Git Flow


## Installation

### Prérequis

- Node.js
- npm ou yarn
- PHP
- Composer
- MySQL

### Instructions

1. Clonez le dépôt:

    - Pour le frontend:
        ```sh
        git clone https://github.com/organisation/appartCosy-frontend.git
        cd appartCosy-frontend
        npm install
        ```

    - Pour le backend:
        ```sh
        git clone https://github.com/organisation/appartCosy-backend.git
        cd appartCosy-backend
        composer install
        ```

2. Configurez les variables d'environnement.

    - Pour le frontend, créez un fichier `.env.local` en vous basant sur `.env.example`.
    - Pour le backend, copiez `.env.example` en `.env` et modifiez-le selon vos configurations MySQL.

3. Démarrez les serveurs:

    - Frontend:
        ```sh
        npm run dev
        ```

    - Backend:
        ```sh
        php artisan serve
        ```

## Contribution

Pour contribuer à ce projet, veuillez suivre les étapes suivantes :

1. Forkez le dépôt.
2. Clonez le dépôt approprié (frontend ou backend).
3. Installez les dépendances et configurez les variables d'environnement comme décrit dans la section [Installation](#installation).
4. Assurez-vous que Git Flow est installé et initialisé:
    ```sh
    git flow init
    ```
    (Voir [Git Flow Cheatsheet](https://danielkummer.github.io/git-flow-cheatsheet/index.fr_FR.html) pour plus de détails).

5. Créez une branche pour votre fonctionnalité:
    ```sh
    git flow feature start ma-fonctionnalité
    ```

6. Commitez vos modifications:
    ```sh
    git commit -m 'Ajout de ma fonctionnalité'
    ```

7. Terminez la fonctionnalité:
    ```sh
    git flow feature finish ma-fonctionnalité
    ```

8. Poussez la branche:
    ```sh
    git push origin develop
    ```

9. Ouvrez une Pull Request pour révision.

### Exigences de Contribution

- Assurez-vous que votre code suit les normes de codage définies.
- Ajoutez des tests pour toute nouvelle fonctionnalité.
- Mettez à jour la documentation si nécessaire.

## Git Flow

Nous utilisons Git Flow pour organiser notre développement. Voici les commandes de base :

- **Initialiser Git Flow** (à faire une seule fois après le clonage du dépôt):
    ```sh
    git flow init
    ```

- **Créer une nouvelle fonctionnalité** :
    ```sh
    git flow feature start ma-fonctionnalité
    ```

- **Terminer une fonctionnalité** :
    ```sh
    git flow feature finish ma-fonctionnalité
    ```

Avant de pousser sur la branche `main`, ouvrez d'abord une Pull Request pour révision.

## Règles de Commit

- Utilisez des messages de commit clairs et concis.
- Format recommandé : `[Type] Courte description`.
  - **Types** : feat (nouvelle fonctionnalité), fix (correction de bug), docs (documentation), style (formatage, CSS, etc.), refactor (refactorisation de code), test (ajout de tests), chore (tâches de maintenance).

## Support

Si vous avez des questions ou avez besoin d'aide, veuillez ouvrir une [issue](https://github.com/organisation/AppartCosy/issues) ou contacter l'équipe de développement.




