---
layout: post
title: AROS x86 - sierpień 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 0724
---

W lipcu Deadwood rozpoczął prace nad aktualizacją przeglądarki OWB (zgodnie z [Development plan](https://arosworld.org/infusions/forum/viewthread.php?thread_id=1114&rowstart=20&pid=5871#post_5869)). Na forum AROS World założone są tematy dotyczące zarówno 32-bitowej jak i 64-bitowej wersji przeglądarki. Można tam pobrać najnowszą wersję deweloperską i uczestniczyć w testach, do czego mocno zachęcam. Jednocześnie wypuszczona została publiczna wersja AROS 64-bit na której można pracować z 64-bitową Oddysey Web Browser.

Na blogu zamieściłem serię tutoriali, jak zainstalować Oddysey Web Browser w różnych środowiskach:
- [Oddysey Web Browser w AROS Linux hosted](https://arosnews.github.io/oddysey-web-browser-aros-linux-hosted/)  
- [Oddysey Web Browser w AxRT Linux](https://arosnews.github.io/oddysey-web-browser-axrt-linux/)  
- [Oddysey Web Browser w AxRT Windows 11 (WSL2)](https://arosnews.github.io/oddysey-web-browser-axrt-wsl2/)  

W serwisie YouTube na kanale Amiten TV jest do obejrzenia zapis blisko 3 godzinnego [live streama](https://www.youtube.com/watch?v=KigowKD1Aag) z przeglądu funkcji i oprogramowania AROS One 2.5. **Amiten TV** używa w pełni obsługiwanego komputera PC, karty graficznej 3D, karty dźwiękowej, karty sieciowej. Film jest w języku hiszpańskim. Polecam!

Na [OSNews.com](https://www.osnews.com/story/140225/package-amigaos-software-for-linux-and-windows-with-axruntime/) został zauważony AROS w wersji AXRuntime. Warto zapoznać się z tym wpisem oraz komentarzami zamieszonymi pod nim.

W ankiecie na Irytujący bug miesiąca mieliśmy w lipcu remis. Równą liczbę głosów otrzymały zgłoszenia:  
*#144 (Graphical artifacts when dragging an icon)*  
*#25 (Shell won't open from icon that leave out)*

![IBOTM 07.2024](/assets/img/ibotm0724.png)
*Irytujący Bug Miesiąca - lipiec 2024*

Naprawiony przez **Deadwooda** został bug *#25*, a [poprawka](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1279&pid=5842#post_5811) ta zasadniczo rozwiązuje również problem buga *#26 Multiple copying of the "Shell" icon when it's deleted*. Więc w lipcu mamy naprawione dwa Irytujące bugi, a bug *#144* przechodzi na sierpień. 

W AROS Archives czuć sezon wakacyjny, bo nowych programów niewiele, ale nawet z tej ilości można wybrać coś ciekawego :)

> ## [The Chaotic Dungeon](http://archives.aros-exec.org/?function=showfile&file=game/roleplaying/chaotic-dungeon.i386-aros.zip) (v. 1.0)
> (autor: Space.cpp)

Ta gra to roguelite dungeon crawler z rozgrywką w stylu Zeldy. Przedzieraj się przez lochy, pokonując wrogów i zbierając przedmioty. Awansuj swoją postać, aby stać się silniejszym i z łatwością pokonywać kolejne piętra. Jeśli zginiesz, musisz zacząć od nowa, ale zachowujesz swoje atrybuty. Czy uda ci się dotrzeć do 30. piętra, zabić strażnika i wrócić na powierzchnię żywy?

![The Chaotic Dungeon](/assets/img/chaotic.png)
*The Chaotic Dungeon*

> ## [WhatIFF?](http://archives.aros-exec.org/?function=showfile&file=document/misc/whatiff3.14.lha) (v. 3.14)
> (autorzy: WhatIFF? Staff)

Magazyn o tematyce amigowej wydawany w formacie Amigaguide. Wydanie 14 - Sierpień 2024 r.

![WhatIFF?](/assets/img/whatiff314.png)
*WhatIFF? - sierpień 2024*

> ## [SFSobject](http://archives.aros-exec.org/?function=showfile&file=utility/misc/sfsobject.i386-aros.zip) (v. 1.6)
> (autorzy: Jean-Marie COAT, Farox)

Jest to małe narzędzie do ustawiania niektórych atrybutów obiektów SmartFilesystem. Obiektami systemu plików są na przykład katalogi i pliki. Za pomocą SFSObject można ukryć niektóre pliki lub uczynić katalog nieusuwalnym, nawet gdy ochrona przed usunięciem jest wyłączona.

![SFSobject](/assets/img/sfsobject.png)
*SFSobject*

> ## [Baphomet ScreenSaver](http://archives.aros-exec.org/?function=showfile&file=utility/misc/baphometscreensaver.lha) (v. 1.0)
> (autor: Juan Carlos Herrán Martín)

Wygaszacz ekranu dla AROSa. Motywem przewodnim jest odwieczna walka pomiędzy aniołami i demonami.

![Baphomet ScreenSaver](/assets/img/baphometss.jpg)
*Baphomet ScreenSaver*

> ## [Leeko](http://archives.aros-exec.org/?function=showfile&file=demo/scene/fit/leeko-i386-aros.zip) (v. 1.0)
> (autor: Fit demogroup, port by Farox)

Leeko to produkcja grupy Fit. Po raz pierwszy została zaprezentowana na party Assembly 2003 w konkursie *Combined 64k Intro*, gdzie zajęła 3 miejsce.  

Jest to port dla AROS i386 ABIv0 autorstwa Faroxa oparty na źródłach dla AmigaOS4. Do optymalnej wydajności potrzebna jest karta graficzna (bez niej też działa, ale wolniej). Demo można uruchamić w różnych rozdzielczościach, opis parametrów uruchomieniowych znajduje się w pliku README.

![Leeko](/assets/img/lekko.jpg)
*Leeko*

> ## [Micery](http://archives.aros-exec.org/?function=showfile&file=demo/scene/fit/micery-i386-aros.zip) (v. 1.0)
> (autorzy: Bandwagon & Fit demogroups, port by Farox)

Micery to produkcja grup Bandwagon & Fit. Po raz pierwszy została zaprezentowana na imprezie Alternative Party V (2004) w konkursie *Dynamic Demo*, gdzie zajęła 2 miejsce.  

Jest to port dla AROS i386 ABIv0 autorstwa Faroxa oparty na źródłach dla AmigaOS4. Do optymalnej wydajności potrzebna jest karta graficzna (bez niej też działa, ale wolniej). Demo można uruchamić w różnych rozdzielczościach, opis parametrów uruchomieniowych znajduje się w pliku README.  

(Demo nie ma zakończenia, aby z niego wyjść należy nacisnąć ESC.)

![Micery](/assets/img/micery.jpg)
*Micery*

