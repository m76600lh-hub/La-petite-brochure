# Ma petite brochure

Application mobile web qui identifie un appareil photographié et recherche sa notice officielle.

## Publication sur Vercel

1. Crée un compte Anthropic Console et une clé API.
2. Crée un dépôt GitHub et ajoute tous les fichiers de ce dossier.
3. Sur Vercel, choisis **Add New > Project**, importe le dépôt et lance le déploiement.
4. Dans **Settings > Environment Variables**, ajoute :
   - `ANTHROPIC_API_KEY` : ta clé secrète
   - `ANTHROPIC_MODEL` : facultatif, par exemple `claude-sonnet-4-20250514`
5. Redéploie le projet.

## Important avant ouverture au public

- Ajoute des mentions légales et une politique de confidentialité.
- Ajoute une limite d'utilisation ou une authentification pour éviter une facture API incontrôlée.
- Vérifie la disponibilité du nom et du domaine avant de communiquer publiquement.
- Les images sont envoyées à l'API uniquement pour identifier l'objet ; indique-le clairement aux utilisateurs.
