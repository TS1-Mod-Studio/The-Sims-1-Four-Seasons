# Les Sims Quatre Saisons

**Première bêta publique · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · **Français** · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

Les quatre saisons arrivent dans The Sims Legacy Collection. Un orage peut pousser vos Sims à rentrer et la neige tient jusque dans le jardin. Lorsque vous chargez une sauvegarde, vous retrouvez la météo et le calendrier de votre terrain. Ce mod est une création non officielle de fans.

![Brouillard sur un terrain résidentiel dans The Sims Legacy Collection](../media/weather.png)

[Feuillages d’automne](../media/autumn.png) · [Un jardin sous la neige](../media/winter.png) · [Galerie complète (ZIP, 8 images)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## La météo sur votre terrain

- Pluie, orages, grêle, neige, blizzards et brouillard suivent le rythme des saisons. La station météo facultative vous permet aussi de choisir le temps, y compris la pluie ou le brouillard magiques.
- Le feuillage change de couleur en automne. En hiver, la neige se dépose sur les routes, la végétation et les objets à l’extérieur, jusqu’aux pierres tombales. Les enfants peuvent patauger dans les flaques et les Sims peuvent faire un bonhomme de neige lorsque la couche est assez épaisse.
- Les Sims, les chiens et les chats peuvent être trempés et chercher un abri. La pluie peut éteindre un incendie à ciel ouvert. Vous pouvez régler séparément les effets de la météo sur le jeu. Le chargement s’accompagne d’un morceau original, *Pocztówka z doliny*.

## Télécharger et installer

La version complète de The Sims Legacy Collection **1.10.0** ou **1.10.7** doit être installée sur Windows 64 bits. Installez également [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0). Prévoyez plusieurs Go d’espace libre, en plus de la place nécessaire à une copie de vos sauvegardes.

1. Sur GitHub, ouvrez la page de la version **1.0.0-beta.1** dans [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1) et téléchargez `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` sous **Assets**.
2. Sauvegardez votre partie, puis fermez le jeu et l’application météo. Décompressez toute l’archive ZIP dans un nouveau dossier. Le dossier `data` doit se trouver à côté de `Setup.exe`.
3. Lancez `Setup.exe` et sélectionnez le dossier du jeu qui contient `sims.exe`. Cliquez sur **Vérifier la compatibilité**, puis sur **Installer**. Le programme vérifie et sauvegarde les fichiers avant d’appliquer les correctifs à votre installation. Un conflit avec un fichier indispensable interrompt l’installation.
4. Attendez la fin de l’installation. Pour jouer, utilisez le raccourci **The Sims Cztery Pory Roku** sur le bureau ou `Launch-weather.cmd` dans le dossier de l’application installée. Le jeu, la météo et le suivi des sauvegardes démarrent ensemble.

Laissez le programme d’installation modifier les fichiers du jeu. Il vérifie leurs sommes de contrôle avant et après chaque modification et conserve `sims.exe` intact. Les objets facultatifs sont mis à jour uniquement si une version compatible est déjà installée.

## En jeu

Chargez un terrain pour activer la météo automatique. Appuyez sur `Ctrl+Alt+R` pour régler les précipitations, le son, le calendrier et les effets sur les Sims. Les menus des objets utilisent la langue du jeu. Le panneau météo l’adopte par défaut. Si vous choisissez une autre langue pour le panneau, elle sera utilisée au prochain démarrage.

## Sauvegardes, mises à jour et désinstallation

Le programme d’installation copie les fichiers concernés, les parties sauvegardées et les données météo. Conservez `backups` et `install-state.json` dans le dossier de l’application sous `%LOCALAPPDATA%\TS1CzteryPoryRoku`. Les données météo des terrains sont aussi stockées sous `%LOCALAPPDATA%\TS1RainOverlay`. Vous pouvez restaurer manuellement une partie à partir de sa copie une fois le jeu fermé. Laissez les dossiers du jeu et de l’application à leur emplacement d’installation.

La sauvegarde inclut `Electronic Arts\The Sims 25` dans le dossier des parties enregistrées de Windows, ainsi que les éventuels dossiers `UserData`, `UserData2` du répertoire du jeu. Chaque copie est placée dans un dossier distinct. Le fichier `save-backup.json` indique les chemins d’origine et les sommes de contrôle pour vous aider à identifier les fichiers à restaurer.

Pour une mise à jour, fermez le jeu et l’application météo, décompressez le nouveau ZIP dans un dossier distinct et choisissez le même dossier du jeu dans le nouveau programme d’installation. Pour retirer le mod, fermez les deux programmes et choisissez **Options → Désinstaller** dans la copie de `Setup.exe` que vous avez conservée. Les fichiers d’origine sont restaurés et vos parties et copies de sauvegarde sont conservées. Si vous souhaitez retrouver les objets du mod, gardez une copie du terrain datant d’avant votre partie sans le mod.

Si l’installation a été interrompue, choisissez **Options → Annuler les modifications**. Si la restauration signale qu’un fichier a été modifié, conservez le message et vos copies de sauvegarde. Si Windows refuse l’accès en écriture, lancez `Setup.exe` en tant qu’administrateur depuis le même compte Windows.

## Tester la bêta et signaler un problème

Les tests d’installation couvrent les deux versions du jeu prises en charge. Les retours sur d’autres PC, sur du matériel moins puissant et après de longues parties dans les 17 langues sont les bienvenus. En cas de ralentissement des effets météo, essayez de désactiver la superposition NVIDIA si elle est active.

Signalez le problème dans [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) sur GitHub. Indiquez les versions du jeu et du mod, la langue et les étapes permettant de le reproduire. Pour un défaut visuel, joignez une capture d’écran et précisez le temps, le zoom, l’angle de la caméra, l’étage et le mode d’affichage des murs. En cas d’échec de l’installation, joignez le message d’erreur complet. Vérifiez que les journaux ne contiennent pas de chemins de fichiers personnels avant de les partager.
