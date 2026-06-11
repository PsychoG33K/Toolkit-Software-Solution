# Installation

## Télécharger

Téléchargez CockpitDiag Enterprise v1.0 depuis le lien fourni :

```text
https://toolkitsoftware.tech/downloads/private/cockpitdiag-v1-0-20260611-7a76ceed/CockpitDiag_Enterprise_v1.0.zip
```

## Vérifier le SHA256

Empreinte attendue :

```text
7a76ceed9d5d20b724d0691ab043fa1166da8f50ef6ec1790f7eeea66c4a6074
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
