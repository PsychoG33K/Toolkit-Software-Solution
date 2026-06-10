# Privacy

CockpitDiag Enterprise est un outil local de diagnostic et de maintenance Windows.

## Traitement Local

CockpitDiag fonctionne localement sur la machine de l'utilisateur. Il peut lire des informations techniques necessaires au diagnostic, notamment :

- version Windows ;
- processeur, memoire, disque, GPU ;
- etat des services ;
- journaux et resultats de commandes systeme ;
- informations reseau utiles au diagnostic ;
- resultats de maintenance ou de verification.

## Rapports Et Logs

CockpitDiag peut generer :

- des logs runtime ;
- des rapports HTML ;
- des rapports JSON ;
- des prompts IA anonymises ;
- des exports techniques selon les actions lancees par l'utilisateur.

Ces fichiers peuvent contenir des informations sensibles. L'utilisateur doit les relire et les anonymiser avant tout partage.

## Services IA Externes

CockpitDiag peut preparer un prompt anonymise a copier manuellement dans un service IA externe.

Aucune donnee n'est envoyee automatiquement par CockpitDiag a un fournisseur IA.

Toolkit Software Solution ne fournit, ne revend et ne sous-licencie aucun credit, compte, token, cle API ou acces API de fournisseur IA tiers.

L'utilisateur utilise ses propres comptes, cles API, credits ou acces aux services IA concernes. Il reste seul responsable des donnees qu'il copie, colle, transmet ou soumet a un fournisseur IA externe.

## Licence

Le fichier `license.json` peut contenir des informations de licence, de validite, d'edition et eventuellement un identifiant machine hache.

Ne publiez pas ce fichier.

## Bonnes Pratiques

- Ne pas publier les rapports complets sans relecture.
- Ne pas partager de dumps memoire sans validation explicite.
- Ne pas publier `%LOCALAPPDATA%\CockpitDiag\Logs`.
- Ne pas publier le dossier `Reports/` tel quel.
- Ne pas publier `license.json`.
- Ne pas copier de secrets, mots de passe, tokens ou cles API dans un prompt IA.
