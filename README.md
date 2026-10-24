# Explore — application web de découverte touristique

## Lancer l'application
1. Décompressez le dossier.
2. Ouvrez `index.html` dans un navigateur récent, ou servez le dossier avec un serveur local.
3. Une connexion Internet est nécessaire pour les polices, les photos, Leaflet et les tuiles OpenStreetMap.

## Fonctionnalités
- Navigation entre accueil, destinations, carte, voyages et favoris
- Recherche et filtres par catégorie
- Fiches destinations détaillées
- Carte interactive Leaflet / OpenStreetMap
- Favoris et voyages sauvegardés dans `localStorage`
- Interface responsive pour mobile et ordinateur

## Limites du prototype
- Les destinations, notes et budgets sont des exemples éditables dans `app.js`; ils ne constituent pas des données touristiques vérifiées.
- Les favoris et voyages sont stockés uniquement dans le navigateur et ne sont pas synchronisés entre appareils.
- La carte et les images requièrent Internet.
- Pour une mise en production, prévoir une API, une base de données, une authentification, une politique de confidentialité et des sources de données touristiques vérifiées.
