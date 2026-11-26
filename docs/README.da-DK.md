# The Sims Fire Årstider

**Første offentlige betaversion · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · **Dansk** · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

Fire årstider i The Sims Legacy Collection. Et tordenvejr kan få dine simmere til at søge indendørs, og nyfalden sne lægger sig i haven. Når du indlæser et gemt spil, får grunden sit vejr og sin kalender tilbage. Dette er en uofficiel mod lavet af fans.

![Tåge på en beboelsesgrund i The Sims Legacy Collection](../media/weather.png)

[Efterårsløv](../media/autumn.png) · [En snedækket have](../media/winter.png) · [Hele galleriet (ZIP, 8 billeder)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## Vejret på din grund

- Regn, torden, hagl, sne, snestorme og tåge følger årstiderne. Med den valgfrie vejrstation kan du også selv vælge vejret, herunder magisk regn og magisk tåge.
- Bladene skifter farve om efteråret. Om vinteren lægger sneen sig på veje, planter og udendørs genstande, også gravsten. Børn kan plaske i vandpytter, og simmerne kan bygge en snemand, når der ligger nok sne.
- Simmere, hunde og katte kan blive gennemblødte og søge ly. Regn kan slukke brande under åben himmel. Du kan selv vælge, hvordan vejret påvirker spillet. Under indlæsningen spiller den nye melodi *Pocztówka z doliny*.

## Download og installation

Du skal have den fulde udgave af The Sims Legacy Collection **1.10.0** eller **1.10.7** installeret på 64-bit Windows samt [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0). Sørg for flere GB ledig plads og ekstra plads til en kopi af dine gemte spil.

1. Åbn [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1) på projektets GitHub-side, vælg **1.0.0-beta.1**, og hent `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` under **Assets**.
2. Gem dit spil, og luk både spillet og vejrprogrammet. Pak hele ZIP-filen ud i en ny mappe. Lad mappen `data` ligge ved siden af `Setup.exe`.
3. Kør `Setup.exe`, og vælg den spilmappe, der indeholder `sims.exe`. Vælg **Kontrollér kompatibilitet** og derefter **Installer**. Installationsprogrammet kontrollerer og sikkerhedskopierer filerne, før det ændrer dine egne spilfiler. En konflikt i en nødvendig fil standser installationen.
4. Vent, til installationen er gennemført. Start fremover spillet via genvejen **The Sims Cztery Pory Roku** på skrivebordet eller via `Launch-weather.cmd` i den installerede programmappe. Så starter spillet sammen med vejret og det modul, der gendanner vejret i gemte spil.

Lad installationsprogrammet opdatere spilfilerne. Det kontrollerer hver fils kontrolsum før og efter ændringen. `sims.exe` forbliver urørt. Valgfrie genstande opdateres kun, hvis der allerede er installeret en understøttet version.

## I spillet

Indlæs en grund for at se det automatiske vejr. Med `Ctrl+Alt+R` åbner du indstillingerne for nedbør, lyd, kalender og vejrets indflydelse på spillet. Genstandenes menuer bruger spillets sprog. Vejrpanelet følger som udgangspunkt også spillets sprog. Hvis du vælger et andet sprog til panelet, træder ændringen i kraft, næste gang du starter spillet.

## Sikkerhedskopier, opdatering og afinstallation

Installationsprogrammet sikkerhedskopierer de berørte filer, dine gemte spil og vejrdata. Behold `backups` og `install-state.json` sammen i programmappen under `%LOCALAPPDATA%\TS1CzteryPoryRoku`. Vejrdata for grundene findes også under `%LOCALAPPDATA%\TS1RainOverlay`. Du kan gendanne gemte spil manuelt fra kopierne, mens spillet er lukket. Behold spillet og programmet i deres oprindelige mapper.

Sikkerhedskopien omfatter `Electronic Arts\The Sims 25` i Windows-mappen til gemte spil samt eventuelle `UserData`, `UserData2`-mapper i spilmappen. Hver sikkerhedskopi har sin egen mappe. I `save-backup.json` finder du filernes oprindelige placeringer og kontrolsummer, hvis du vil gendanne en gemt spilstand manuelt.

Når du vil opdatere, skal du lukke spillet og vejrprogrammet, pakke den nye ZIP-fil ud i en separat mappe og vælge den samme spilmappe i det nye installationsprogram. Vil du fjerne modden, skal du lukke begge programmer og vælge **Indstillinger → Afinstaller** i den kopi af `Setup.exe`, du har gemt. De oprindelige filer gendannes, og du beholder dine gemte spil og sikkerhedskopier. Hvis du senere vil bruge moddens genstande igen, så gem en kopi af grunden, inden du spiller uden modden.

Hvis installationen blev afbrudt, skal du vælge **Indstillinger → Fortryd ændringer**. Hvis gendannelsen melder om en ændret fil, skal du beholde fejlmeddelelsen og sikkerhedskopierne. Hvis Windows nægter skriveadgang, skal du køre `Setup.exe` som administrator fra den samme Windows-konto.

## Betatest og fejlrapporter

Installationen er testet med begge understøttede spilversioner. Vi modtager gerne erfaringer fra andre pc’er, mindre kraftige computere og længere spilforløb på de 17 sprog. Hvis vejreffekterne hakker med NVIDIA-overlayet slået til, så prøv at slå det fra.

Meld fejl under [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) på GitHub. Angiv spilversion, modversion, sprog og de trin, der udløser fejlen. Ved grafikfejl kan du vedlægge et skærmbillede og beskrive vejr, zoom, kameravinkel, etage og vægvisning. Ved installationsfejl skal du medtage hele fejlmeddelelsen. Gennemgå logfiler for personlige filstier, før du deler dem.
