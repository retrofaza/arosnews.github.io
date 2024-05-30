---
layout: post
title: AROS x86 - maj 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 0524
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

> ## [wipEout Rewrite](http://archives.aros-exec.org/?function=showfile&file=game/driving/wipeout_rewrite.i386-aros.zip) (v.1.2)
> (autorzy: phoboslab/arczi/Farox)

wipEout Rewrite to reimplentacja kultowej gry z 1995 roku, w której gracze ścigają się na futurystycznych torach, używając szybkich statków antygrawitacyjnych. Wersja z AROS Archives nie zawiera zasobów gry (tekstur, modeli 3D itp.), można je ściągnąć ze [strony autora oryginalnego portu](https://phoboslab.org/log/2023/08/rewriting-wipeout). Dla fanów gry wipEout to świetna okazja, aby wrócić do nostalgii i poczuć ducha futurystycznych wyścigów!

![wipEout Rewrite](/assets/img/wipeout.jpg)
*Reimplementacja gry wipEout z PSX-a*

> ## [LoView](http://archives.aros-exec.org/?function=showfile&file=graphics/viewer/loview.i386-aros.lha) (v. 2024)
> (autor: Simone "Tuxedo" Monsignori)

Simone Monsignori przygotował nową wersję przeglądarki obrazków - LoView. Program obsługuje wiele formatów plików (w zależności od zainstalowanych DataTypes) i może 
zapisywać w formacie JPG, PNG, IFF lub BMP. Dostępne są także także inne operacje na tych plikach (kasowanie, kopiowanie, przenoszenie, zmiana nazwy, prosta edycja). 

![LoView](/assets/img/loview2024.png)
*LoView*

> ## [GI Omino Stage](http://archives.aros-exec.org/?function=showfile&file=game/giominoaros.i386-aros.zip) (v. 1.1)
> (autor: Giovanni Iacobelli)

Prosta gra platformowa w której zbieramy apteczki. Bohater którym kierujemy musi unikać strzykawek i stawić czoła złemu wirusowi na ostatnich poziomach.

![GI Omino Stage](/assets/img/giomino.jpg)
*GI Omino Stage*

> ## [GISplit](http://archives.aros-exec.org/?function=showfile&file=utility/filetool/gisplit.i386-aros.zip) (v. 1.5)
> (autor: Giovanni Iacobelli)

Niewielki program do dzielenia dużych plików na małe pliki w celu przeniesienia ich na dyskietki.

![GISplit](/assets/img/gisplit.png)
*GI Split*

> ## [GMoreAros](http://archives.aros-exec.org/?function=showfile&file=utility/text/misc/gmore.i386-aros.zip) (v. 1.2)
> (autor: Giovanni Iacobelli)

Prosta przeglądarka tekstu podobna do MORE. 

![GMoreAros](/assets/img/gmore.png)
*GMoreAros*

> ## [GScopaAros](http://archives.aros-exec.org/?function=showfile&file=game/card/giscopa.i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

Scopa to popularna włoska gra karciana. W tej cyfrowej wersji gracz będzie grał przeciwko sztucznej inteligencji komputera. Grę wygrywa gracz lub komputer, który jako pierwszy osiągnie lub przekroczy wynik 11.

![GScopaAros](/assets/img/giscopa.png)
*GScopaAros*

> ## [GIMorraCinese](http://archives.aros-exec.org/?function=showfile&file=game/board/gimorracinese.i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

GI Morra Cinese, komputerowa wersja popularnej gry znanej jako Papier Nożyce Kamień.

![GIMorraCinese](/assets/img/gimorra.png)
*GIMorraCinese*

> ## [GIMineAros](http://archives.aros-exec.org/?function=showfile&file=game/board/gimine.i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

Jeszcze jedna odsłona klasycznego Minesweepera.

![GIMineAros](/assets/img/gimine.png)
*GIMineAros*

> ## [GI Poker](http://archives.aros-exec.org/?function=showfile&file=game/card/gipoker.i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

W latach 70. i 80. bardzo popularne były automaty do wideo pokera. Gracz stawia zakład, a komputer losowo generuje karty, które są wyświetlane na ekranie.
Następnie gracz może zmienić kilka wybranych przez siebie kart, aby uzyskać lepszy wynik.

![GI Poker](/assets/img/gipoker.png)
*GI Poker*

> ## [GI Sequence Memory](http://archives.aros-exec.org/?function=showfile&file=game/board/gisequencememory.i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

Gra ćwicząca pamięć i koncentrację. Celem gry jest powtórzenie sekwencji wyświetlanych kolorów.

![GI Sequence Memory](/assets/img/gimemory.png)
*GI Sequence Memory*

> ## [7Mezzo Plus](http://archives.aros-exec.org/?function=showfile&file=game/card/7mezzoplus.i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

Popularna włoska gra świąteczna.

![7Mezzo Plus](/assets/img/7mezzo.png)
*7Mezzo Plus*

> ## [Witch Cleaner](http://archives.aros-exec.org/?function=showfile&file=network/server/misc/witchcleaner.lha) (v. 3.20)
> (autor:	Juan Carlos Herrán Martín)

Mały i prosty program do czyszczenia kosza .recycled z przestarzałych i starych plików. Program usuwa kolejne pliki z OWB (Orygin Web
Browser):
- Cache drawer.
- cookies.db
- History.db
- TopSites.db
- WebpageIcons.dbth
- Pliki cookie LocalStorage
- 29a5abb3-i386-aros.cache-4 UWAGA: Jeśli usuniesz tę pamięć podręczną to po ponownym uruchomieniu OWB, pamięć podręczna zostanie przywrócona.
- font: fonts cache
- AutoFill.db
- Bookmarks.html
- Passwords.db
- sesje

![Witch Cleaner](/assets/img/witchcleaner.jpg)
*Witch Cleaner*

> ## [L.M. Calendar&Clock](http://archives.aros-exec.org/?function=showfile&file=network/server/misc/witchcleaner.lha) (v. 3.20)
> (autor:	Juan Carlos Herrán Martín)

Zegar i kalendarz z postaciami ze świata gry Los Malditos del Valle del Cerro. Narzędzie być przydatne do kontrolowania czasu jaki spędzamy przed komputerem. Możemy ustawiać alarmy, a nawet zaplanować porę samoczynnego wyłączenia komputera.

![L.M. Calendar&Clock](/assets/img/lmcalendarclock.jpg)
*L.M. Calendar&Clock*
