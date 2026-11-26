# The Sims Four Seasons

**First public beta · 1.0.0-beta.1**

**English** · [Polski](docs/README.pl-PL.md) · [Dansk](docs/README.da-DK.md) · [Deutsch](docs/README.de-DE.md) · [Español](docs/README.es-ES.md) · [Suomi](docs/README.fi-FI.md) · [Français](docs/README.fr-FR.md) · [Italiano](docs/README.it-IT.md) · [日本語](docs/README.ja-JP.md) · [한국어](docs/README.ko-KR.md) · [Norsk bokmål](docs/README.nb-NO.md) · [Nederlands](docs/README.nl-NL.md) · [Português (Brasil)](docs/README.pt-BR.md) · [Svenska](docs/README.sv-SE.md) · [ไทย](docs/README.th-TH.md) · [简体中文](docs/README.zh-CN.md) · [繁體中文](docs/README.zh-TW.md)

Four seasons for The Sims Legacy Collection. A storm can send your Sims running indoors, fresh snow settles on the garden, and the lot’s weather and calendar pick up where you left them when you load your save. This is an unofficial fan mod.

![A snow-covered garden](media/winter.png)

[Screenshots](#gallery) · [Full gallery (ZIP, 8 images)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## What changes on your lot

### The week, the seasons and tomorrow’s forecast

- The calendar runs from Monday to Sunday. On Saturdays and Sundays children have school off and working Sims have the weekend off. The school bus and carpool stay away, and the weekend does not count as a missed workday. Overnight shifts are accounted for.
- Each home lot keeps its own calendar. Spring, summer, autumn and winter last seven Sim days each by default. Choose 14 or 28 days per season for a longer year. Under **Ctrl+Alt+R**, the calendar lets you set the season, day of the season, weekday and time. Saving a household preserves its weather and calendar.
- The collapsible forecast panel shows today’s weekday, season, temperature and weather. Tomorrow is split into night, morning, afternoon and evening. In automatic weather mode, Sims can also watch the forecast on supported televisions.
- On ordinary community trips the family takes its weather and seasonal progress along. Vacation Island has its own climates: winter in the mountains, spring in the forest and summer at the beach. Time on vacation leaves the home calendar where you left it.

### Weather in the garden and in the house

- Rain, thunderstorms, hail, snow, blizzards and fog can arrive on their own. Rain can give way to fog. Wind carries rain and autumn leaves across the lot. Lightning is followed by thunder, water runs off roofs, and ordinary rain can put out an outdoor fire, including one started by lightning.
- Rain waters exposed plants. Heavy hail can damage outdoor ornamental plants. Fireflies appear near shrubs and flowers at night, especially in summer. In autumn the foliage changes colour. In winter frost and snow accumulate on the ground, roofs, roads, fences, plants, outdoor objects and gravestones, then melt as conditions warm.
- Sims, cats and dogs get wet outdoors and dry faster under cover. They may seek shelter or leave a small puddle that can be mopped up. After a long soaking, a Sim can fall ill, cough and sneeze, then recover somewhere dry. Children may splash in outdoor puddles on their own. Adults and children can do it for fun when directed.
- Sims can change into winter clothes outdoors below freezing. Buy a snowman building spot for **§1** and place it outside. When snow cover reaches **60%**, Sims can build there, including on community and vacation lots.

### Two new spells for the spellbook

An adult Sim with a wand can prepare either recipe in the wand charger. Use one of each ingredient. A batch gives **three charges**. Choose **Cast spell…** on the charger. A successful cast brings **three Sim hours** of magical weather, even on a lot without a weather station.

- **Mist of Enchantment** uses Pixie Dust, Dragon Tears and Toadstools. Garden gnomes and scarecrows may come to life, lawn flamingos can turn into dancers, chess and checkers boards can play by themselves, and refrigerator doors can move on their own. Harvestable toadstools may sprout, and ghosts can become more active around eligible graves between **22:00 and 06:00**. While the mist lasts, supported objects can replenish energy, fun, hygiene, bladder and hunger **50% faster**, and skill objects can teach at **double speed**. You can adjust the frequency of magical events and toggle individual bonuses.
- **Rain of Enchantment** uses Pixie Dust, Dragon Tears and Clown Confetti. Coloured raindrops leave animated rainbow puddles. The rain waters and improves exposed living plants and can ripen planted crops. Up to **seven** of the original *Makin’ Magic* ability crystals can grow on free grass. They remain when the shower ends and can teach their abilities once mature.
- Magical weather can also occur naturally. In Magic Town, magical mist is more likely, especially at night, and magical rain is more likely outside winter.

### Forecasts, weather control and sound

- Automatic weather needs no purchased object. The optional weather station costs **§10,000**. A Sim with **7 Logic** and **6 Mechanical** can use its controls to change weather and calendar settings. If one Sim reaches **10 in both skills**, the household can earn a free station once.
- The weather panel has individual switches for wetness, rain reactions, illness, winter clothes, shelter from hail, rain puddles, drying puddles, splashing, snowmen, firefighting by rain and fog after rain. You can also tune effects, sound and animation performance. Weather follows the game’s pause, speed, zoom and camera.
- The mod includes localized loading screens and an original loading theme, *Pocztówka z doliny*.

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

<!-- gallery -->
<a name="gallery"></a>

## Screenshots

| Autumn rain | Fog over the lot |
| --- | --- |
| ![Autumn rain](media/autumn.png) | ![Fog over the lot](media/weather.png) |

| Hail in the garden | Magical mist |
| --- | --- |
| ![Hail in the garden](media/hail.png) | ![Magical mist](media/magic-fog.png) |

| Magical rain and puddles | English loading screen |
| --- | --- |
| ![Magical rain and puddles](media/magic-rain.png) | ![English loading screen](media/loading-screen-en.png) |

**Tomorrow’s forecast**

![Tomorrow’s forecast](media/forecast-en.png)

<!-- /gallery -->

## Beta testing and bug reports

Installer checks cover both supported builds. Testing on other PCs, lower-end hardware and full play sessions in all 17 languages is ongoing. If the weather display slows down with the NVIDIA overlay active, try a session with that overlay disabled.

Use [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) on GitHub. Include your game and mod versions, language and steps to reproduce. For a visual issue, add a screenshot and note the weather, zoom, camera angle, floor and wall mode. For installation issues, include the full error text. Check logs for personal file paths before sharing.
