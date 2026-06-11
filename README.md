# Toolkit Software Solution

![Éditeur](https://img.shields.io/badge/éditeur-Toolkit%20Software%20Solution-00b7ff)
![Windows](https://img.shields.io/badge/plateforme-Windows%2010%20%2F%2011-0078d4)
![Licence](https://img.shields.io/badge/logiciels-propriétaires-orange)
![Support](https://img.shields.io/badge/contact-support-brightgreen)

Solutions logicielles de diagnostic, maintenance et reporting Windows.

Toolkit Software Solution développe et édite des outils destinés à structurer le diagnostic PC, améliorer la lisibilité des interventions et faciliter la production de rapports techniques.

Ce dépôt public est une vitrine de présentation, de documentation et de vérification. Il ne contient pas les sources propriétaires, les exécutables internes de build, les clés privées, les licences client ou les scripts de génération de licence.

## Produits

| Produit | Positionnement | Accès |
|---|---|---|
| [MotherDiag Community Edition](MotherDiag/docs/community.md) | Édition gratuite de diagnostic local Windows, orientée informations système et rapports simples. | Téléchargement public, sans activation `license.json`. |
| [MotherDiag Technician Edition](MotherDiag/docs/installation-technician.md) | Édition technicien / freemium-pro pour interventions, atelier et workflows plus avancés. | Trial contrôlé via canal officiel Toolkit Software Solution. |
| [CockpitDiag Enterprise](CockpitDiag/Enterprise/README.md) | Suite propriétaire professionnelle pour ateliers, techniciens, MSP, services IT et environnements de support. | Version `v1.0`, distribution contrôlée avec vérification SHA256. |

## Accès Rapide

### CockpitDiag Enterprise

- [Page produit](CockpitDiag/Enterprise/README.md)
- [Guide d'installation](CockpitDiag/Enterprise/docs/INSTALL.md)
- [SHA256 v1.0](CockpitDiag/Enterprise/release/v1.0/SHA256SUMS.txt)

Licence perpétuelle pour la version majeure achetée, avec plan Maintenance & Évolution optionnel.

### MotherDiag

- [Page produit](MotherDiag/README.md)
- [MotherDiag Community Edition](MotherDiag/docs/community.md) : édition gratuite, sans activation
- [Télécharger Community v1.0](https://toolkitsoftware.tech/downloads/public/motherdiag/community/v1.0/MotherDiag_Community_Edition_v1.0_2026-06-10.zip)
- [MotherDiag Technician Edition Trial](MotherDiag/docs/installation-technician.md) : édition technicien / freemium-pro
- [Télécharger Technician Trial](https://toolkitsoftware.tech/downloads/private/MotherDiag_Technician_Edition_v1.0_TRIAL_PUBLIC/MotherDiag_Technician_Edition_v1.0_TRIAL_PUBLIC_2026-06-30.zip)

## Distribution

CockpitDiag Enterprise est distribué via un canal officiel Toolkit Software Solution.

Les binaires ne sont pas publiés librement dans ce dépôt à ce stade. Le fichier `license.json` est fourni séparément aux clients autorisés.

## Vérification SHA256

Après téléchargement du ZIP fourni par Toolkit Software Solution, ouvrir PowerShell dans le dossier du fichier puis exécuter :

```powershell
Get-FileHash ".\CockpitDiag_Enterprise_v1.0.zip" -Algorithm SHA256
```

Le résultat doit correspondre exactement au SHA256 publié dans ce dépôt ou communiqué par Toolkit Software Solution.

En cas de différence, ne pas exécuter le fichier et contacter Toolkit Software Solution.

## Sécurité

Ce dépôt ne contient pas de clé privée, de fichier `license.json` client, de rapports clients, de dumps, de tokens ou de clés API.

Avant tout partage de logs, rapports, captures ou prompts IA, anonymisez les données sensibles.

Toolkit Software Solution ne fournit, ne revend et ne sous-licencie aucun crédit, compte, token, clé API ou accès API de fournisseur IA tiers.

## Éditeur

CockpitDiag Enterprise est développé et édité par Toolkit Software Solution.

Les informations légales, la politique de confidentialité et les conditions commerciales sont disponibles sur le site officiel : toolkitsoftware.tech.

Contact : contact@toolkitsoftware.tech
