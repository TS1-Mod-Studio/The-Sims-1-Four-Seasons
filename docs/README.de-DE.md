# Die Sims Vier Jahreszeiten

**Erste öffentliche Beta · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · **Deutsch** · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

Vier Jahreszeiten für The Sims Legacy Collection. Ein Gewitter kann deine Sims ins Haus treiben, frischer Schnee bleibt im Garten liegen, und beim Laden eines Spielstands kehren Wetter und Kalender des Grundstücks zurück. Dies ist eine inoffizielle Fan-Mod.

![Nebel auf einem Wohngrundstück in The Sims Legacy Collection](../media/weather.png)

[Herbstlaub](../media/autumn.png) · [Ein verschneiter Garten](../media/winter.png) · [Vollständige Galerie (ZIP, 8 Bilder)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## Das Wetter auf deinem Grundstück

- Je nach Jahreszeit gibt es Regen, Gewitter, Hagel, Schnee, Schneestürme und Nebel. Mit der optionalen Wetterstation kannst du das Wetter selbst bestimmen, einschließlich magischem Regen und magischem Nebel.
- Im Herbst färbt sich das Laub. Im Winter bleibt Schnee auf Straßen, Pflanzen und Gegenständen im Freien liegen, auch auf Grabsteinen. Kinder können in Pfützen plantschen. Liegt genug Schnee, können Sims einen Schneemann bauen.
- Sims, Hunde und Katzen werden durchnässt und können Schutz suchen. Regen kann Brände im Freien löschen. Welche Auswirkungen das Wetter auf das Spiel hat, kannst du einzeln einstellen. Beim Laden hörst du das eigens komponierte Stück *Pocztówka z doliny*.

## Download und Installation

Du brauchst eine installierte Vollversion von The Sims Legacy Collection in Version **1.10.0** oder **1.10.7**, Windows mit 64 Bit und die [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0). Plane mehrere GB freien Speicherplatz sowie Platz für eine Kopie deiner Spielstände ein.

1. Öffne auf der GitHub-Projektseite [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1), wähle **1.0.0-beta.1** und lade unter **Assets** das Archiv `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` herunter.
2. Speichere dein Spiel und schließe das Spiel und das Wetterprogramm. Entpacke das gesamte ZIP-Archiv in einen neuen Ordner. `data` und `Setup.exe` müssen im selben Ordner liegen.
3. Starte `Setup.exe` und wähle den Spielordner mit `sims.exe` aus. Klicke zuerst auf **Kompatibilität prüfen** und anschließend auf **Installieren**. Das Programm prüft und sichert die Dateien und wendet die Patches auf deine Spieldaten an. Bei einem Konflikt mit einer erforderlichen Datei bricht es die Installation ab.
4. Warte, bis die Installation abgeschlossen ist. Starte das Spiel künftig über die Desktopverknüpfung **The Sims Cztery Pory Roku** oder über `Launch-weather.cmd` im Installationsordner des Wetterprogramms. So starten Spiel, Wetter und Spielstandverarbeitung gemeinsam.

Überlasse das Ändern der Spieldateien dem Installationsprogramm. Es prüft vor und nach jedem Patch die Prüfsummen und lässt `sims.exe` unverändert. Optionale Objekte werden nur angepasst, wenn eine unterstützte Version davon bereits installiert ist.

## Im Spiel

Sobald du ein Grundstück lädst, wechselt das Wetter automatisch. Mit `Ctrl+Alt+R` öffnest du die Einstellungen für Niederschlag, Ton, Kalender und Spielmechanik. Die Objektmenüs verwenden die Spielsprache, das Wetterfenster übernimmt sie standardmäßig ebenfalls. Eine andere Sprache für das Wetterfenster wird beim nächsten Start aktiv.

## Sicherung, Aktualisierung und Deinstallation

Das Installationsprogramm sichert betroffene Dateien, Spielstände und Wetterdaten. Bewahre `backups` und `install-state.json` im Programmordner unter `%LOCALAPPDATA%\TS1CzteryPoryRoku` auf. Wetterdaten einzelner Grundstücke liegen auch unter `%LOCALAPPDATA%\TS1RainOverlay`. Gesicherte Spielstände kannst du bei geschlossenem Spiel manuell wiederherstellen. Lass den Spiel- und den Programmordner an ihrem ursprünglichen Ort.

Die Sicherung umfasst `Electronic Arts\The Sims 25` im Windows-Ordner für gespeicherte Spiele sowie vorhandene `UserData`, `UserData2`-Ordner im Spielverzeichnis. Jede Sicherung erhält einen eigenen Ordner. In `save-backup.json` stehen die ursprünglichen Pfade und Prüfsummen, mit denen du die gewünschten Dateien für eine manuelle Wiederherstellung findest.

Für ein Update schließt du Spiel und Wetterprogramm, entpackst das neue ZIP in einen separaten Ordner und wählst im neuen Installationsprogramm denselben Spielordner. Zum Entfernen schließt du beide Programme und wählst in der aufbewahrten `Setup.exe` die Option **Optionen → Deinstallieren**. Die ursprünglichen Dateien werden wiederhergestellt, Spielstände und Sicherungen bleiben erhalten. Möchtest du die Mod-Objekte später wieder nutzen, behalte eine Kopie des Grundstücks aus der Zeit vor dem Spielen ohne Mod.

Wurde die Installation unterbrochen, wähle **Optionen → Änderungen zurücksetzen**. Meldet die Wiederherstellung eine veränderte Datei, bewahre die Meldung und die Sicherungen auf. Verweigert Windows den Schreibzugriff, starte `Setup.exe` mit Administratorrechten unter demselben Windows-Konto.

## Beta testen und Fehler melden

Die Installationstests decken beide unterstützten Spielversionen ab. Rückmeldungen zu anderen PCs, schwächerer Hardware und längeren Spielsitzungen in allen 17 Sprachen sind willkommen. Ruckelt die Wetterdarstellung bei aktivem NVIDIA-Overlay, teste sie auch mit ausgeschaltetem Overlay.

Melde Fehler unter [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) auf GitHub. Gib Spiel- und Mod-Version, Sprache und die Schritte zum Nachstellen an. Bei Grafikfehlern helfen ein Screenshot sowie Angaben zu Wetter, Zoom, Kamerawinkel, Stockwerk und Wandansicht. Bei Installationsfehlern füge die vollständige Fehlermeldung bei. Prüfe Protokolle vor dem Hochladen auf persönliche Dateipfade.
