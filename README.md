# Portfolio — Djibril DIOP

Site personnel : **https://djibril44.github.io/portfolio/**

Ingénieur Transport & Mobilité Numérique · Data Scientist au CETUD (Dakar).

## Structure

| Fichier | Rôle |
|---|---|
| `index.html` | La page du site |
| `assets/js/content.js` | **Tout le contenu** (textes FR/EN, projets, expériences, certifications…) |
| `assets/js/main.js` | Affichage et interactions (langue, thème, filtres, fenêtres de projet) |
| `assets/css/styles.css` | Apparence |
| `assets/img/`, `assets/certificats/`, `assets/cv/` | Photo, images, certificats, CV |
| `admin.html` | Espace d'édition du contenu, sans code |

## Mettre à jour le contenu

1. Ouvrir `admin.html` dans Chrome ou Edge (double-clic sur le fichier en local).
2. Modifier les rubriques, vérifier avec **Aperçu du site**.
3. Cliquer sur **Enregistrer content.js** et remplacer `assets/js/content.js`.
4. Publier :

```bash
git add .
git commit -m "Mise à jour du contenu"
git push
```

Le site en ligne se met à jour en une à deux minutes.
