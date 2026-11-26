# The Sims Fire årstider

**Første offentlige betaversjon · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · **Norsk bokmål** · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

Fire årstider i The Sims Legacy Collection. Et tordenvær kan få simmene dine til å løpe inn, og nysnø legger seg i hagen. Når du laster inn et lagret spill, får tomten tilbake været og kalenderen sin. Dette er en uoffisiell mod laget av fans.

![Tåke på en boligtomt i The Sims Legacy Collection](../media/weather.png)

[Høstløv](../media/autumn.png) · [En snødekt hage](../media/winter.png) · [Hele galleriet (ZIP, 8 bilder)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## Været på tomten

- Regn, tordenvær, hagl, snø, snøstorm og tåke følger årstidene. Med den valgfrie værstasjonen kan du også velge været selv, blant annet magisk regn og magisk tåke.
- Om høsten skifter løvet farge. Om vinteren legger snøen seg på veier, planter og gjenstander utendørs, også gravsteiner. Barn kan plaske i sølepytter, og simmene kan lage en snømann når det har kommet nok snø.
- Simmer, hunder og katter kan bli gjennomvåte og søke ly. Regn kan slukke branner under åpen himmel. Du kan justere de enkelte virkningene været har på spillet. Under innlastingen hører du den nye melodien *Pocztówka z doliny*.

## Nedlasting og installasjon

Du trenger fullversjonen av The Sims Legacy Collection **1.10.0** eller **1.10.7** installert på 64-biters Windows, samt [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0). Sett av flere GB ledig plass i tillegg til plass til en kopi av de lagrede spillene dine.

1. Åpne [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1) på prosjektets GitHub-side, velg **1.0.0-beta.1** og last ned `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` under **Assets**.
2. Lagre spillet og lukk både spillet og værprogrammet. Pakk ut hele ZIP-filen i en ny mappe. La mappen `data` ligge ved siden av `Setup.exe`.
3. Kjør `Setup.exe` og velg spillmappen som inneholder `sims.exe`. Velg **Sjekk kompatibilitet** og deretter **Installer**. Installasjonsprogrammet kontrollerer og sikkerhetskopierer filene før det gjør endringer i dine egne spillfiler. En konflikt i en nødvendig fil stopper installasjonen.
4. Vent til installasjonen er ferdig. Start deretter spillet med skrivebordssnarveien **The Sims Cztery Pory Roku** eller med `Launch-weather.cmd` i mappen til det installerte programmet. Da starter spillet sammen med været og modulen som henter tilbake været fra lagrede spill.

La installasjonsprogrammet endre spillfilene. Det kontrollerer filenes sjekksummer før og etter hver endring, og `sims.exe` forblir uendret. Valgfrie gjenstander oppdateres bare hvis du allerede har installert en versjon som støttes.

## I spillet

Last inn en tomt for å se det automatiske været. Med `Ctrl+Alt+R` åpner du innstillingene for nedbør, lyd, kalender og virkninger på spillet. Menyene for gjenstander bruker spillets språk. Værpanelet bruker også dette språket som standard. Hvis du velger et annet språk i panelet, gjelder det fra neste gang du starter spillet.

## Sikkerhetskopier, oppdatering og avinstallering

Installasjonsprogrammet tar sikkerhetskopier av berørte filer, lagrede spill og værdata. Behold `backups` og `install-state.json` i programmappen under `%LOCALAPPDATA%\TS1CzteryPoryRoku`. Værdata for tomtene lagres også under `%LOCALAPPDATA%\TS1RainOverlay`. Du kan gjenopprette lagrede spill manuelt fra kopiene mens spillet er lukket. La spillmappen og programmappen ligge der de ble installert.

Sikkerhetskopien omfatter `Electronic Arts\The Sims 25` i Windows-mappen for lagrede spill og eventuelle `UserData`, `UserData2`-mapper i spillmappen. Hver sikkerhetskopi får en egen mappe. I `save-backup.json` finner du opprinnelige filbaner og sjekksummer som kan brukes til å identifisere filene du vil gjenopprette manuelt.

For å oppdatere lukker du spillet og værprogrammet, pakker ut den nye ZIP-filen i en egen mappe og velger den samme spillmappen i det nye installasjonsprogrammet. For å fjerne modden lukker du begge programmene og velger **Alternativer → Avinstaller** i kopien av `Setup.exe` du har tatt vare på. Originalfilene gjenopprettes, og du beholder lagrede spill og sikkerhetskopier. Hvis du vil bruke gjenstandene fra modden igjen senere, ta vare på en kopi av tomten fra før du spilte uten modden.

Hvis installasjonen ble avbrutt, velger du **Alternativer → Tilbakestill endringer**. Hvis gjenopprettingen melder at en fil er endret, tar du vare på meldingen og sikkerhetskopiene. Hvis Windows nekter skrivetilgang, kjører du `Setup.exe` som administrator fra den samme Windows-kontoen.

## Betatesting og feilrapporter

Installasjonen er testet på begge spillversjonene som støttes. Vi tar gjerne imot erfaringer fra andre PC-er, svakere maskinvare og lengre spilløkter på alle de 17 språkene. Hvis væreffektene hakker med NVIDIA-overlegget aktivert, kan du prøve å slå det av.

Meld feil under [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) på GitHub. Oppgi spillversjon, modversjon, språk og fremgangsmåten som utløser feilen. Ved grafikkfeil hjelper det med et skjermbilde og opplysninger om vær, zoom, kameravinkel, etasje og veggvisning. Ved installasjonsfeil legger du ved hele feilmeldingen. Se etter personlige filbaner i loggene før du deler dem.
