- URL site WEB :
- URL Notebook Observable :
- Nom :
- Prénom :
- Nom binome :
- Prénom binome :

# Remarques :

Le site propose deux parcours :

- `/species/Adelie`, `/species/Gentoo` et `/species/Chinstrap` affichent une page dédiée à chaque espèce grâce au composant partagé `GraphicSpecies.astro`.
- `/species` regroupe les trois graphiques dans un slider horizontal CSS. Les ancres du menu font défiler le slider et un `IntersectionObserver` ajoute la classe `active` à l'entrée visible.

Les graphiques utilisent les données `penguins.json` et tracent la longueur et la profondeur du culmen. Le projet est configuré avec l'adaptateur Netlify dans `astro.config.mjs`.

Décrire ici les éléments techniques remarquables de votre site (interactions, navigation, responsive, accessibilité...).
Idéalement avec des liens vers votre site et/ou [votre code](https://github.blog/news-insights/product-news/relative-links-in-markup-files/)
