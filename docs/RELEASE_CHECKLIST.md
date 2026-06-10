# Release Checklist

Avant publication d'une nouvelle version :

- Mettre à jour `README.md`.
- Mettre à jour `CHANGELOG.md`.
- Mettre à jour `release/vX.Y/SHA256SUMS.txt`.
- Mettre à jour `release/vX.Y/release-manifest.json`.
- Vérifier que le ZIP n'est pas commité dans ce dépôt.
- Vérifier que `license.json` n'est jamais présent.
- Vérifier que `PrivateKeys`, `Licensing_Private`, `TestLicenses`, `Reports` et `Logs` sont absents.
- Vérifier que le lien de téléchargement fonctionne.
- Vérifier que le SHA256 publié correspond au ZIP hébergé.
