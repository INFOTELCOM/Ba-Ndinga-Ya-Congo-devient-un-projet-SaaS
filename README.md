# Ba Ndinga Ya Congo — SaaS

Plateforme de traduction multilingue dédiée aux langues congolaises, africaines et internationales.

## Configuration des traductions

1. Créer un projet Google Cloud et activer Cloud Translation API.
2. Configurer la facturation et créer une clé API limitée à cette API.
3. Ajouter GOOGLE_TRANSLATE_API_KEY dans les variables d'environnement de l'hébergement. Ne jamais publier cette clé dans le dépôt.
4. Installer les dépendances avec npm install, puis lancer npm run dev.

Les traductions réelles nécessitent un fournisseur configuré; la couverture varie selon la langue.

## Sécurité

Ne jamais committer .env.local, une clé API ou des secrets.