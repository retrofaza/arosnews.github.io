---
layout: post
title: AROS x86 - październik 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 1024
---

Dawno nie działo się tak wiele jednocześnie. W tym miesiącu dostaliśmy zbiorczą aktualizację do wersji bazowej systemu ABIv0, mamy nową wersję przeglądarki internetowej, a na dodatek zaczęły się pojawiać wersje x64 ważnego oprogramowania. Parafrazując slogan Commodore: "Are you keeping up with the AROS?". Mam nadzieję, że tak!

Firma AirSoft Softwair wydała nową wersję wtyczki do programu Hollywood, która umożliwia odtwarzanie plików dźwiękowych w formacie SID. W wersji 2.0 dokonano całkowitej zmiany głównego silnika obsługującego ten format, zastępując TinySID nowym cRSID. Dzięki temu emulacja jest bardziej precyzyjna i wspiera Real SID. Wersję dla AROS x86 można pobrać [stąd](https://www.hollywood-mal.com/download/SID_Amiga.lha).

Za sprawą Daremonowi jest już 64-bitowy [Python](https://archives.aros-exec.org/?function=showfile&file=development/language/python-2.5.2.x86_64-aros-v11.zip) i [Perl](https://archives.aros-exec.org/?function=showfile&file=development/language/perl-5.7.2.x86_64-aros-v11.zip), dzięki czemu jest już cały natywny toolchain dla 64-bit. Ponadto Daremon skompilował bibliotekę audio [libMAD](https://archives.aros-exec.org/?function=showfile&file=development/library/libmad-0.15.1b.x86_64-aros-v11.zip), a gracze ucieszą się z 64-bitowych wersji [Doom 3](https://archives.aros-exec.org/?function=showfile&file=game/fps/adoom3-1.5.3.x86_64-aros-v11.zip), silników [GemRB](https://archives.aros-exec.org/?function=showfile&file=game/roleplaying/gemrb-0.8.8-0.x86_64-aros-v11.zip), [ResidualVM](https://archives.aros-exec.org/?function=showfile&file=emulation/misc/residualvm-0.3.1-1.x86_64-aros-v11.zip) i [ScummVM](https://archives.aros-exec.org/?function=showfile&file=emulation/misc/scummvm-1.9.0-1.x86_64-aros-v11.zip). ALB42 swój czytnik ePub [Legadaon](https://home.alb42.de/files/Legadon03_AROS64.lha) także udostepnił w wersji dla ABIv11. Czy przyszły rok będzie rokiem totalnej przesiadki na 64-bity?

Wracając do 32-bitowej teraźniejszości:  

Serk118 zaktualizował swoje porty [GLFW 3.4](https://archives.aros-exec.org/?function=showfile&file=development/library/lib_glfw_3_4.i386-aros.zip) oraz [Raylib 5.0](https://archives.aros-exec.org/?function=showfile&file=development/library/lib_raylib5.i386-aros.zip).

![Ralib5](/assets/img/1024/raylib.png)
*Raylib 5*

Raylib to biblioteka programistyczna pozwalająca cieszyć się programowaniem gier wideo; bez wyszukanego interfejsu, bez wizualnych pomocników, bez narzędzi gui lub edytorów... po prostu kodowanie w czysto spartański sposób. Z tym updatem dostajemy także:

> ## [rFXGen](https://archives.aros-exec.org/?function=showfile&file=audio/rfxgen-aros.zip)
> (autor: raylibtech.itch.io/rfxgen, port by Serk118)

Prosty i łatwy w użyciu generator efektów dźwiękowych.

Funkcje:  
- Predefiniowane **ustawienia dźwiękowe** (Coin, Shoot, Explosion, PowerUp...)
- Obsługa wielu typów fal (kwadratowa, piłokształtna, sinusoidalna, szum)
- Do **5 slotów dźwiękowych** do przechowywania wygenerowanego dźwięku (zapis tymczasowy)
- Wczytywanie plików `.rfx` z parametrami generowania dźwięku
- Zapisywanie plików `.rfx` z parametrami generowania dźwięku (**104 bajty**)
- Eksport danych wave jako `.wav`, `.raw` lub `.h` (tablica bajtów)
- Konfigurowalna częstotliwość próbkowania, bity na próbkę i kanały podczas eksportu
- Wiele stylów GUI z obsługą niestandardowych (`.rgs`)
- Obsługa konwersji wsadowej `.rfx` do `.wav` z wiersza poleceń
- Odtwarzacz audio z wiersza poleceń dla plików `.wav`, `.ogg`, `.mp3` i `.flac`
- Całkowicie przenośny (jednoplikowy, bez zależności)**.
- **Darmowy i open-source**

> ## [RayGui](https://archives.aros-exec.org/?function=showfile&file=development/misc/raygui.i386-aros.zip)
> (autor: github.com/raysan5/raygui, port by Serk118)

Raygui został zaprojektowany jako moduł pomocniczy dla Raylib do tworzenia prostych interfejsów GUI przy użyciu stylu graficznego raylib (proste kolory, zwykłe prostokątne kształty, szerokie granice...), ale może być dostosowany do innych silników/frameworków.

![RayGui](/assets/img/1024/raygui.png)
*RayGui*

> ## [kMusicPlayer](https://archives.aros-exec.org/?function=showfile&file=utility/archive/cabextract1.11.i386-aros.zip)
> (autor: github.com/notkatsuu/kMusicPlayer, port by Serk118)

kMusicPlayer to wizualny odtwarzacz muzyki zbudowany z C i Raylib. Zapewnia prosty interfejs wizualny do odtwarzania ulubionych utworów muzycznych.  

Główne cechy:
- Odtwarzanie muzyki: Łatwe odtwarzanie ulubionych utworów. Obsługuje formaty .mp3 i .wav.
- Wizualizacja kształtu fali: Wizualizacja muzyki dzięki renderowaniu kształtu fali.
- Wątkowe ładowanie muzyki: Szybkie ładowanie muzyki dzięki ładowaniu wątkowemu.
- Proste sterowanie: Kontroluj odtwarzanie za pomocą prostych skrótów klawiaturowych w RayGUI.

> ## [Koala Seasons](https://archives.aros-exec.org/?function=showfile&file=game/strategy/koala_seasons.i386-aros.zip)
> (autor: www.raylib.com, port by Serk118)

Walcz z żywiołami! Walcz z wrogami! Ocal świat! Jak długo uda ci się przetrwać? Ta gra została pierwotnie stworzona przez emegeme jako benchmark dla Raylib na urządzeniach z Androidem.  
  
Pozostałe nowości w AROS Archives:  

> ## [BeeBase](https://archives.aros-exec.org/?function=showfile&file=office/database/beebase-1.1.lha) (v. 1.1)
> (autor: Steffen Gutman)

BeeBase to relacyjny, programowalny system baz danych z graficznym interfejsem użytkownika dla wszystkich systemów amigowych, a także dla Windows, Mac i Linux. Siła BeeBase leży w graficznym interfejsie użytkownika i możliwościach programowania. Umożliwia on przetwarzanie danych na różne sposoby, np. automatyczne obliczenia po wprowadzeniu danych przez użytkownika, generowanie raportów, importowanie i eksportowanie danych itp. 

![BeeBase](/assets/img/1024/beebase.png)
*BeeBase*

> ## [Amifish](https://archives.aros-exec.org/?function=showfile&file=game/board/amifish.i386-aros.lha) (v. 2.0)
> (autor:	Domenico Lattanzi)

Amifish to program szachowy stworzony do gry w szachy na systemach amigowych, wykorzystujący moc jednego z najpotężniejszych silników szachowych na świecie: Stockfish, opracowanego przez Torda Romstada, Marco Costalbę, Joonę Kiiski i Gary'ego Linscotta. Silnik szachowy to program konsolowy, który gra w szachy, odbierając ciągi znaków jako polecenia i generując ciągi znaków na wyjściu jako wynik obliczeń. Stockfish i wiele innych silników jest kompatybilnych ze standardem o nazwie UCI (Universal Chess Interface). Nazwa Amifish powstała z połączenia słów Amiga i Stockfish (choć projekt jest otwarty dla wszystkich silników zgodnych ze standardem UCI), jest lekkim programem dla amatorów, stworzonym do zabawy w szachy, z zaimplementowanymi tylko najważniejszymi opcjami.

Do gry przeciwko komputerowi potrzebny jest silnik szachowy Stockfish, który również można pobrać z AROS Archives.

![Amifish](/assets/img/1024/amifish.png)
*Amifish*

> ## [GemRB](https://archives.aros-exec.org/?function=showfile&file=game/roleplaying/gemrb-0.8.8-0.i386-aros.zip) (v. 0.8.8-0)
> (autor: The GemRB Project)

GemRB to przenośna, open-source'owa implementacja 8 wersji silnika Infinity Engine firmy Bioware. Uruchamia gry **Baldur's Gate**, **Icewind Dale** i **Planescape: Torment** oraz ich rozszerzenia i mody. Silnik wymaga plików z danymi z oryginalnych gier. Port dla AROSa przygotował Daremon.

> ## [CabExtract](https://archives.aros-exec.org/?function=showfile&file=utility/archive/cabextract1.11.i386-aros.zip) (v. 1.11)
> (autor: Stuart Caie, port by Farox)

Program do rozpakowywania plików Microsoft Cabinet. Pliki Cabinet (`.CAB`) są formą archiwum, którego Microsoft używa do dystrybucji swojego oprogramowania i rzeczy takich jak Windows Font Packs. Program cabextract rozpakowuje te pliki.

> ## [Unshield](https://archives.aros-exec.org/?function=showfile&file=utility/archive/unshield.i386-aros.zip) (v. 1.5.1)
> (autor:	David Eriksson, port by Farox)

Narzędzie do wyodrębniania plików `.CAB` z pliku `.exe` InstallShield.

> ## [SetScreenMode](https://archives.aros-exec.org/?function=showfile&file=utility/shell/setscreenmode.i386-aros.zip) (v. 1.0)
> (autor:	Nigel Tromans)

Set_Screen_Mode to mała aplikacja Hollywood do automatycznego ustawiania tryb ekranu podczas uruchamiania z wcześniej ustawionej listy.  

Uwaga: Set_Screen_Mode jest przydatny tylko wtedy, gdy instalacja AROS jest wykorzystuje natywną grafikę.  

Została stworzona, aby umożliwić maszynom, które są przenoszone między różnymi wyświetlaczami (takimi jak laptopy z wewnętrznym ekranem i zewnętrznie podłączonymi monitorami) automatycznie uruchamiać się w preferowanym trybie ekranu dla każdego z tych wyświetlaczy, a także pomóc w wyświetlaniu ekranu na ekranach, które są trudne do w użyciu (na przykład takich, które nie są w stanie wyświetlić domyślnego trybu 640x480).  

Set_Screen_Mode odczyta dostępne tryby ekranu dostarczone przez przez wyświetlacz i porówna je z trybami wybranymi przez użytkownika na uporządkowanej liście. Możliwe jest również wymuszenie trybu, nawet jeśli nie ma go na liście lub całkowicie zignorować tryby ustawione dla Set_Screen_Mode.  


