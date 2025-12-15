🎬 Movie App – React & OMDb API

Application web développée avec React permettant de rechercher des films, consulter les films en tendance et afficher les détails complets d’un film grâce à l’API OMDb.

🧩 Fonctionnalités
🏠 Page d’accueil (Home)

Affiche une section Films en Tendance

Films chargés à partir d’IDs IMDb prédéfinis :

tt0111161 – The Shawshank Redemption

tt0068646 – The Godfather

tt0468569 – The Dark Knight

tt0167260 – The Lord of the Rings

Affichage sous forme de cartes élégantes avec :

Affiche du film

Titre

Année

Bouton Détails

🔍 Recherche de films

Formulaire de recherche intégré dans la barre de navigation

Recherche par mot-clé (ex : batman, avengers, harry)

Résultats affichés dynamiquement sous forme de cartes

🎥 Détails du film

Page dédiée pour chaque film

Affiche les informations complètes :

Synopsis

Acteurs

Genre

Note IMDb

Affiche du film

Accès via le bouton Détails

🧭 Navigation

NavBar avec :

Maison (Home)

À propos (About)

Recherche

Navigation gérée avec React Router

🛠️ Technologies utilisées

⚛️ React

🌐 Axios (requêtes HTTP)

🎞️ OMDb API

🧭 React Router DOM

🎨 Tailwind CSS

💡 JavaScript (ES6+)

🔗 API utilisée

Recherche :

https://www.omdbapi.com/?apikey=4a3b711b&s=batman


Détails d’un film :

https://www.omdbapi.com/?apikey=4a3b711b&i=tt0372784

📁 Structure du projet (simplifiée)
src/
│── components/
│   ├── NavBar.jsx
│   ├── SearchForm.jsx
│   ├── MovieCard.jsx
│   ├── MovieDetails.jsx
│
│── pages/
│   ├── Home.jsx
│   ├── About.jsx
│
│── App.jsx
│── index.js

▶️ Lancer le projet

Installer les dépendances :

npm install


Lancer l’application :

npm start


Ouvrir dans le navigateur :

http://localhost:3000

✨ Améliorations possibles

Pagination des résultats

Gestion des erreurs (film introuvable)

Loader pendant le chargement

Dark mode

Favoris

👩‍💻 Auteur

Développé par Khadija
Projet pédagogique React + API 🎓
