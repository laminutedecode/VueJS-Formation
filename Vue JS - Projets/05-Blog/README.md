# Application de Blog en Vue.js

## Description
Ce dépôt de code contient une application Web créée en utilisant Vue.js pour un blog simple. L'application permet aux utilisateurs de parcourir les articles de blog et de voir les détails d'un article individuel.

## Mise en Route
Pour utiliser cette application de Blog en Vue.js, suivez ces étapes :

1. Clonez le dépôt sur votre machine locale.
2. Assurez-vous d'avoir Node.js installé sur votre machine.
3. Installez les dépendances en exécutant `npm install` dans le répertoire du projet.
4. Exécutez l'application en utilisant `npm run serve`.
5. Ouvrez votre navigateur et accédez à `http://localhost:8080` pour utiliser l'application de Blog.

## Fonctionnalités
- L'application de Blog en Vue.js offre les fonctionnalités suivantes :
  - Affichage de la page d'accueil avec une liste d'articles de blog.
  - Possibilité de cliquer sur un article pour voir les détails.
  - Navigation entre la page d'accueil et la page de détails de l'article en utilisant Vue Router.

## Structure du Code
- `src/main.js` : Point d'entrée de l'application Vue.
- `src/App.vue` : Le composant Vue principal qui intègre l'application.
- `src/components` : Les composants réutilisables utilisés dans l'application.
- `src/components/blog` : Les composants spécifiques au blog.
- `src/components/blog/Accueil.vue` : Le composant de la page d'accueil du blog.
- `src/components/blog/blog.vue` : Le composant de la page principale du blog avec la liste des articles.
- `src/components/blog/article.vue` : Le composant de détails d'un article individuel.
- `src/router/index.js` : La configuration de Vue Router pour gérer la navigation.
- `src/assets` : Les ressources statiques, y compris les images et le logo du blog.

## Licence
Ce code est disponible sous la licence MIT. Vous pouvez trouver les détails complets de la licence dans le fichier LICENSE.

## Auteur
Ce code a été rédigé par Jonathan Benitez. Si vous avez des questions ou avez besoin d'aide, veuillez me contacter à laminutedecode@gmail.com
