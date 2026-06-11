# Toolkit Software

![Éditeur](https://img.shields.io/badge/éditeur-Toolkit%20Software%20Solution-00b7ff)
![Windows](https://img.shields.io/badge/plateforme-Windows%2010%20%2F%2011-0078d4)
![Licence](https://img.shields.io/badge/logiciels-propriétaires-orange)
![Support](https://img.shields.io/badge/contact-support-brightgreen)

Vitrine publique de Toolkit Software Solution.

Toolkit Software Solution développe et édite des outils destinés à structurer le diagnostic PC, améliorer la lisibilité des interventions et faciliter la production de rapports techniques.

Ce dépôt public sert de point d'entrée vers les produits et leur documentation publique. Il ne contient pas les sources propriétaires, les exécutables internes de build, les clés privées, les licences client ou les scripts de génération de licence.

## Produits

| Produit | Positionnement | Accès |
|---|---|---|
| [CockpitDiag Enterprise](https://github.com/Toolkit-Software-Solution/CockpitDiag-Enterprise) | Suite propriétaire professionnelle pour ateliers, techniciens, MSP, services IT et environnements de support. | Distribution contrôlée sur demande, avec vérification SHA256. |
| [MotherDiag Technician](https://github.com/Toolkit-Software-Solution/MotherDiag-Technician) | Édition technicien / freemium-pro pour interventions, atelier et workflows plus avancés. | Distribution contrôlée sur demande via canal officiel Toolkit Software Solution. |
| [MotherDiag Community](https://github.com/Toolkit-Software-Solution/MotherDiag-Community) | Édition gratuite de diagnostic local Windows, orientée informations système et rapports simples. | Téléchargement public, sans activation `license.json`. |

## Vérification SHA256

Après téléchargement d'un ZIP fourni par Toolkit Software Solution, ouvrez PowerShell dans le dossier du fichier puis exécutez :

```powershell
Get-FileHash ".\Nom_Du_Fichier.zip" -Algorithm SHA256
```

Le résultat doit correspondre exactement au SHA256 publié dans le dépôt du produit concerné ou communiqué par Toolkit Software Solution.

En cas de différence, ne pas exécuter le fichier et contacter Toolkit Software Solution.

## Sécurité

Ce dépôt ne contient pas de clé privée, de fichier `license.json` client, de rapports clients, de dumps, de tokens ou de clés API.

Avant tout partage de logs, rapports, captures ou prompts IA, anonymisez les données sensibles.

Toolkit Software Solution ne fournit, ne revend et ne sous-licencie aucun crédit, compte, token, clé API ou accès API de fournisseur IA tiers.

## Éditeur

Développé et édité par Jarrod Barraco, entrepreneur individuel exerçant sous le nom commercial Toolkit Software Solution.

Contact : contact@toolkitsoftware.tech
