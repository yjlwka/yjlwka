# Application de Mise en Relation Joueurs-Coachs pour les Universités Américaines

## Description
Cette application web facilite le processus de mise en relation entre les joueurs de sports et les entraîneurs des universités américaines. Les joueurs peuvent créer des profils détaillés et se connecter avec les entraîneurs qui cherchent des talents. Les entraîneurs peuvent également rechercher des joueurs prometteurs en fonction de critères spécifiques.

## Fonctionnalités
- **Profils Joueurs :** Statistiques, performances, ambitions académiques, préférences de programme.
- **Profils Coachs :** Exigences académiques, objectifs sportifs, possibilités de bourses.
- **Recherche Avancée :** Outils de recherche pour les joueurs et les coachs.
- **Communication Directe :** Système de messagerie pour les interactions entre joueurs et coachs.
- **Gestion des Événements :** Planification des visites, entrevues, et événements.

## Technologies Utilisées
- **Frontend :** React.js, Tailwind CSS, React Router
- **Backend :** Node.js, Express.js (Non inclus dans ce dépôt)
- **Base de Données :** MongoDB (Non inclus dans ce dépôt)
- **Autres :** Git, GitHub, Vercel, Netlify

## Installation et Configuration
### Prérequis
- Node.js (v14 ou supérieur)
- NPM ou Yarn
- Git

### Étapes d'Installation
1. **Cloner le dépôt :**
    ```bash
    git clone https://github.com/votre-utilisateur/joueur-coach-app.git
    cd joueur-coach-app
    ```

2. **Installer les dépendances :**
    ```bash
    npm install
    ```
    ou
    ```bash
    yarn install
    ```

3. **Configurer les variables d'environnement :**
    Créez un fichier `.env` à la racine du projet avec les variables suivantes :
    ```env
    REACT_APP_API_URL=http://localhost:5000/api
    REACT_APP_ENV=development
    ```

4. **Lancer le serveur de développement :**
    ```bash
    npm start
    ```
    ou
    ```bash
    yarn start
    ```

5. **Accéder à l'application :**
    Ouvrez votre navigateur et accédez à `http://localhost:3000`.

## Structure du Projet
```bash
joueur-coach-app/
│
├── public/               # Fichiers statiques (index.html, manifest, etc.)
├── src/
│   ├── components/       # Composants réutilisables
│   ├── pages/            # Pages de l'application
│   ├── services/         # Appels API et gestion des données
│   ├── styles/           # Fichiers CSS/SCSS
│   ├── App.js            # Composant principal
│   ├── index.js          # Point d'entrée de l'application
│   └── ...
├── .env                  # Variables d'environnement
├── .gitignore            # Fichiers à ignorer par Git
├── package.json          # Dépendances et scripts
└── README.md             # Documentation du projet

## Contribuer
Les contributions sont les bienvenues ! Suivez les étapes ci-dessous pour contribuer au projet.

1. **Fork le projet**
2. **Créez une branche pour votre fonctionnalité/correction de bug :**
    ```bash
    git checkout -b feature/ma-nouvelle-fonctionnalite
    ```
3. **Committez vos changements :**
    ```bash
    git commit -m "Ajout d'une nouvelle fonctionnalité"
    ```
4. **Poussez vos changements :**
    ```bash
    git push origin feature/ma-nouvelle-fonctionnalite
    ```
5. **Ouvrez une Pull Request**

