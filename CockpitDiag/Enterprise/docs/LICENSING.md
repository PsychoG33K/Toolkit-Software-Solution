# Licensing

CockpitDiag Enterprise est un logiciel propriétaire concédé sous licence.

## Éditions

Les éditions utilisées pour CockpitDiag Enterprise peuvent inclure :

- `Trial`
- `Enterprise`
- `Partner`
- `Internal`

Ces éditions définissent les droits, la durée, les fonctionnalités et les usages autorisés selon les conditions accordées par Toolkit Software Solution.

## Fichier De Licence

L'activation peut utiliser un fichier :

```text
license.json
```

Ce fichier est fourni séparément aux clients ou testeurs autorisés.

Il doit être placé à la racine du dossier CockpitDiag Enterprise, au même niveau que `CockpitDiag.exe`.

## Validation

CockpitDiag Enterprise utilise le module `CockpitDiag.Licensing.dll` pour la validation de licence.

En cas d'absence, de corruption, d'erreur de chargement ou de réponse invalide du module de licence, CockpitDiag Enterprise doit rester en mode verrouillé ou limité.

## Restrictions

Sauf autorisation écrite explicite de Toolkit Software Solution, il est interdit de :

- partager ou publier `license.json` ;
- revendre ou transférer une licence ;
- contourner le contrôle de licence ;
- modifier ou neutraliser `CockpitDiag.Licensing.dll` ;
- redistribuer un paquet modifié.

## Changement De Machine

Certaines licences peuvent être liées à une machine via un identifiant haché. En cas de changement de machine, contactez Toolkit Software Solution.

## Contact

contact@toolkitsoftware.tech
