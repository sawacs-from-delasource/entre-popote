# Mes recettes

Prototype de webapp de recettes inspirée de Mela.

Fonctions : saisie, photos, catégories, recherche, ajustement des portions, mode Lecture plein écran, import Mela (.melarecipes), import par texte ou captures (Instagram) via Claude, partage.

## Important
Cette version tourne comme artifact Claude. Elle s'appuie sur l'API `window.claude` (base de données, stockage photos, appel à Claude). Ouverte hors de Claude (GitHub Pages par exemple), elle affiche l'interface mais ne charge ni n'enregistre aucune recette.

Pour une version autonome, remplacer ces appels par un backend (ex. Supabase) et une API IA.
