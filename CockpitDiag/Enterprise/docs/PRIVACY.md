# Confidentialité

CockpitDiag Enterprise est un outil local de diagnostic et de maintenance Windows.

## Traitement Local

CockpitDiag fonctionne localement sur la machine de l'utilisateur. Il peut lire des informations techniques nécessaires au diagnostic, notamment :

- version Windows ;
- processeur, mémoire, disque, GPU ;
- état des services ;
- journaux et résultats de commandes système ;
- informations réseau utiles au diagnostic ;
- résultats de maintenance ou de vérification.

## Rapports Et Logs

CockpitDiag peut générer :

- des logs runtime ;
- des rapports HTML ;
- des rapports JSON ;
- des prompts IA anonymisés ;
- des exports techniques selon les actions lancées par l'utilisateur.

Ces fichiers peuvent contenir des informations sensibles. L'utilisateur doit les relire et les anonymiser avant tout partage.

## Services IA Externes

CockpitDiag peut préparer un prompt anonymisé à copier manuellement dans un service IA externe.

Aucune donnée n'est envoyée automatiquement par CockpitDiag à un fournisseur IA.

Toolkit Software Solution ne fournit, ne revend et ne sous-licencie aucun crédit, compte, token, clé API ou accès API de fournisseur IA tiers.

L'utilisateur utilise ses propres comptes, clés API, crédits ou accès aux services IA concernés. Il reste seul responsable des données qu'il copie, colle, transmet ou soumet à un fournisseur IA externe.

## Licence

Le fichier `license.json` peut contenir des informations de licence, de validité, d'édition et éventuellement un identifiant machine haché.

Ne publiez pas ce fichier.

## Bonnes Pratiques

- Ne pas publier les rapports complets sans relecture.
- Ne pas partager de dumps mémoire sans validation explicite.
- Ne pas publier `%LOCALAPPDATA%\CockpitDiag\Logs`.
- Ne pas publier le dossier `Reports/` tel quel.
- Ne pas publier `license.json`.
- Ne pas copier de secrets, mots de passe, tokens ou clés API dans un prompt IA.
