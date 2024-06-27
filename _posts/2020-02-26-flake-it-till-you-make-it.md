---
layout: post
title: AROS x86 - czerwiec 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 0624
---

W maju społeczność AROSa jak zwykle nie próżnowała. Na początku miesiąca Deadwood wypuścił zbiorczy zestaw poprawek dla systemu bazowego w wersji 20220318-1. Aktualizacja **Update 1** zawiera głównie poprawki wprowadzane na przestrzeni ostatnich kilku miesięcy w ramach "irytujących bugów miesiąca".  

{: .box-success}
Strona z której można pobrać najnowszy system bazowy oraz Updade 1:  
[https://www.axrt.org/downloads-aros](https://www.axrt.org/downloads-aros)  
Pełna lista zmian:  
[https://github.com/deadwood2/AROS/releases/tag/ABIv0_20220318-1](https://github.com/deadwood2/AROS/releases/tag/ABIv0_20220318-1)  

W najbliższych dniach możemy się spodziewać dystrybucji AROS One 2.5, która będzie zawierać wszystkie aktualne poprawki plus wiele dodatkowych udogodnień. W oczekiwaniu na tę dystrybucję możecie poczytać [wywiad z Carlo "AMIGASYSTEM" Spadoni](https://obligement-free-fr.translate.goog/articles/itwcarlospadoni.php?_x_tr_sl=fr&_x_tr_tl=en&_x_tr_hl=fr&_x_tr_sch=http) (autorem dystrybucji AROS One) przeprowadzony przez portal OBLIGEMENT.

**Amiwell79** uruchomił nową stronę pod adresem [https://www.tinyaros.it/](www.tinyaros.it). Znajdziemy tam dystrybucję Tiny AROS w wersji 3.2, a także dodatkowe paczki z grami i oprogramowaniem.

W ankiecie na Irytujący bug miesiąca mieliśmy w maju remis. Równą liczbę głosów otrzymały zgłoszenia:  
*#125 (You can access a drawer icon even if the directory assigned to it does not exist)*  
*#140 (Wanderer: Changing the disk label does not work)*

![Irytujący bug miesiąca](/assets/img/ibotm0524.png)
*Irytujący bug miesiąca - maj 2024*

W drodze losowania Deadwood zajął się błędem z ikonami, a stosowną poprawkę można już pobrać w [wątku z majową ankietą](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1246&pid=5344). Bug nr #140 automatycznie przechodzi na czerwiec w związku z czym w kolejnym miesiącu nie będzie nowej ankiety.

Mocnymi pozycjami w AROS Archives są tym razem z pewnością port gry **wipeOut** oraz nowa wersja przeglądarki obrazków **LoView**. Pojawiło się też wiele mniejszych propozycji, które również mogą przykuć uwagę, m.in. cała seria gier i programów od Giovanni Iacobelli. Poniżej pełna lista.

> ## [Python](http://archives.aros-exec.org/?function=showfile&file=development/language/i386-aros-python2.5.2.zip) (v. 2.5.2)
> (autor: Stanisław Szymczyk)

Eksperymentalny Python 2.5.2 dla AROS. Ta wersja zotała skompilowana przez Deremona z nową biblioteką C i jest kompatybilna z najnowszym wydaniem AROSa. Zawiera następujące moduły:
- array, cmath, math, struct, time, operator, weakref, testcapi, random, collections, itertools, strop  

Ten port nie obsługuje dynamicznie łączonych rozszerzeń.

![Python](/assets/img/python205.png)
*Python-2.5.2*

> ## [Image2PDF](http://archives.aros-exec.org/?function=showfile&file=office/dtp/image2pdf.lha) (v. 2.7)
> (autor: Bernd Assenmacher)

Małe narzędzie do konwersji obrazów do formatu PDF. Przede wszystkim służy do konwertowania skanów wykonanych np. za pomocą Scandal lub Scanquix do dokumentów PDF w określonych formatach wyjściowych, takich jak A3, A4, A5, Legal, Letter lub ImageSize, ale może być również używane do konwersji innych plików graficznych.

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

![AROS Backdrops](/assets/img/tapety.jpg)
*AROS Backdrops*
