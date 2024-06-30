---
layout: post
title: AROS x86 - czerwiec 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 0624
---

W czerwcu wyszedł AROS One 2.5. Dystrybucja przygotowana przez Carlo "AMIGASYSTEM" Spadoni oparta jest na najnowszym systemie bazowym i zawiera wszystkie ostatnie aktualizacje i poprawki. Autor wiele wysiłku poświęcił na konfigurację i testowanie załączonego oprogramowania, którego jest naprawdę dużo. Pod ręką mamy wszystko co niezbędne w systemie. AROS One to także nowoczesne, wysokiej jakości tła, okna i ikony. Dzięki temu AROS One to obecnie najlepsza dystrybucja zarówno dla początujących użytkowników AROSa jak i dla zaawansowanych. 

![AROS One 2.5](/assets/img/arosone25.jpg)
*AROS One 2.5*

{: .box-success}
Pełna lista zmian dla AROS One v2.5:  
[https://arosworld.org/infusions/forum/viewthread.php?thread_id=1124&pid=5394#post_5394](https://arosworld.org/infusions/forum/viewthread.php?thread_id=1124&pid=5394#post_5394)

Na kanale YouTube Jamesa Mattsona można zobaczyć kilka filmików z działania AROS One 2.5: [Video1](https://www.youtube.com/watch?v=2_E9SkgzHEw), [Video2](https://www.youtube.com/watch?v=e0frJFbanXc), [Video3](https://www.youtube.com/watch?v=tBkEZjfg5yM). 


W czerwcu w ramach **Irytującego buga miesiąca** Deadwood zajął się błędem: 
*#140 (Wanderer: Changing the disk label does not work)*
Stosowną poprawkę można już pobrać w [wątku z czerwcową ankietą](https://arosworld.org/infusions/forum/viewthread.php?thread_id=1266&pid=5703#post_5671).
Aktualną ankietę znajdziemy tutaj: [Irytujący Bug Miesiąca - Lipiec](https://arosworld.org/infusions/forum/viewthread.php?thread_id=1279&pid=5712).

Na koniec jak zwykle nowości z AROS Archives, gdzie pojawiło się kilka mniejszych produkcji i aktualizacji. Poniżej szczegółowe zestawienie.

> ## [Python](http://archives.aros-exec.org/?function=showfile&file=development/language/i386-aros-python2.5.2.zip) (v. 2.5.2)
> (autor: Stanisław Szymczyk)

Eksperymentalny Python 2.5.2 dla AROS. Ta wersja zotała skompilowana przez Deremona z nową biblioteką C i jest kompatybilna z najnowszym wydaniem AROSa. Zawiera następujące moduły:
- array, cmath, math, struct, time, operator, weakref, testcapi, random, collections, itertools, strop  

Ten port nie obsługuje dynamicznie łączonych rozszerzeń.

![Python](/assets/img/python205.png)
*Python-2.5.2*

> ## [Aros-GOCR](http://archives.aros-exec.org/?function=showfile&file=development/language/i386-aros-python2.5.2.zip) (v. 0.52)
> (autor: Joerg Schulenburg)

GOCR to program do optycznego rozpoznawania znaków, wydany na licencji. Powszechnej Licencji Publicznej GNU. Odczytuje obrazy w wielu formatach i generuje plik tekstowy. Możliwe formaty obrazów to pnm, pbm, pgm, ppm, niektóre pliki obrazów pcx i tga.

Jest to nowa kompilacja wersji 0.52 programu, działająca z najnowszą wersją AROSa.

![Aros-GOCR](/assets/img/gocr.png)
*Aros-GOCR*


> ## [Image2PDF](http://archives.aros-exec.org/?function=showfile&file=office/dtp/image2pdf.lha) (v. 2.7)
> (autor: Bernd Assenmacher)

Małe narzędzie do konwersji obrazów do formatu PDF. Przede wszystkim służy do konwertowania skanów wykonanych np. za pomocą Scandal lub Scanquix do dokumentów PDF w określonych formatach wyjściowych, takich jak A3, A4, A5, Legal, Letter lub ImageSize, ale może być również używane do konwersji innych plików graficznych.

Zmiany w wersji 2.7:
- wprowadzono kilka drobnych poprawek kosmetycznych
- ulepszone etykiety narzędzi
- rozszerzono zakres skalowania funkcji "skaluj obraz(y) do" (teraz 10-6000)
- dodano funkcję "abort", aby mieć możliwość przerwania procesów gdy w pętli znajduje się wiele obrazów. Nie działa to z funkcją "Konwertuj PDF do". 

![Image2PDF](/assets/img/img2pdf27.png)
*Image2PDF*

> ## [Omanko!](http://archives.aros-exec.org/?function=showfile&file=utility/filetool/omanko.lha) (v.1.25)
> (autor: Juan Carlos Hérran Martín)

Małe narzędzie stworzone do generowania sum kontrolnych MD5 i CRC32 plików. W wersji 1.25 wprowadzono drobne poprawki w grafice.

![Omanko!](/assets/img/omanko125.png)
*Omanko!*

> ## [Videntium Picta](http://archives.aros-exec.org/?function=showfile&file=graphics/viewer/videntiumpicta.lha) (v. 3.05)
> (autor: Juan Carlos Hérran Martín)

Videntium Picta to przeglądarka obrazów, której główną cechą jest poszanowanie prywatności użytkownika (nie ma listy ostatnich plików, nie ma listy odtwarzania, może być używana z pamięci USB, CD itp.) Dla użytkownikow AROSa ta wersja jest freeware (wcześniejsza miała wymóg rejestracji drogą mailową).

![Videntium Picta](/assets/img/videntium305.png)
*Videntium Picta*

> ## [Vintage Song Player](http://archives.aros-exec.org/?function=showfile&file=audio/play/vintagesongplayer.lha) (v. 2.6)
> (autor: Juan Carlos Herrán Martín)

Odtwarzacz muzyki - Juke Box obsługujący pliki w tych formatach: 8svx, aiff, mp3, ogg, m4a, mod, med, dbm, hvl, xm, s3m, ac3, wav, flac, sid

![Vintage Song Player](/assets/img/vintage260.png)
*Vintage Song Player*

> ## [iConecta](http://archives.aros-exec.org/?function=showfile&file=network/misc/iconecta.lha) (v. 5.2)
> (autor: Juan Carlos Herrán Martín)

Mały i prosty program do testowania połączenia internetowego. W tej wersji dodano nową grafikę, użyto darmowego fontu i zastosowano większe cyfry zegara.

![iConecta](/assets/img/iconecta520.png)
*iConecta*

> ## [Tressette a Perdere](http://archives.aros-exec.org/?function=showfile&file=game/card/gitressette.i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

Tressette a Perdere to popularna włoska gra karciana. W tej cyfrowej wersji gracz będzie grał przeciwko sztucznej inteligencji komputera, która zastąpi trzech przeciwników. Gra kończy się, gdy jeden z graczy osiągnie 51 punktów, a wygrywa gracz, który zdobędzie najmniej punktów.

![Tressette a Perdere](/assets/img/tressette.png)
*Tressette a Perdere*

> ## [Giocodel15](http://archives.aros-exec.org/?function=showfile&file=game/card/giocodel15.i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

GiocoDel15 to klasyczna gra logiczna sprzed około 50 lat. Składa się z tabeli z 4 kolumnami i 4 wierszami, w których umieszczono 15 pól ponumerowanych od 1 do 15 oraz pustego pudełka. Celem gry jest przestawienie pól po ich losowym przetasowaniu. 

![Giocodel15](/assets/img/giocodel.png)
*Giocodel15*

> ## [Catch It](http://archives.aros-exec.org/?function=showfile&file=game/action/catchit.i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

Prosta gra w której celem jest znalezienie klucza i dostanie się do wyjścia. Po drodze trzeba uważać na przeszkadzajki i nie dać się złapać strażnikom. Do przejścia jest 10 poziomów.

![Catch It](/assets/img/catchit.png)
*Catch It*

> ## [Stoppa card game](http://archives.aros-exec.org/?function=showfile&file=game/card/gistoppa.i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

La Stoppa to włoska hazardowa gra karciana podobna do pokera. W tej wersji zmierzymy się przeciwko trzem komputerowym graczom. 

![Stoppa card game](/assets/img/lastoppa.png)
*Stoppa card game*

> ## [GI SlotGame](http://archives.aros-exec.org/?function=showfile&file=game/board/slotgamearos.i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

Gra w Slotsy. Na szczęście nie na prawdziwe pieniądze :)

![GI SlotGame](/assets/img/slotgame.png)
*GI SlotGame*


> ## [AROS Space Backdrops](http://archives.aros-exec.org/?function=showfile&file=graphics/theme/spacearosbackdrops.zip) (v. 1.0)
> ## [AROS Scenic Backdrop](http://archives.aros-exec.org/?function=showfile&file=graphics/theme/scenic_backdrops.zip) (v. 1.0)
> (autor: James Mattson)

Tła dla AROSa. W pierwszym archiwum mamy 10 teł w tematyce kosmicznej, a w drugim 8 innych. Tła mają logo AROS i są w wysokiej rozdzielczości.

Nagrania na Youtube prezentujące tła: [Video1](https://www.youtube.com/watch?v=PD04-5snP2E), [Video2](https://www.youtube.com/watch?v=U6fSA5-ny9k).

![AROS Backdrops](/assets/img/tapety.jpg)
*AROS Backdrops*
