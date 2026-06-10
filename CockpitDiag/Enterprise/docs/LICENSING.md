# Licensing

CockpitDiag Enterprise est un logiciel proprietaire concede sous licence.

## Editions

Les editions utilisees pour CockpitDiag Enterprise peuvent inclure :

- `Trial`
- `Enterprise`
- `Partner`
- `Internal`

Ces editions definissent les droits, la duree, les fonctionnalites et les usages autorises selon les conditions accordees par Toolkit Software Solution.

## Fichier De Licence

L'activation peut utiliser un fichier :

```text
license.json
```

Ce fichier est fourni separement aux clients ou testeurs autorises.

Il doit etre place a la racine du dossier CockpitDiag Enterprise, au meme niveau que `CockpitDiag.exe`.

## Validation

CockpitDiag Enterprise utilise le module `CockpitDiag.Licensing.dll` pour la validation de licence.

En cas d'absence, de corruption, d'erreur de chargement ou de reponse invalide du module de licence, CockpitDiag Enterprise doit rester en mode verrouille ou limite.

## Restrictions

Sauf autorisation ecrite explicite de Toolkit Software Solution, il est interdit de :

- partager ou publier `license.json` ;
- revendre ou transferer une licence ;
- contourner le controle de licence ;
- modifier ou neutraliser `CockpitDiag.Licensing.dll` ;
- redistribuer un paquet modifie.

## Changement De Machine

Certaines licences peuvent etre liees a une machine via un identifiant hache. En cas de changement de machine, contactez Toolkit Software Solution.

## Contact

contact@toolkitsoftware.tech
