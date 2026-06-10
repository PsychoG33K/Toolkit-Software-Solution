# Security Policy

CockpitDiag Enterprise est développé et édité par Jarrod Barraco, entrepreneur individuel, régime micro-entreprise, exerçant sous le nom commercial Toolkit Software Solution.

## Signalement

Pour signaler une faille ou un problème de sécurité lié à CockpitDiag Enterprise, contacter Toolkit Software Solution à l'adresse contact@toolkitsoftware.tech avant toute publication publique du détail technique.

## Données sensibles

CockpitDiag peut générer des rapports, logs, dumps, exports Wi-Fi et prompts IA contenant des informations sensibles : nom machine, nom utilisateur, chemins locaux, IP, pilotes, périphériques, SSID, éléments de configuration et parfois contenu mémoire pour les dumps.

Les logs runtime sont stockés dans `%LOCALAPPDATA%\CockpitDiag\Logs`. Les rapports et exports restent à surveiller dans les emplacements choisis par l'utilisateur ou dans `Reports`.

Avant partage avec un tiers ou un fournisseur IA :

- relire le rapport ;
- supprimer ou anonymiser les informations sensibles ;
- ne pas transmettre de dumps sans validation explicite ;
- ne pas publier `%LOCALAPPDATA%\CockpitDiag\Logs`, `Reports/`, backups, caches ou exports Wi-Fi.
- vérifier les conditions du fournisseur IA externe choisi, car les données transmises relèvent du compte, des règles et des conditions de ce fournisseur.

## Actions sensibles

Les actions suivantes doivent rester protégées par confirmation utilisateur explicite :

- winget avec acceptation d'accords/licences ;
- ProcDump/Sysinternals, dont toute acceptation d'EULA tierce comme Microsoft/Sysinternals avec `-accepteula` ;
- export Wi-Fi avec `key=clear` ;
- partage ou copie de prompt IA base sur un rapport système ;
- modification globale de crash handler Windows AeDebug.

## Outils tiers

Ne pas redistribuer d'exécutables tiers dans une release publique sans droits explicites. Garder uniquement `Tools/README.md` si nécessaire.

