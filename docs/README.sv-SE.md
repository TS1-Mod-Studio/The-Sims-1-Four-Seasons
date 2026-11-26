# The Sims Fyra årstider

**Första offentliga betaversionen · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · **Svenska** · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

Fyra årstider i The Sims Legacy Collection. Ett åskväder kan få dina simmar att springa inomhus, och nysnö lägger sig i trädgården. När du laddar ett sparat spel får tomten tillbaka sitt väder och sin kalender. Det här är en inofficiell mod gjord av fans.

![Dimma på en bostadstomt i The Sims Legacy Collection](../media/weather.png)

[Höstlöv](../media/autumn.png) · [En snötäckt trädgård](../media/winter.png) · [Hela galleriet (ZIP, 8 bilder)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## Väder på tomten

- Regn, åska, hagel, snö, snöstormar och dimma följer årstiderna. Med den valfria väderstationen kan du också välja väder själv, till exempel magiskt regn eller magisk dimma.
- Löven skiftar färg på hösten. På vintern lägger sig snön på vägar, växter och föremål utomhus, även gravstenar. Barn kan plaska i vattenpölar och simmar kan bygga en snögubbe när det finns tillräckligt med snö.
- Simmar, hundar och katter kan bli genomblöta och söka skydd. Regn kan släcka bränder under bar himmel. Du väljer själv vilka effekter vädret har på spelet. Under laddningen spelas den nyskrivna melodin *Pocztówka z doliny*.

## Ladda ner och installera

Du behöver ha den fullständiga versionen av The Sims Legacy Collection **1.10.0** eller **1.10.7** installerad på 64-bitars Windows samt [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0). Räkna med flera GB ledigt utrymme utöver plats för en kopia av dina sparade spel.

1. Gå till [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1) på projektets GitHub-sida, välj **1.0.0-beta.1** och ladda ner `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` under **Assets**.
2. Spara spelet och stäng både spelet och väderprogrammet. Packa upp hela ZIP-filen i en ny mapp. Låt mappen `data` ligga bredvid `Setup.exe`.
3. Starta `Setup.exe` och välj spelmappen som innehåller `sims.exe`. Välj **Kontrollera kompatibilitet** och sedan **Installera**. Installationsprogrammet kontrollerar och säkerhetskopierar filerna och tillämpar ändringarna på dina egna spelfiler. Om en nödvändig fil inte stämmer avbryts installationen.
4. Vänta tills installationen är klar. Starta sedan spelet med skrivbordsgenvägen **The Sims Cztery Pory Roku** eller `Launch-weather.cmd` i det installerade programmets mapp. Då startas spelet, vädret och funktionen som återställer väder från sparade spel tillsammans.

Låt installationsprogrammet ändra spelfilerna. Det kontrollerar filernas kontrollsummor före och efter varje ändring och lämnar `sims.exe` orörd. Valfria föremål uppdateras bara om en version som stöds redan är installerad.

## I spelet

Ladda en tomt för att se det automatiska vädret. Med `Ctrl+Alt+R` öppnar du inställningarna för nederbörd, ljud, kalender och vädrets inverkan på spelet. Föremålens menyer använder spelets språk. Väderpanelen följer också spelets språk som standard. Ett annat språk för panelen börjar gälla nästa gång du startar spelet.

## Säkerhetskopior, uppdateringar och avinstallation

Installationsprogrammet säkerhetskopierar berörda filer, sparade spel och väderdata. Behåll `backups` och `install-state.json` i programmets mapp under `%LOCALAPPDATA%\TS1CzteryPoryRoku`. Väderdata för tomterna finns även under `%LOCALAPPDATA%\TS1RainOverlay`. Du kan återställa sparade spel manuellt från kopiorna när spelet är stängt. Låt spelmappen och programmappen ligga kvar där de installerades.

Säkerhetskopian omfattar `Electronic Arts\The Sims 25` i Windows-mappen för sparade spel samt eventuella `UserData`, `UserData2`-mappar i spelmappen. Varje säkerhetskopia får en egen mapp. I `save-backup.json` hittar du filernas ursprungliga sökvägar och kontrollsummor så att du kan identifiera de filer du vill återställa.

För att uppdatera stänger du spelet och väderprogrammet, packar upp den nya ZIP-filen i en separat mapp och väljer samma spelmapp i det nya installationsprogrammet. För att ta bort modden stänger du båda programmen och väljer **Alternativ → Avinstallera** i den sparade kopian av `Setup.exe`. Originalfilerna återställs och dina sparade spel och säkerhetskopior finns kvar. Vill du använda moddens föremål igen senare, behåll en kopia av tomten från innan du spelade utan modden.

Om installationen avbröts väljer du **Alternativ → Ångra ändringar**. Om återställningen rapporterar att en fil har ändrats, behåll felmeddelandet och säkerhetskopiorna. Om Windows nekar skrivåtkomst, kör `Setup.exe` som administratör från samma Windows-konto.

## Betatest och felrapporter

Installationen har testats för båda spelversionerna. Vi tar gärna emot resultat från andra datorer, svagare maskinvara och längre spelsessioner på alla 17 språk. Om vädereffekterna hackar när NVIDIA-överlägget är aktivt, prova att stänga av överlägget.

Rapportera fel under [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) på GitHub. Ange spelversion, modversion, språk och hur felet kan återskapas. Vid grafikfel hjälper en skärmbild och uppgifter om väder, zoom, kameravinkel, våningsplan och väggvisning. Vid installationsfel behöver vi hela felmeddelandet. Kontrollera om loggarna innehåller personliga filsökvägar innan du delar dem.
