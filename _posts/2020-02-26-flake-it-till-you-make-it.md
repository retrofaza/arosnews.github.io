---
layout: post
title: AROS x86 - sierpień 2025
subtitle: podsumowanie miesiąca
lang: pl
ref: 0825
---

**Deadwood** wypuścił aktualizację [**U1.B**](https://axrt.org/download/aros/v11/AROS-20250418-1-U1.B-any-x86_64-update.zip) dla systemu bazowego *20250418-1*, a także [aktualizację SDK](https://axrt.org/download/aros/v11/SDK-20250418-1-U1-any-x86_64-update.zip). Pakiety te zawierają poprawki z kilku ostatnich miesięcy.

**AMIGASYSTEM** wydał pakiet aktualizacyjny dla dystrybucji [AROS One](https://drive.google.com/file/d/175bS0GSN3YCQxJoXWkaQmczm20v3HKh1/view?usp=sharing) zawierający U1.B plus dodatkowo wzbogacający AROS One o nowe programy ([lista zmian](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1418&pid=9157)). 

Na swoją aktualizację nie czekał również projekt [AROS Portable](https://arosnews.github.io/aros-portable/) – to doskonała opcja dla tych, którzy chcą wypróbować najnowsze zdobycze systemu, takie jak przeglądarka **Odyssey Web Browser 3.0**, bez konieczności instalacji. Wystarczy nagrać obraz na pendrive i uruchomić go na niemal dowolnym nowoczesnym komputerze.

![AROS Portable](/assets/img/0825/aros.jpg)
*AROS Portable*

Kalamatee kontynuował prace nad portem SDL2. Najnowsze poprawki, które wprowadził, pozwoliły mu już na uruchomienie zaktualizowanego portu Doom 3:  

<iframe width="700" height="480" src="https://www.youtube.com/embed/I23S1BHWqJ8" title="AROS hosted (under WSL) running doom3 with hostgl." frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>  

Ponadto Kalamatee wprowadził w sierpniu do repozytorium ADT poprawki i ulepszenia dla AROS-Shell, SMP, font.datatype, iconlist, Zune, Wanderer i nie tylko! Kolejny pracowity miesiąc ze strony Kalamatee.

**Amigamia**, administrator forum **AROSWorld**, odświeżył wygląd strony. Nowa skórka jest bardziej przejrzysta i nowoczesna. 

Sezon wakacyjny daje o sobie znać szczególnie w AROS Archives – tym razem nowych pozycji jest tak niewiele, że można je policzyć na palcach jednej ręki. Miejmy jednak nadzieję, że w przyszłym miesiącu zaległości zostaną nadrobione z nawiązką :)


> ## [Super-Haxagon](https://archives.arosworld.org/?function=showfile&file=game/action/super-haxagon.x86_64-aros-v11.zip) (v. 3.9.1) `x86_64`
> (autor:	AJ Walter)

Super Hexagon to intensywna i niezwykle wymagająca minimalistyczna gra zręcznościowa autorstwa Terry'ego Cavanagha. Gracz steruje niewielkim trójkątem, omijając nadciągające przeszkody w rytm hipnotycznej, elektronicznej ścieżki dźwiękowej Chipzela. Jej psychodeliczna, pulsująca estetyka i perfekcyjne zsynchronizowanie muzyki z działaniem tworzą wciągające, choć bezlitosne doświadczenie. Dostępna na PC i urządzenia mobilne, gra słynie z przytłaczająco pozytywnych recenzji, a jej nieubłagany poziom trudności i mechanika „jeszcze jednej próby” stanowią idealny test refleksu i koncentracji. Wersja dla AROS oparta jest o otwartoźródłową implementację gry (Super-Haxagon) autorstwa AJ Waltera.

![Super-Haxagon](/assets/img/0825/haxagon.png)
*Super-Haxagon*

> ## [TBFTSS: The Pandora War](https://archives.arosworld.org/?function=showfile&file=game/action/tbftss.x86_64-aros-v11.zip) (v. 1.5.1) `x86_64`
> (autor:	Stephen J Sweeney)

"The Battle for the Solar System: The Pandoran War" to dwuwymiarowy space shooter osadzony w uniwersum science fiction znanym z serii powieści. Rozgrywka, rozgrywająca się pomiędzy tomami książkowej trylogii, pozwala pilotować różnorodne statki kosmiczne – w tym kultowe jednostki z sagi oraz zupełnie nowe modele – w ponad 60 nieliniowych misjach. Gracz angażuje się w intensywne potyczki, wykorzystując zdolności taktyczne i współpracując z AI, aby stawić czoła piratom, zdrajcom oraz potężnej armii Pandory. Dzięki systemowi trofeów, bogatej fabule, gra stanowi gratkę zarówno dla miłośników klasycznych strzelanin, jak i fanów głębokiego, literackiego science-fiction. 

![TBFTSS](/assets/img/0825/tbftss.png)
*The Battle for the Solar System: the Pandora War*

> ## [Tilt-N-Roll](https://archives.arosworld.org/?function=showfile&file=game/action/tiltnroll.x86_64-aros-v11.zip) (v. 1.2.0) `x86_64`
> (autor:	Greg Kennedy)

Tilt-n-Roll to trójwymiarowa wersja klasycznej gry z kulką, stworzona w technologii OpenGL. Kierujesz kątem nachylenia poziomu za pomocą myszki lub klawiatury. Obracając świat, możesz poprowadzić kulkę przez różne przeszkody do wyjścia. Gra ma wbudowany edytor poziomów - może być używany do tworzenia i dystrybucji poziomów wśród znajomych. Świetna propozycja dla tych, którzy szukają nietypowego, lekkiego wyzwania z ciekawym pomysłem na sterowanie.

![Tilt-N-Roll](/assets/img/0825/tiltnroll.png)
*Tilt-N-Roll*

Pozostałe programy:  

|----------|-----------------------------------------------------------------------------------------------|-------------------------------------|
| `x86_64` | [ccd2iso v.0.3](https://archives.arosworld.org/?function=showfile&file=utility/archive/ccd2iso.x86_64-aros-v11.zip) | Convert CloneCD (.ccd) to ISO Images |
| `x86_64` | [Sploiner v.1.01](https://archives.arosworld.org/?function=showfile&file=utility/misc/sploiner.x86_64-aros-v11.zip) | split, join and recover files |

{: .box-note}
Na 32-bit wersję AROS wychodzą już tylko aplikacje Hollywood. Może to już czas, aby producent Hollywood zdecydował się na wydanie swojego programu dla głównej 64-bitowej linii AROSa?

> ## [RNOSoundboard](https://archives.arosworld.org/?function=showfile&file=audio/play/rnosoundboard.i386-aros.lha) (v. 1.0) `i386`
> (autor:	jPV^RNO)

Nowe oprogramowanie stworzone przez jPV^RNO dla AROS 32Bit, RNOSoundboard to aplikacja umożliwiająca odtwarzanie plików audio za pomocą skrótów klawiaturowych i kliknięć myszą. Ożyw swoją imprezę dzięki gotowemu zestawowi utworów muzycznych i sampli!

Główne cechy:
- MUI GUI do aranżowania zestawów dźwiękowych
- Tryb pełnoekranowy soundboard z graficznymi przyciskami
- Ładuje osadzone obrazy okładek z plików MP3, FLAC i Ogg Vorbis do grafiki przycisków soundboard
- Wewnętrzne ładowanie i zapisywanie listy odtwarzania
- Programowalne skróty klawiszowe, a także opcje zapętlania i głośności dla każdego pliku audio
- Obsługa przeciągania i upuszczania do ładowania plików, katalogów i list odtwarzania
- Obsługa formatów MP3, FLAC, Ogg Vorbis, AAC, AIFF, WAV, Protracker, DigiBooster, SID, AHX, FastTracker II, ScreamTracker, OctaMED, The Player, NoisePacker, ProRunner, Oktalyzer, Impulse Tracker, Ultra Tracker, Ice Tracker, Liquid Tracker, Quadra Composer i wiele innych formatów
- Obsługa ARexx, wiersza poleceń i tooltypes

![RNOSoundboard](/assets/img/0825/rnosoundboard.jpg)
*RNOSoundboard*


|----------|-----------------------------------------------------------------------------------------------|-------------------------------------|
| `i386` | [Cards Making Kit v.2.30](https://archives.arosworld.org/?function=showfile&file=game/utility/cardsmakingkit.lha) | SDK to make your decks for Morgue Games |
| `i386` | [Janggi v.1.0](https://archives.arosworld.org/?function=showfile&file=game/board/janggi.i386-aros.lha) | Korean chess program UCI compatible |
| `i386` | [PolarPaint v.1.169](https://archives.arosworld.org/?function=showfile&file=graphics/edit/polarpaint_aros.lha) | Paint program made with Hollywood |


