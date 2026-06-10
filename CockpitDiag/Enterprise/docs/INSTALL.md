# Installation

## Télécharger

Téléchargez CockpitDiag Enterprise v1.0 depuis le lien fourni :

```text
https://toolkitsoftware.tech/downloads/private/cockpitdiag-v1-0-20260610-f8276780/CockpitDiag_Enterprise_v1.0.zip
```

## Vérifier le SHA256

Empreinte attendue :

```text
f8276780a1c9959e5c1c2869e51ca0e5e232c3cb2e9cef4467eb0d02d5a4139f
```

Sous Windows PowerShell :

```powershell
Get-FileHash .\CockpitDiag_Enterprise_v1.0.zip -Algorithm SHA256
```

La valeur affichée doit correspondre exactement au SHA256 attendu.

## Extraire

Extrayez le ZIP dans un dossier local, par exemple :

```text
C:\Tools\CockpitDiag_Enterprise_v1.0
```

Évitez de lancer l'application directement depuis le ZIP.

## Ajouter la licence

Copiez le fichier `license.json` fourni séparément par Toolkit Software Solution à la racine du dossier extrait, au même niveau que `CockpitDiag.exe`.

```text
CockpitDiag_Enterprise_v1.0\
+-- CockpitDiag.exe
+-- license.json
```

Le fichier doit s'appeler exactement `license.json`.

## Lancer

Lancez :

```text
CockpitDiag.exe
```

L'exécution administrateur est recommandée pour les fonctions de diagnostic et maintenance système.

## Support

Contact : contact@toolkitsoftware.tech
