# Installation

## Distribution

Distribution contrôlée sur demande via le canal officiel Toolkit Software Solution.

Contact : contact@toolkitsoftware.tech — le ZIP et le `license.json` sont fournis séparément aux clients autorisés.

## Vérifier le SHA256

Empreinte attendue :

```text
233396cd0ae553a55bd60e3b4b6000730d8736d7f08cbf0a076f6698fe1eb87c
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
