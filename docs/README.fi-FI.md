# The Sims Neljä vuodenaikaa

**Ensimmäinen julkinen beetaversio · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · **Suomi** · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

Neljä vuodenaikaa The Sims Legacy Collectioniin. Ukkoskuuro voi ajaa simit sisälle, ja tuore lumi peittää pihan. Kun lataat tallennetun pelin, myös tontin sää ja kalenteri palautuvat. Tämä on fanien tekemä epävirallinen modi.

![Sumua asuintontilla The Sims Legacy Collectionissa](../media/weather.png)

[Syksyn lehtiä](../media/autumn.png) · [Lumipeitteinen puutarha](../media/winter.png) · [Koko galleria (ZIP, 8 kuvaa)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## Sää tontillasi

- Sade, ukkonen, rakeet, lumi, lumimyrskyt ja sumu vaihtelevat vuodenaikojen mukaan. Valinnaisella sääasemalla voit valita sään itse, myös taikasateen tai taikasumun.
- Syksyllä lehdet saavat ruskan värit. Talvella lumi peittää teitä, kasveja ja ulkoesineitä, myös hautakiviä. Lapset voivat loiskutella lätäköissä, ja kun lunta on kertynyt tarpeeksi, simit voivat rakentaa lumiukon.
- Simit, koirat ja kissat voivat kastua läpimäriksi ja hakeutua suojaan. Sade voi sammuttaa taivasalla syttyneen tulipalon. Voit säätää sään vaikutuksia pelaamiseen yksi kerrallaan. Pelin latautuessa kuulet modia varten sävelletyn kappaleen *Pocztówka z doliny*.

## Lataus ja asennus

Tarvitset 64-bittisen Windowsin, asennetun The Sims Legacy Collectionin täysversion **1.10.0** tai **1.10.7** sekä [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0) -ajoympäristön. Varaa useita gigatavuja vapaata levytilaa sekä tilaa tallennustesi varmuuskopiolle.

1. Avaa GitHub-projektin [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1), valitse julkaisu **1.0.0-beta.1** ja lataa `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` kohdasta **Assets**.
2. Tallenna peli ja sulje sekä peli että sääohjelma. Pura koko ZIP-paketti uuteen kansioon. Jätä `data` samaan kansioon kuin `Setup.exe`.
3. Käynnistä `Setup.exe` ja valitse pelikansio, jossa `sims.exe` sijaitsee. Valitse ensin **Tarkista yhteensopivuus** ja sitten **Asenna**. Asennusohjelma tarkistaa tiedostot, tekee varmuuskopiot ja päivittää oman peliasennuksesi tiedostot. Asennus keskeytyy, jos jokin vaadituista tiedostoista ei ole yhteensopiva.
4. Odota, että asennus valmistuu. Käynnistä peli jatkossa työpöydän **The Sims Cztery Pory Roku** -pikakuvakkeesta tai asennetun sääohjelman kansiossa olevalla `Launch-weather.cmd`-tiedostolla. Näin myös sääohjelma ja tallennusten sään palauttava osa käynnistyvät.

Anna asennusohjelman päivittää pelitiedostot. Se tarkistaa tiedostojen tarkistussummat ennen muutoksia ja niiden jälkeen. `sims.exe` säilyy ennallaan. Valinnaiset esineet päivitetään vain, jos niiden tuettu versio on jo asennettu.

## Pelaaminen

Kun lataat tontin, sää vaihtuu automaattisesti. Pikanäppäimellä `Ctrl+Alt+R` voit säätää sateita, ääntä, kalenteria ja sään vaikutuksia pelaamiseen. Esineiden valikot seuraavat pelin kieltä. Myös sääpaneeli käyttää oletuksena pelin kieltä. Jos valitset paneelille toisen kielen, muutos tulee voimaan seuraavalla käynnistyskerralla.

## Varmuuskopiot, päivitykset ja poistaminen

Asennusohjelma varmuuskopioi käsiteltävät tiedostot, pelitallennukset ja säätiedot. Säilytä `backups` ja `install-state.json` asennetun ohjelman omassa kansiossa kohteessa `%LOCALAPPDATA%\TS1CzteryPoryRoku`. Tonttien säätietoja on myös kansiossa `%LOCALAPPDATA%\TS1RainOverlay`. Voit palauttaa tallennukset varmuuskopioista itse, kun peli on suljettu. Pidä peli ja sääohjelma alkuperäisissä asennuskansioissaan.

Varmuuskopioon sisältyvät Windowsin tallennettujen pelien kansiossa sijaitseva `Electronic Arts\The Sims 25` sekä pelikansiossa mahdollisesti olevat `UserData`, `UserData2`-kansiot. Jokaisella varmuuskopiolla on oma kansio. Tiedostossa `save-backup.json` näkyvät alkuperäiset polut ja tarkistussummat, joiden avulla löydät palautettavat tiedostot.

Kun päivität modin, sulje peli ja sääohjelma, pura uusi ZIP-paketti erilliseen kansioon ja valitse uudessa asennusohjelmassa sama pelikansio. Kun haluat poistaa modin, sulje molemmat ohjelmat, käynnistä säilyttämäsi `Setup.exe` ja valitse **Asetukset → Poista asennus**. Alkuperäiset tiedostot palautetaan, ja tallennukset ja varmuuskopiot säilyvät. Jos aiot käyttää modin esineitä myöhemmin uudelleen, säilytä tontista kopio ajalta ennen pelaamista ilman modia.

Jos asennus keskeytyi, valitse **Asetukset → Kumoa muutokset**. Jos palautus ilmoittaa muuttuneesta tiedostosta, säilytä ilmoitus ja varmuuskopiot. Jos Windows estää tiedostojen kirjoittamisen, suorita `Setup.exe` järjestelmänvalvojana samalla Windows-käyttäjätilillä.

## Beetatestaus ja virheraportit

Asennustestit kattavat molemmat tuetut peliversiot. Palaute muunlaisilta tietokoneilta, heikommalta laitteistolta ja pidemmistä pelikerroista kaikilla 17 kielellä on tervetullutta. Jos säätehosteet nykivät NVIDIA-peittokuvan ollessa käytössä, kokeile peliä myös peittokuva poistettuna käytöstä.

Ilmoita virheestä GitHubin [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues)-osiossa. Kerro pelin ja modin versiot, kieli sekä vaiheet, joilla ongelman voi toistaa. Jos ongelma näkyy ruudulla, liitä kuvakaappaus ja kerro sää, zoomaus, kameran kulma, kerros ja seinien näyttötapa. Liitä asennusongelmista koko virheilmoitus. Tarkista lokit henkilökohtaisten tiedostopolkujen varalta ennen jakamista.
