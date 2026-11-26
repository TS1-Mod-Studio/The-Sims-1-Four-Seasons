# The Sims Cztery Pory Roku

**Pierwsza publiczna beta · 1.0.0-beta.1**

[English](../README.md) · **Polski** · [Dansk](README.da-DK.md) · [Deutsch](README.de-DE.md) · [Español](README.es-ES.md) · [Suomi](README.fi-FI.md) · [Français](README.fr-FR.md) · [Italiano](README.it-IT.md) · [日本語](README.ja-JP.md) · [한국어](README.ko-KR.md) · [Norsk bokmål](README.nb-NO.md) · [Nederlands](README.nl-NL.md) · [Português (Brasil)](README.pt-BR.md) · [Svenska](README.sv-SE.md) · [ไทย](README.th-TH.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md)

Cztery pory roku w The Sims Legacy Collection. Burza może zagnać Simów pod dach, świeży śnieg osiada w ogrodzie, a po wczytaniu zapisu wracają pogoda i kalendarz danej parceli. To nieoficjalny mod fanowski.

![Mgła na parceli mieszkalnej w The Sims Legacy Collection](../media/weather.png)

[Jesienne liście](../media/autumn.png) · [Ogród pod śniegiem](../media/winter.png) · [Pełna galeria (ZIP, 8 obrazów)](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/download/v1.0.0-beta.1/The-Sims-1-Four-Seasons-Screenshots.zip)

## Co zmienia się na parceli

- Deszcz, burze, grad, śnieg, zamiecie i mgła pojawiają się zgodnie z kalendarzem pór roku. Opcjonalna stacja pogodowa pozwala wybrać pogodę ręcznie, w tym magiczny deszcz i magiczną mgłę.
- Jesienią zmienia się kolor liści. Zimą śnieg osiada na drogach, roślinach i obiektach na dworze, również na nagrobkach. Dzieci mogą chlapać się w kałużach, a przy dostatecznej pokrywie śnieżnej Simowie mogą ulepić bałwana.
- Simowie, psy i koty mokną i mogą szukać schronienia. Deszcz potrafi ugasić pożar pod gołym niebem. Poszczególne mechaniki można włączać w panelu pogody. Przy ładowaniu gry usłyszysz nowy utwór *Pocztówka z doliny*.

## Pobieranie i instalacja

Potrzebujesz pełnej gry The Sims Legacy Collection w wersji **1.10.0** lub **1.10.7**, zainstalowanej w 64-bitowym systemie Windows, oraz środowiska [Microsoft .NET Desktop Runtime 10 (x64)](https://dotnet.microsoft.com/download/dotnet/10.0). Przygotuj kilka GB wolnego miejsca i uwzględnij rozmiar kopii swoich zapisów.

1. Na stronie projektu w GitHubie otwórz [Releases](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/releases/tag/v1.0.0-beta.1), wybierz wydanie **1.0.0-beta.1** i pobierz `TheSimsCzteryPoryRoku-1.0.0-beta.1.zip` z sekcji **Assets**.
2. Zapisz rozgrywkę, a następnie zamknij grę i program pogody. Rozpakuj cały ZIP do nowego folderu. Folder `data` powinien leżeć obok `Setup.exe`.
3. Uruchom `Setup.exe` i wskaż folder gry zawierający `sims.exe`. Wybierz **Sprawdź zgodność**, a po sprawdzeniu plików **Zainstaluj**. Instalator weryfikuje pliki, tworzy kopie i nanosi poprawki na zasoby Twojej gry. Konflikt wymaganego pliku zatrzyma instalację.
4. Poczekaj na zakończenie. Odtąd uruchamiaj grę przez skrót **The Sims Cztery Pory Roku** na pulpicie lub `Uruchom pogode.cmd` w folderze zainstalowanego programu. Razem z grą wystartują pogoda i moduł odtwarzający ją po wczytaniu zapisu.

Pozwól instalatorowi nanieść poprawki na pliki gry. Sprawdza on sumy kontrolne przed zmianą i po niej. Plik `sims.exe` pozostaje bez zmian. Poprawki do dodatkowych obiektów są stosowane tylko wtedy, gdy masz zainstalowaną ich obsługiwaną wersję.

## W grze

Po wczytaniu parceli pogoda działa automatycznie. Naciśnij `Ctrl+Alt+R`, aby zmienić ustawienia opadów, dźwięku, kalendarza i rozgrywki. Menu obiektów korzystają z języka gry. Panel pogody domyślnie też go używa. Jeśli wybierzesz inny język panelu, zmiana zacznie działać przy następnym uruchomieniu.

## Kopie zapasowe, aktualizacje i odinstalowanie

Instalator kopiuje zmieniane pliki, zapisy gry i dane pogody. Zachowaj `backups` oraz `install-state.json` w folderze zainstalowanego programu w `%LOCALAPPDATA%\TS1CzteryPoryRoku`. Dane pogodowe parcel są też w `%LOCALAPPDATA%\TS1RainOverlay`. Kopie zapisów służą do ręcznego odzyskania rozgrywki przy zamkniętej grze. Pozostaw foldery gry i programu w miejscu instalacji.

Kopia obejmuje folder `Electronic Arts\The Sims 25` w systemowym folderze zapisanych gier Windows oraz ewentualne foldery `UserData`, `UserData2` w katalogu gry. Każda kopia ma osobny folder. W pliku `save-backup.json` znajdziesz ścieżki źródłowe i sumy kontrolne potrzebne do rozpoznania plików przy ręcznym odzyskiwaniu zapisów.

Aby zaktualizować mod, zamknij grę i program pogody, rozpakuj nowy ZIP do osobnego folderu i w jego instalatorze wskaż tę samą grę. Aby usunąć mod, zamknij oba programy i wybierz **Opcje → Odinstaluj** w zachowanej kopii `Setup.exe`. Instalator przywróci pierwotne pliki i zachowa zapisy oraz kopie zapasowe. Jeśli chcesz później wrócić do obiektów moda, zachowaj kopię parceli sprzed gry bez moda.

Po przerwanej instalacji wybierz **Opcje → Cofnij zmiany**. Jeśli odzyskiwanie zgłosi zmianę pliku, zachowaj komunikat i kopie zapasowe. Jeśli Windows odmówi zapisu, uruchom `Setup.exe` jako administrator z tego samego konta.

## Testy i zgłaszanie błędów

Testy instalatora obejmują obie obsługiwane wersje gry. Nadal przydadzą się testy na innych komputerach, na słabszym sprzęcie i podczas dłuższej gry w każdym z 17 języków. Jeśli animacja pogody zwalnia przy aktywnej nakładce NVIDIA, sprawdź działanie po jej wyłączeniu.

Zgłoś problem w zakładce [Issues](https://github.com/TS1-Mod-Studio/The-Sims-1-Four-Seasons/issues) na GitHubie. Podaj wersje gry i moda, język oraz kroki potrzebne do powtórzenia błędu. W przypadku usterki grafiki dołącz zrzut ekranu i opisz pogodę, zbliżenie, obrót kamery, piętro oraz widok ścian. Przy błędzie instalacji podaj pełny komunikat. Przed udostępnieniem dzienników sprawdź, czy zawierają prywatne ścieżki plików.
