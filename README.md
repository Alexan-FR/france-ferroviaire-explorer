# France Ferroviaire Explorer

Prototype statique Leaflet prêt à publier sur Netlify.

## Lancer localement
Utiliser un petit serveur local, car `projects.json` est chargé par JavaScript.

```bash
python3 -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.

## Publier
Déposer le dossier dans un dépôt GitHub, puis connecter le dépôt à Netlify. Aucun build n'est requis.

## Données
Les localisations sont indicatives et devront être consolidées avec les sources officielles. Le site est conçu pour accueillir ensuite le catalogue SNCF Réseau et la couche des chantiers 2026.
