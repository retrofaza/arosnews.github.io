---
layout: post
title: AROS x86 - sierpień 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 0724
---


W ramach Irytującego Buga Miesiąca w sierpniu został naprawiony bug:  
*#144 (Graphical artifacts when dragging an icon)*  
Link do poprawki znajdziecie w [temacie na forum ArosWorld](https://arosworld.org/infusions/forum/viewthread.php?thread_id=1299&pid=6134#post_6124).

Na ten moment program IBOTM zostaje zawieszony. Przypomnę, że ankiety w których użytkownicy mogli głosować na najbardziej irytujące ich bugi pojawiały się co miesiąc począwszy od listopada 2023. Kolejno wygrywały:  
*#64 (Wanderer: properly run tools with CLI tooltype)*  
*#107 (Wanderer Rename: Cannot change size of letters in name without changing name)*  
*#91 (Wrong parsing of boot parameters in Prefs/Boot)*  
*#115 (Add an easy way to enable tethering in Network preferences)*  
*#135 (AHCI - only 7.9 GB allocated out of disk)*  
*#105 (DiskInfo showing OFS instead of FAT)*  
*#116 (Wanderer: Allow deleting by pressing Del key)*  
*#125 (You can access a drawer icon even if the directory assigned to it does not exist)*  
*#140 (Wanderer: Changing the disk label does not work)*  
*#25 (Shell won't open from icon that leave out)*  
*#26 (Multiple copying of the Shell icon when it is deleted)*  
*#144 (Graphical artifacts when dragging an icon)*  

Dzięki pracy Deadwooda wszystkie te bugi zostały załatane, a AROS stał się o wiele stabilniejszy i wygodniejszy w użyciu. IBOTM być może wróci do nas w przyszłym roku! Póki co wysiłek naszego najbardziej obecnie aktywnego dewelopera został przekieroway na aktualizację przeglądarki OWB.

Timothy Deters, obecny właściciel praw do programu **Final Writer**, wprowadził długo oczekiwaną aktualizację. Nowa wersja (7.1) zawiera funkcję eksportu do pliku PDF, lokalizację zgodną z wytycznymi AmigaOS, możliwość drukowania przez FTP/IPP, zaktualizowaną obsługę formatu RTF oraz zupełnie nowy mechanizm sprawdzania pisowni w czasie rzeczywistym oparty na MySpell. Na [stronie producenta](https://final-writer.com/) dostępne są wersje dla AROS 68k/ApolloOS, AROS x86-64 (ABIv1) oraz AROS x86 (ABIv0). Pełna wersja kosztuje 50$. Wersje demo są do pobrania bezpłatnie.

![The Chaotic Dungeon](/assets/img/finalwriter7.png)
*Final Writer 7.1 dla AROSa*

Firma Airsoft Softwair wypuściła aktualizację wtyczki do programu Hollywood o nazwie RapaGUI. Wersja 2.2 zawiera kilka poprawek błędów. RapaGUI to jedna z najczęściej używanych wtyczek do Hollywood, umożliwiająca tworzenie graficznych interfejsów. Interfejsy te są definiowane w plikach XML, co pozwala na ich uruchamianie na różnych systemach operacyjnych z użyciem natywnych widżetów, co zapewnia spójny wygląd i styl. [Wersję dla systemu AROS x86](https://www.hollywood-mal.com/download/RapaGUI_Amiga.lha) można pobrać z oficjalnej strony Hollywood.

Na koniec jak zwykle nowości z AROS Archives. W tym miesiącu pojawiło się kilka nowych pozycji. Poniżej szczegółowa lista.

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

Jest to port dla AROS i386 ABIv0 autorstwa Faroxa oparty na źródłach dla AmigaOS4. Do optymalnej wydajności potrzebna jest karta graficzna (bez niej też działa, ale wolniej). Demo można uruchomić w różnych rozdzielczościach, opis parametrów uruchomieniowych znajduje się w pliku README.

![Leeko](/assets/img/lekko.jpg)
*Leeko*

> ## [Micery](http://archives.aros-exec.org/?function=showfile&file=demo/scene/fit/micery-i386-aros.zip) (v. 1.0)
> (autorzy: Bandwagon & Fit demogroups, port by Farox)

Micery to produkcja grup Bandwagon & Fit. Po raz pierwszy została zaprezentowana na imprezie Alternative Party V (2004) w konkursie *Dynamic Demo*, gdzie zajęła 2 miejsce.  

Jest to port dla AROS i386 ABIv0 autorstwa Faroxa oparty na źródłach dla AmigaOS4. Do optymalnej wydajności potrzebna jest karta graficzna (bez niej też działa, ale wolniej). Demo można uruchomić w różnych rozdzielczościach, opis parametrów uruchomieniowych znajduje się w pliku README.  

(Demo nie ma zakończenia, aby z niego wyjść należy nacisnąć ESC.)

Oba dema, Leeko i Micery, możecie zobaczyć [na filmiku w serwisie Youtube](https://www.youtube.com/watch?v=4cN1mXnszIQ) na kanale Jamesa Mattsona.

![Micery](/assets/img/micery.jpg)
*Micery*

