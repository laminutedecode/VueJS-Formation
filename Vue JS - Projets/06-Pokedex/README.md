# Application Pokédex en Vue.js

## Description
Ce dépôt de code contient une application Web créée en utilisant Vue.js qui affiche une liste de Pokémon à partir de l'API PokeBuildAPI. L'application affiche les informations de base de chaque Pokémon, y compris leur nom, ID, et statistiques de combat.

## Mise en Route
Pour utiliser cette application Pokédex en Vue.js, suivez ces étapes :

1. Clonez le dépôt sur votre machine locale.
2. Assurez-vous d'avoir Node.js installé sur votre machine.
3. Installez les dépendances en exécutant `npm install` dans le répertoire du projet.
4. Exécutez l'application en utilisant `npm run serve`.
5. Ouvrez votre navigateur et accédez à `http://localhost:8080` pour utiliser l'application Pokédex.

## Fonctionnalités
- L'application Pokédex en Vue.js offre les fonctionnalités suivantes :
  - Affichage de la liste des Pokémon à partir de l'API PokeBuildAPI.
  - Affichage des informations de base de chaque Pokémon, y compris leur nom, ID et statistiques de combat.
  - Utilisation d'une image d'en-tête personnalisée pour la page d'accueil.

## Structure du Code
- `src/main.js` : Point d'entrée de l'application Vue.
- `src/App.vue` : Le composant Vue principal qui intègre l'application.
- `src/components` : Les composants réutilisables utilisés dans l'application.
- `src/components/Home.vue` : Le composant de la page d'accueil qui affiche la liste des Pokémon.
- `src/assets` : Les ressources statiques, y compris l'image d'en-tête du Pokédex.
- `axios` : Une bibliothèque utilisée pour effectuer des requêtes HTTP vers l'API PokeBuildAPI.

## API
L'application utilise l'API PokeBuildAPI pour obtenir les données des Pokémon. Vous pouvez trouver plus d'informations sur cette API à l'adresse suivante : [PokeBuildAPI](https://pokebuildapi.fr/api/v1).

## Licence
Ce code est disponible sous la licence MIT. Vous pouvez trouver les détails complets de la licence dans le fichier LICENSE.

## Auteur
Ce code a été rédigé par Jonathan Benitez. Si vous avez des questions ou avez besoin d'aide, veuillez me contacter à laminutedecode@gmail.com
