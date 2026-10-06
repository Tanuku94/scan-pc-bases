# scan-pc-bases

Bases de données utilisées par la clé USB « Scan PC » (processeurs Intel, AMD, ARM et cartes graphiques).

**Ne pas modifier ces fichiers à la main** : ils sont générés avec des contrôles de qualité et chacun a une empreinte SHA-256 enregistrée dans `manifest.json`.

- `manifest.json` : version, date et empreinte de chaque fichier
- `bases/` : les fichiers de données (CSV)
- `CHANGELOG.md` : ce qui a changé dans la dernière version

Le scan télécharge uniquement ces fichiers (aucune donnée n'est envoyée) et ne les applique que si tous les contrôles réussissent.
