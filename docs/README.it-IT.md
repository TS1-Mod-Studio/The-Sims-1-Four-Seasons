# The Sims Quattro Stagioni

**Prima beta pubblica · 1.0.0-beta.1**

[English](../README.md) · [Polski](README.pl-PL.md) · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · **Italiano** · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

Le quattro stagioni arrivano in The Sims Legacy Collection. Un temporale può far correre i tuoi Sim al riparo e la neve fresca si posa in giardino. Quando carichi una partita ritrovi il meteo e il calendario del lotto. Questa è una mod non ufficiale creata dagli appassionati.

![Nebbia su un lotto residenziale in The Sims Legacy Collection](../media/weather.png)

[Foglie d’autunno](../media/autumn.png) · [Un giardino innevato](../media/winter.png) · [Galleria completa (ZIP, 8 immagini)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## Il meteo sul tuo lotto

- Pioggia, temporali, grandine, neve, bufere e nebbia seguono le stagioni. Con la stazione meteorologica facoltativa puoi anche scegliere il tempo, inclusi pioggia e nebbia magiche.
- In autunno le foglie cambiano colore. In inverno la neve si posa sulle strade, sulla vegetazione e sugli oggetti all’aperto, comprese le lapidi. I bambini possono sguazzare nelle pozzanghere e i Sim possono fare un pupazzo di neve quando lo strato è abbastanza spesso.
- I Sim, i cani e i gatti possono inzupparsi e cercare riparo. La pioggia può spegnere gli incendi all’aperto. Puoi regolare separatamente gli effetti del meteo sul gioco. Durante il caricamento si sente un brano originale, *Pocztówka z doliny*.

## Download e installazione

Occorrono la versione completa di The Sims Legacy Collection **1.10.0** o **1.10.7** già installata su Windows a 64 bit e [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0). Servono alcuni GB di spazio libero oltre allo spazio per una copia dei salvataggi.

1. Apri [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1) su GitHub, scegli la versione **1.0.0-beta.1** e scarica `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` da **Assets**.
2. Salva la partita e chiudi il gioco e l’applicazione meteo. Estrai tutto lo ZIP in una nuova cartella e lascia la cartella `data` accanto a `Setup.exe`.
3. Avvia `Setup.exe` e seleziona la cartella del gioco che contiene `sims.exe`. Scegli **Verifica compatibilità** e poi **Installa**. Il programma verifica i file, ne crea copie di sicurezza e applica le modifiche ai file del tuo gioco. Un conflitto in un file necessario interrompe l’installazione.
4. Attendi il messaggio di completamento. Per giocare, usa il collegamento **The Sims Cztery Pory Roku** sul desktop oppure `Launch-weather.cmd` nella cartella dell’applicazione installata. In questo modo vengono avviati insieme il gioco, il meteo e il modulo che ripristina il meteo dei salvataggi.

Lascia che sia il programma di installazione ad applicare le modifiche. Verifica le somme di controllo dei file prima e dopo ogni modifica e lascia intatto `sims.exe`. Gli oggetti facoltativi vengono aggiornati solo se ne è già installata una versione supportata.

## Durante il gioco

Carica un lotto per attivare il meteo automatico. Premi `Ctrl+Alt+R` per regolare precipitazioni, audio, calendario ed effetti sul gioco. I menu degli oggetti usano la lingua del gioco. Il pannello meteo adotta la stessa lingua per impostazione predefinita. Se scegli una lingua diversa per il pannello, la modifica avrà effetto all’avvio successivo.

## Backup, aggiornamento e disinstallazione

Il programma d’installazione crea copie di sicurezza dei file interessati, dei salvataggi e dei dati meteo. Conserva `backups` e `install-state.json` nella cartella dell’applicazione sotto `%LOCALAPPDATA%\TS1CzteryPoryRoku`. I dati meteo dei lotti vengono memorizzati anche in `%LOCALAPPDATA%\TS1RainOverlay`. Puoi ripristinare manualmente una partita dalla sua copia a gioco chiuso. Lascia le cartelle del gioco e dell’applicazione nelle posizioni originali.

La copia comprende `Electronic Arts\The Sims 25` nella cartella dei giochi salvati di Windows e le eventuali cartelle `UserData`, `UserData2` nella directory del gioco. Ogni copia ha una cartella dedicata. Il file `save-backup.json` riporta i percorsi originali e le somme di controllo per aiutarti a individuare i file da ripristinare.

Per aggiornare la mod, chiudi il gioco e il programma meteo, estrai il nuovo ZIP in una cartella separata e indica al nuovo programma d’installazione la stessa cartella del gioco. Per rimuovere la mod, chiudi entrambi i programmi e scegli **Opzioni → Disinstalla** nella copia di `Setup.exe` che hai conservato. Verranno ripristinati i file originali, mantenendo salvataggi e backup. Se pensi di riutilizzare gli oggetti della mod, conserva una copia del lotto prima di giocare senza la mod.

Se l’installazione si interrompe, scegli **Opzioni → Annulla modifiche**. Se il ripristino segnala che un file è stato modificato, conserva il messaggio e le copie di sicurezza. Se Windows nega l’accesso in scrittura, esegui `Setup.exe` come amministratore con lo stesso account Windows.

## Test della beta e segnalazioni

I test d’installazione coprono entrambe le versioni supportate del gioco. Sono utili prove su altri PC, su hardware meno potente e con partite lunghe in tutte le 17 lingue. Se gli effetti meteo rallentano con l’overlay NVIDIA attivo, prova a disattivarlo.

Segnala i problemi nella sezione [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) su GitHub. Indica le versioni del gioco e della mod, la lingua e i passaggi per riprodurre il problema. Per un difetto grafico aggiungi uno screenshot e indica il meteo, lo zoom, l’angolo della visuale, il piano e la modalità dei muri. Per un errore d’installazione riporta il messaggio completo. Prima di condividere i registri, controlla se contengono percorsi di file personali.
