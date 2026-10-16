# Anniversaire 2 ans

Carnet de bord pour une journée à Gand : billet à composter, choix des visites, carte de la journée, infos pratiques et lettre.

Tout tient dans `index.html`.

## Modifier

- **Textes, dates, horaires, lettre** : bloc `CONFIG` en haut du script.
- **Visites** : tableau `ACTS` (identifiant, catégorie, titre, texte, latitude, longitude).
- **Photos** : déposer `images/<identifiant>.jpg` (ex. `images/graslei.jpg`). Sans photo, un dégradé s'affiche.

## Raccourcis d'URL

- `?skip` : saute l'animation du carnet.
- `?dev` : affiche le nom de fichier attendu pour chaque photo.

## Services externes (sans clé)

- Carte : Leaflet, tuiles Esri Light Gray (repli OpenStreetMap). Chargée seulement à l'approche de la section « choses à voir ».
