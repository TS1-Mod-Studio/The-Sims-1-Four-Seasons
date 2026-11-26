# The Sims Four Seasons

**First public beta · 1.0.0-beta.1**

**English** · [Polski](docs/README.pl-PL.md) · [Dansk](docs/README.da-DK.md) · [Deutsch](docs/README.de-DE.md) · [Español](docs/README.es-ES.md) · [Suomi](docs/README.fi-FI.md) · [Français](docs/README.fr-FR.md) · [Italiano](docs/README.it-IT.md) · [日本語](docs/README.ja-JP.md) · [한국어](docs/README.ko-KR.md) · [Norsk bokmål](docs/README.nb-NO.md) · [Nederlands](docs/README.nl-NL.md) · [Português (Brasil)](docs/README.pt-BR.md) · [Svenska](docs/README.sv-SE.md) · [ไทย](docs/README.th-TH.md) · [简体中文](docs/README.zh-CN.md) · [繁體中文](docs/README.zh-TW.md)

Four seasons for The Sims Legacy Collection. A storm can send your Sims running indoors, fresh snow settles on the garden, and the lot’s weather and calendar pick up where you left them when you load your save. This is an unofficial fan mod.

![Fog on a residential lot in The Sims Legacy Collection](media/weather.png)

[Autumn foliage](media/autumn.png) · [A snow-covered garden](media/winter.png) · [Full gallery (ZIP, 8 images)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## What changes on your lot

- Rain, thunderstorms, hail, snow, blizzards and fog follow the seasonal calendar. The optional weather station lets you choose the weather yourself, including magic rain and magic fog.
- Autumn changes the foliage. In winter, snow settles on roads, plants and outdoor objects, including gravestones. Children can splash in puddles and Sims can build a snowman when enough snow has accumulated.
- Sims, dogs and cats can get soaked or seek shelter. Rain can put out outdoor fires. You can adjust individual gameplay effects in the weather panel. The mod also includes an original loading theme, *Pocztówka z doliny*.

## Download and install

You need the full The Sims Legacy Collection installed on 64-bit Windows, game build **1.10.0** or **1.10.7**, and [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0). Allow several GB of free space plus room for a copy of your saves.

1. On the project’s GitHub page, open [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1), choose **1.0.0-beta.1**, and download `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` under **Assets**.
2. Save your game and close both the game and the weather app. Extract the entire ZIP to a new folder. Keep `data` beside `Setup.exe`.
3. Run `Setup.exe` and select the game folder containing `sims.exe`. Choose **Check compatibility** to check the files, then **Install**. The installer verifies the files, backs them up and applies patches to your own game assets. A conflicting required file stops the installation.
4. Wait for the completion message. Start future sessions with the **The Sims Cztery Pory Roku** desktop shortcut or `Launch-weather.cmd` in the installed app folder. This starts the game and its weather and save services together.

Let the installer patch the game files. It checks their hashes before and after applying each patch and leaves `sims.exe` intact. It patches optional objects only when a supported version is already installed.

## Playing

Load a lot to see automatic weather. Press `Ctrl+Alt+R` to open the panel for precipitation, sound, the calendar and gameplay settings. Object menus follow the game language. The panel also follows the game language by default. A language you select in the panel takes effect on the next launch.

## Backups, updates and removal

The installer backs up the affected files, game saves and weather data. Keep `backups` and `install-state.json` together in the installed app folder under `%LOCALAPPDATA%\TS1CzteryPoryRoku`. Lot weather data also lives under `%LOCALAPPDATA%\TS1RainOverlay`. Save backups are available for manual recovery with the game closed. Leave the game and app folders in their installed locations.

Save backups include the Windows Saved Games folder `Electronic Arts\The Sims 25` and any `UserData`, `UserData2` folders in the game directory. Each backup has its own folder. `save-backup.json` records the original paths and checksums so you can identify the files to restore.

For an update, close the game and weather app, extract the new ZIP to a separate folder and select the same game folder in its installer. To remove the mod, close both apps and choose **Options → Uninstall** in the copy of `Setup.exe` you kept. This restores the original files and retains your saves and backups. If you plan to use the mod’s objects again, keep a copy of the lot from before playing without the mod.

After an interrupted installation, use **Options → Roll back**. If restoration reports that a file has changed, keep the error message and the backups. If Windows denies write access, run `Setup.exe` as administrator from the same Windows account.

## Beta testing and bug reports

Installer checks cover both supported builds. Testing on other PCs, lower-end hardware and full play sessions in all 17 languages is ongoing. If the weather display slows down with the NVIDIA overlay active, try a session with that overlay disabled.

Use [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) on GitHub. Include your game and mod versions, language and steps to reproduce. For a visual issue, add a screenshot and note the weather, zoom, camera angle, floor and wall mode. For installation issues, include the full error text. Check logs for personal file paths before sharing.
