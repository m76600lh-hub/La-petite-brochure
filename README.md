# Ma Petite Brochure — version 2

Application web mobile qui reconnaît un appareil sur une photo et recherche sa notice.

## Publication sur Vercel

1. Envoyer tous les fichiers à la racine du dépôt GitHub. Le dossier `api` doit apparaître à côté de `index.html`.
2. Dans Vercel : projet > Settings > Environment Variables.
3. Ajouter `ANTHROPIC_API_KEY` avec la clé créée dans la console Anthropic.
4. Facultatif : ajouter `ANTHROPIC_MODEL` pour choisir le modèle.
5. Dans Deployments, lancer Redeploy.

## Fichiers importants

- `index.html` : application
- `api/analyze.js` : reconnaissance de la photo
- `api/search.js` : recherche de la notice
- `api/status.js` : vérifie si la clé est configurée
- `manifest.webmanifest` et `service-worker.js` : installation sur téléphone
- `confidentialite.html` : première page de confidentialité à personnaliser

Ne placez jamais une clé API dans `index.html` ou dans un fichier public.
