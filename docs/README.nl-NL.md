# De Sims Vier Jaargetijden

**Eerste openbare bèta · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · **Nederlands** · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

Vier seizoenen voor The Sims Legacy Collection. Tijdens een onweersbui kunnen je Sims naar binnen vluchten en in de winter blijft de sneeuw in de tuin liggen. Laad je een opgeslagen spel, dan gaan het weer en de kalender van de kavel verder waar je gebleven was. Dit is een onofficiële mod van fans.

![Mist op een woonkavel in The Sims Legacy Collection](../media/weather.png)

[Herfstbladeren](../media/autumn.png) · [Een besneeuwde tuin](../media/winter.png) · [Volledige galerij (ZIP, 8 afbeeldingen)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## Wat verandert er op je kavel?

- Afhankelijk van het seizoen krijg je regen, onweer, hagel, sneeuw, sneeuwstormen en mist. Met het optionele weerstation kun je het weer zelf kiezen, ook magische regen en magische mist.
- In de herfst verkleuren de bladeren. In de winter blijft sneeuw liggen op wegen, planten en voorwerpen buiten, waaronder grafstenen. Kinderen kunnen in plassen spetteren en bij voldoende sneeuw kunnen Sims een sneeuwpop maken.
- Sims, honden en katten kunnen doorweekt raken en een schuilplaats zoeken. Regen kan buiten een brand blussen. Je bepaalt zelf welke gevolgen het weer voor het spel heeft. Tijdens het laden hoor je de speciaal voor de mod gemaakte muziek *Pocztówka z doliny*.

## Downloaden en installeren

Je hebt een geïnstalleerde volledige versie van The Sims Legacy Collection **1.10.0** of **1.10.7**, 64-bits Windows en [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0) nodig. Zorg voor enkele GB vrije ruimte en extra ruimte voor een kopie van je opgeslagen spellen.

1. Open [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1) op de GitHub-pagina van het project, kies **1.0.0-beta.1** en download `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` onder **Assets**.
2. Sla je spel op en sluit het spel en het weerprogramma. Pak het hele ZIP-bestand uit in een nieuwe map. Laat de map `data` naast `Setup.exe` staan.
3. Start `Setup.exe` en kies de spelmap waarin `sims.exe` staat. Kies eerst **Compatibiliteit controleren** en daarna **Installeren**. Het installatieprogramma controleert de bestanden, maakt back-ups en past de wijzigingen toe op je eigen spelbestanden. Bij een conflict met een vereist bestand stopt de installatie.
4. Wacht tot de installatie klaar is. Start het spel voortaan met de snelkoppeling **The Sims Cztery Pory Roku** op het bureaublad of met `Launch-weather.cmd` in de installatiemap van het weerprogramma. Zo starten het spel en de onderdelen voor het weer en je opgeslagen spel tegelijk.

Laat het installatieprogramma de spelbestanden aanpassen. Het controleert de controlesommen voor en na het toepassen van elke patch en laat `sims.exe` intact. Optionele voorwerpen worden alleen bijgewerkt als er al een ondersteunde versie van is geïnstalleerd.

## Tijdens het spelen

Laad een kavel om het automatische weer te zien. Met `Ctrl+Alt+R` open je de instellingen voor neerslag, geluid, de kalender en de speleffecten. De menu’s van voorwerpen volgen de taal van het spel. Het weerpaneel gebruikt standaard dezelfde taal. Kies je voor het paneel een andere taal, dan gaat die in wanneer je het spel opnieuw start.

## Back-ups, updates en verwijderen

Het installatieprogramma maakt een back-up van de betrokken bestanden, opgeslagen spellen en weergegevens. Bewaar `backups` en `install-state.json` bij elkaar in de programmamap onder `%LOCALAPPDATA%\TS1CzteryPoryRoku`. Weergegevens per kavel staan ook onder `%LOCALAPPDATA%\TS1RainOverlay`. Je kunt opgeslagen spellen handmatig terugzetten zodra je het spel hebt afgesloten. Laat de spelmap en de programmamap op hun oorspronkelijke plek staan.

De back-up bevat `Electronic Arts\The Sims 25` in de Windows-map voor opgeslagen spellen en de eventuele `UserData`, `UserData2`-mappen in de spelmap. Elke back-up krijgt een eigen map. In `save-backup.json` vind je de oorspronkelijke bestandspaden en controlesommen. Zo kun je bij handmatig herstel de juiste bestanden terugvinden.

Voor een update sluit je het spel en het weerprogramma, pak je het nieuwe ZIP-bestand uit in een aparte map en kies je bij de installatie dezelfde spelmap. Om de mod te verwijderen sluit je beide programma’s en kies je **Opties → Verwijderen** in de bewaarde `Setup.exe`. De oorspronkelijke bestanden worden hersteld. Je opgeslagen spellen en back-ups blijven bewaard. Wil je de voorwerpen uit de mod later weer gebruiken, bewaar dan een kopie van de kavel van vóór het spelen zonder de mod.

Is de installatie onderbroken, kies dan **Opties → Wijzigingen terugdraaien**. Meldt het herstelprogramma dat een bestand is gewijzigd, bewaar dan de melding en de back-ups. Als Windows schrijftoegang weigert, voer je `Setup.exe` vanuit hetzelfde Windows-account als administrator uit.

## Bèta testen en fouten melden

Het installatieprogramma is voor beide ondersteunde spelversies getest. Ervaringen op andere pc’s, op minder krachtige computers en tijdens langere speelsessies in de 17 talen zijn welkom. Hapert het weerbeeld wanneer de NVIDIA-overlay actief is, probeer het dan ook met die overlay uitgeschakeld.

Meld een probleem op GitHub onder [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues). Vermeld de spelversie, modversie, taal en de stappen waarmee je het probleem kunt herhalen. Voeg bij een beeldfout een schermafbeelding toe en vermeld het weer, de zoomstand, camerahoek, verdieping en muurweergave. Geef bij installatiefouten de hele foutmelding door. Controleer logbestanden voor het delen op persoonlijke bestandspaden.
