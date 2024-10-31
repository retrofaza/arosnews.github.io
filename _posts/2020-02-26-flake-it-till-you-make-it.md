---
layout: post
title: AROS x86 - październik 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 1024
---

Dawno nie działo się tak wiele jednocześnie. W tym miesiącu dostaliśmy zbiorczą aktualizację do wersji bazowej systemu ABIv0, mamy nową wersję przeglądarki internetowej, a na dodatek zaczęły się pojawiać wersje x64 ważnego oprogramowania. Parafrazując slogan Commodore: "Are you keeping up with the AROS?". Mam nadzieję, że tak!

Firma AirSoft Softwair wydała nową wersję wtyczki do programu Hollywood, która umożliwia odtwarzanie plików dźwiękowych w formacie SID. W wersji 2.0 dokonano całkowitej zmiany głównego silnika obsługującego ten format, zastępując TinySID nowym cRSID. Dzięki temu emulacja jest bardziej precyzyjna i wspiera Real SID. Wersję dla AROS x86 można pobrać [stąd](https://www.hollywood-mal.com/download/SID_Amiga.lha).

Nowe pozycje w AROS-Archive od zeszłego miesiąca:

> ## [Raylib](https://archives.aros-exec.org/?function=showfile&file=development/library/lib_raylib5.i386-aros.zip) (v. 5.0)
> (autor: www.raylib.com, port by Serk118)

Raylib 5

![Raylib](/assets/img/0924/SkyBallsAros.png)
*Raylib 5*

> ## [GLFW](https://archives.aros-exec.org/?function=showfile&file=development/library/lib_glfw_3_4.i386-aros.zip) (v. 3.4)
> (autor: www.glfw.org, port by Serk118)

GLFW 3.4

![GLFW](/assets/img/0924/SkyBallsAros.png)
*GLFW 3.4*

> ## [rFXGen](https://archives.aros-exec.org/?function=showfile&file=audio/rfxgen-aros.zip)
> (autor: raylibtech.itch.io/rfxgen, port by Serk118)

rFXGen

![rFXGen](/assets/img/0924/SkyBallsAros.png)
*rFXGen*

> ## [RayGui](https://archives.aros-exec.org/?function=showfile&file=development/misc/raygui.i386-aros.zip)
> (autor: github.com/raysan5/raygui, port by Serk118)

RayGui

![RayGui](/assets/img/0924/SkyBallsAros.png)
*RayGui*

> ## [kMusicPlayer](https://archives.aros-exec.org/?function=showfile&file=utility/archive/cabextract1.11.i386-aros.zip)
> (autor: github.com/notkatsuu/kMusicPlayer, port by Serk118)

kMusicPlayer to wizualny odtwarzacz muzyki zbudowany z C i Raylib. Zapewnia prosty interfejs wizualny do odtwarzania ulubionych utworów muzycznych.  
Główne cechy:
- Odtwarzanie muzyki: Łatwe odtwarzanie ulubionych utworów. Obsługuje formaty .mp3 i .wav.
- Wizualizacja kształtu fali: Wizualizacja muzyki dzięki renderowaniu kształtu fali.
- Wątkowe ładowanie muzyki: Szybkie ładowanie muzyki dzięki ładowaniu wątkowemu.
- Proste sterowanie: Kontroluj odtwarzanie za pomocą prostych skrótów klawiaturowych w RayGUI.

![kMusicPlayer](/assets/img/0924/SkyBallsAros.png)
*kMusicPlayer*

> ## [BeeBase](https://archives.aros-exec.org/?function=showfile&file=office/database/beebase-1.1.lha) (v. 1.1)
> (autor: Steffen Gutman)

BeeBase to relacyjny, programowalny system baz danych z graficznym interfejsem użytkownika dla wszystkich systemów amigowych, a także dla Windows, Mac i Linux. Siła BeeBase leży w graficznym interfejsie użytkownika i możliwościach programowania. Umożliwia on przetwarzanie danych na różne sposoby, np. automatyczne obliczenia po wprowadzeniu danych przez użytkownika, generowanie raportów, importowanie i eksportowanie danych itp. 

![BeeBase](/assets/img/0924/SkyBallsAros.png)
*BeeBase*

> ## [Koala Seasons](https://archives.aros-exec.org/?function=showfile&file=game/strategy/koala_seasons.i386-aros.zip)
> (autor: www.raylib.com, port by Serk118)

Fight the elements! Fight your enemies! Save the world! How long will you survive? This game was originally created by emegeme to be used as a benchmark test for Raylib on Android devices.

![Koala Seasons](/assets/img/0924/SkyBallsAros.png)
*Koala Seasons*

> ## [Amifish](https://archives.aros-exec.org/?function=showfile&file=game/board/amifish.i386-aros.lha) (v. 2.0)
> (autor:	Domenico Lattanzi)

Amifish is a chess program made to play chess with the Amiga-like systems, exploiting the power of one of the most powerful chess engines of the world: Stockfish, developed by Tord Romstad, Marco Costalba, Joona Kiiski and Gary Linscott. A chess engine is a console program who play chess, receiving strings as commands and producing strings in output as result of computation. Stockfish and much others engines are compatible with a standard named UCI (Universal Chess Interface). The name Amifish is obtained by joining the words Amiga and Stockfish (although, however, the project is open to all engines compliant with the UCI standard), is a light program for amateurs, is made to have fun with chess, with only the most important options
implemented.  

To play against the computer, you need the Stockfish chess engine, which you can also download from AROS Archives.

![Amifish](/assets/img/0924/organica.jpg)
*Amifish*

> ## [GemRB](https://archives.aros-exec.org/?function=showfile&file=game/roleplaying/gemrb-0.8.8-0.i386-aros.zip) (v. 0.8.8-0)
> (autor: The GemRB Project)

GemRB

![GemRB](/assets/img/0924/blackivancard.jpg)
*GemRB*

> ## [CabExtract](https://archives.aros-exec.org/?function=showfile&file=utility/archive/cabextract1.11.i386-aros.zip) (v. 1.11)
> (autor: Stuart Caie, port by Farox)

CabExtract

![CabExtract](/assets/img/0924/SkyBallsAros.png)
*CabExtract*

> ## [Unshield](https://archives.aros-exec.org/?function=showfile&file=utility/archive/unshield.i386-aros.zip) (v. 1.51)
> (autor:	David Eriksson, port by Farox)

Unshield

![Unshield](/assets/img/0924/MemoryGameAros.png)
*Unshield*

> ## [SetScreenMode](https://archives.aros-exec.org/?function=showfile&file=utility/shell/setscreenmode.i386-aros.zip) (v. 1.0)
> (autor:	Nigel Tromans)

SetScreenMode

![SetScreenMode](/assets/img/0924/organica.jpg)
*SetScreenMode*

> ## [Perl](https://archives.aros-exec.org/?function=showfile&file=development/language/perl-5.7.2.x86_64-aros-v11.zip) (v. 5.7.2)
> (autor: Stanislaw Szymczyk)

Perl

![Perl](/assets/img/0924/baccarat.jpg)
*Perl*

> ## [Python](https://archives.aros-exec.org/?function=showfile&file=development/language/python-2.5.2.x86_64-aros-v11.zip) (v. 2.5.2)
> (autor: Stanislaw Szymczyk)

Python 2.5.2

![Python](/assets/img/0924/baccarat.jpg)
*Python 2.5.2*

> ## [Adoom3](https://archives.aros-exec.org/?function=showfile&file=game/fps/adoom3-1.5.3.x86_64-aros-v11.zip) (v. 1.5.3)
> (autorzy:	Nick 'Kalamatee' Andrews)

Adoom3

![Adoom3](/assets/img/0924/neandertaler.jpg)
*Adoom3*



