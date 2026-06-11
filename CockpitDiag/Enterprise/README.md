# CockpitDiag Enterprise

![Version](https://img.shields.io/badge/version-1.0-00b7ff)
![Windows](https://img.shields.io/badge/plateforme-Windows%2010%20%2F%2011-0078d4)
![PowerShell](https://img.shields.io/badge/PowerShell-5.1%2B-5391fe)
![Licence](https://img.shields.io/badge/licence-propriétaire-orange)
![SHA256](https://img.shields.io/badge/SHA256-publié-brightgreen)

CockpitDiag Enterprise est une suite propriétaire professionnelle avancée pour le diagnostic, la maintenance, le reporting et l'assistance technique Windows.

CockpitDiag Enterprise est développé et édité par Toolkit Software Solution.

![CockpitDiag Enterprise v1.0](assets/screenshots/cockpitdiag-enterprise-v1-dashboard.png)

## Téléchargement

Release actuelle : `v1.0`  
Date de publication : `2026-06-10`  
Statut : distribution contrôlée  
Licence client : `license.json` fourni séparément aux clients autorisés

Distribution contrôlée sur demande via le canal officiel Toolkit Software Solution.

Contact : contact@toolkitsoftware.tech — le ZIP et le `license.json` sont fournis séparément aux clients autorisés.

Empreinte SHA256 attendue :

```text
233396cd0ae553a55bd60e3b4b6000730d8736d7f08cbf0a076f6698fe1eb87c
```

Fichiers de vérification :

- [SHA256SUMS.txt](release/v1.0/SHA256SUMS.txt)
- [release-manifest.json](release/v1.0/release-manifest.json)

Important : le ZIP client et la licence d'activation sont fournis séparément aux clients autorisés.

## Tarif

CockpitDiag Enterprise : 149€ paiement unique.

Licence perpétuelle pour la version majeure achetée. Les mises à jour mineures de la branche v1 sont incluses.

Plan Maintenance & Évolution : 39€/an, optionnel, facturé à N+1.

Inclut l'accès aux futures versions majeures, aux évolutions importantes et au support prioritaire pendant la durée active du plan.

Le plan Maintenance & Évolution n'est pas obligatoire pour continuer à utiliser la version achetée. Sans ce plan, la licence CockpitDiag Enterprise reste valable pour la version majeure achetée.

## Vérification SHA256

Après téléchargement du ZIP officiel, ouvrir PowerShell dans le dossier du fichier puis exécuter :

```powershell
Get-FileHash ".\CockpitDiag_Enterprise_v1.0.zip" -Algorithm SHA256
```

Le hash obtenu doit correspondre exactement au SHA256 publié par Toolkit Software Solution.

En cas de différence, ne pas exécuter le fichier et contacter Toolkit Software Solution.

## Fonctions Principales

- Diagnostic système Windows.
- Maintenance guidée : SFC, DISM, CHKDSK, registre, nettoyage.
- Rapports HTML et JSON.
- Génération de prompt IA anonymisé en mode manuel.
- Centre d'applications portables configurable.
- Analyse santé système et logs locaux.
- Validation de licence via module dédié `CockpitDiag.Licensing.dll`.

## Installation Rapide

1. Télécharger le ZIP.
2. Vérifier le SHA256.
3. Extraire le ZIP dans un dossier local.
4. Copier le fichier `license.json` fourni séparément à la racine du dossier extrait.
5. Lancer `CockpitDiag.exe` en administrateur.

Guide complet : [docs/INSTALL.md](docs/INSTALL.md)

## IA Et Services Tiers

CockpitDiag Enterprise peut générer un prompt anonymisé prêt à copier dans un assistant IA externe. Aucune donnée n'est envoyée automatiquement par CockpitDiag.

Toolkit Software Solution ne fournit, ne revend et ne sous-licencie aucun crédit, compte, token, clé API ou accès API de fournisseur IA tiers.

L'utilisateur utilise ses propres comptes, clés API, crédits ou accès aux services IA concernés. Il reste seul responsable des données qu'il copie, colle, transmet ou soumet à un fournisseur IA externe.

## Documents

- [Licence propriétaire](LICENSE.txt)
- [EULA](docs/EULA.md)
- [Security Policy](SECURITY.md)
- [NOTICE](NOTICE)
- [Guide d'installation](docs/INSTALL.md)
- [Licensing](docs/LICENSING.md)
- [Privacy](docs/PRIVACY.md)
- [FAQ](docs/FAQ.md)
- [Support](SUPPORT.md)
- [Changelog](CHANGELOG.md)

## Support

Contact : contact@toolkitsoftware.tech
