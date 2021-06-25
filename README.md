# Analyse du pack d'optimisation de @InfoOpti
Vous trouverez ci-dessous son pack d'optimisation. Il y'a beaucoup de choses qui peut causer des pertes de fonctionnalités, des pertes considérables de performances.

[![Header](https://pbs.twimg.com/media/E4vIf_9WEAoaLxE?format=png&name=900x900 "Header")](https://pbs.twimg.com/media/E4vIf_9WEAoaLxE?format=png&name=900x900)

```
Memory Cleaner.exe
→ Pourquoi vider la ram c'est inutile? https://pastebin.com/kEeQvfT3
```
```
Enlever AccéSouris.reg
Une explication parfaite sur l'accélération souris by @Piwielle : https://youtu.be/YM9SdIT6K20
```
```
Fortnite.Ink
Pourquoi vouloir créer un raccourcis, ça fais gagner des FPS ? NON
```
```
InSpectre.exe
Ce logiciel permet d'empêcher les attaques Meltdown et Spectre. Mais pourquoi les désactiver sa fais gagner des FPS ? NON
```
```
16GB.reg
[HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Control]
"SvcHostSplitThresholdInKB"=dword:16777216
Ce regedit permet de rassembler les SvcHost. lorsqu'un service d'un hôte de service échoue, tous les services de l'hôte de service échouent, ça fais gagner 0 FPS
```
```
Defender.reg
Pourquoi désactiver l'anti-virus qui vous protège des malwares? Est-ce qu'on gagne des FPS ? NON, un peu de RAM.
```
```
Delete Temp Files.Ink
C'est vrai que c'est compliqué de faire "Windows" + "R", tapez "%temp% et "temp" et de supprimer les fichiers.
```
```
Device Cleanup.exe
J'approuve, mais cela ne fais gagner 0 FPS.
```
```
Pourquoi lancer un .exe pour désactiver Cortana alors que tu peux ouvrir le CMD et taper "powershell Get-AppxPackage -allusers Microsoft.549981C3F5F10 ^| Remove-AppxPackage"
