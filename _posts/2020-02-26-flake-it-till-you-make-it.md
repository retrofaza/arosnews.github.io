---
layout: post
title: AROS x86 - kwiecień 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 0424
---



![Irytujący bug miesiąca](/assets/img/ibotm0424.png)
*Irytujący bug miesiąca - kwiecień 2024*

Jak zwykle zachęcam do wzięcia udziału w kolejnym głosowaniu. Tym razem dla uczczenia pół roku działalności ankiety czeka nas niespodzianka - aż dwa błędy zostaną wytypowane i naprawione :) [Link do aktualnej ankiety](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1228&pid=4744). 

Nowości w AROS Archives z kwietnia:

> ## [ScummVM](http://archives.aros-exec.org/?function=showfile&file=emulation/misc/scummvm-1.9.0-1.i386-aros.zip) (v.1.9.0)
> (autorzy: Max Horn, Eugene Sandulenko i wielu innych)

ScummVM

![ScummVM](/assets/img/scumm.png)
*ScummVM 1.9.0*

> ## [ResidualVM](http://archives.aros-exec.org/?function=showfile&file=emulation/misc/residualvm-0.3.1-1.i386-aros.zip) (v. 0.3.1)
> (autorzy: Thomas Allen, Torbjorn Andersson i wielu innych)

ResidualVM

![ResidualVM](/assets/img/residualvm.png)
*ResidualVM*

> ## [ScummVM_Kens](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/scummvm_kens.lha) (v. 0.5)
> ## [ResidualVM-Kens](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/residualvm-kens.lha) (v. 0.5)
> ## [DOSBox Kens](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/dosbox-kens.lha) (v. 0.1)
> ## [MBX Kens](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/mbx-kens-unofficial.lha)(v. 0.1)
> (autor: amiwell79)

Nieoficjalne ikony szuflad w stylu Kens dla ScummVM, ResidualVM, DOSBox oraz gier Myst i MBX.

![Kens](/assets/img/iconscumm.png)
*Zestaw ikon w stylu Kens*

> ## [ADoom3](http://archives.aros-exec.org/?function=showfile&file=game/fps/adoom3-1.5.3.i386-aros.zip) (v. 1.5.3)
> (autor: Nick "Kalamatee" Andrews)

ADoom 3

![ADoom3](/assets/img/doom3.jpg)
*ADoom 3*

> ## [MBX Magical Broom Ex](http://archives.aros-exec.org/?function=showfile&file=game/action/mbx.i386-aros.zip) (v. 1.0)
> (autor: Farox)

MBX Magical Broom Ex

![MBX Magical Broom Ex](/assets/img/mbx.jpg)
*Magical Broom Extreme (MBX)*

> ## [Protrekkr 2](http://archives.aros-exec.org/?function=showfile&file=audio/tracker/protrekkr.i386-aros.zip) (v. 2.6.7)
> (autor: Franck "hitchhikr" Charlet)

Protrekkr 2

![Protrekkr](/assets/img/protrekkr267.png)
*Protrekkr 2*

> ## [Origami Intro](http://archives.aros-exec.org/?function=showfile&file=demo/intro/origami.i386-aros.zip) (v. 1.0)
> (autor: Faemiyah Demogroup)

Origami Intro

![Origami Intro](/assets/img/origami.jpg)
*Origami Intro*

> ## [The Fulcrum](http://archives.aros-exec.org/?function=showfile&file=demo/scene/thefulcrum.i386-aros.zip) (v. 1.0)
> (autorzy: Matrix Demogroup)

Kolejna demoscenowa produkcja przeportowana dla AROSa przez Faroxa. The Fulcrum to zwycięskie demo z party Mekka & Symposium 1998. To wydanie dla AROS opiera się na imponującej pracy wykonanej przez M-HT, który przekonwertował wszystkie źródła ASM na
C++/SDL i wydał dla Linuksa i OpenPandora Handheld kilka lat temu. Jego źródła znajdują się tutaj https://github.com/M-HT/fulcrum.

![The Fulcrum](/assets/img/fulcrum.jpg)
*The Fulcrum*

> ## [DUMB](http://archives.aros-exec.org/?function=showfile&file=development/library/libdumb.i386-aros.zip) (v. 0.93)
> (autorzy: Dumb team/M-HT)

DUMB to biblioteka odtwarzaczy IT, XM, S3M i MOD opracowana przez Roberta J. Ohannessiana, Juliena Cugnière'a i Bena Davisa. Dzięki Faroxowi, który skompilował ją na potrzeby portu dema Fulcrum, jest teraz dostępna dla wszystkich programistów AROSa do wykorzystania w swoich projektach. 

![DUMB](/assets/img/dumb.png)
*DUMB - "Dynamic Universal Music Bibliotheque"*

> ## [Image2PDF](http://archives.aros-exec.org/?function=showfile&file=office/dtp/image2pdf.lha) (v. 2.6)
> (autor: Bernd Assenmacher)

Małe narzędzie do konwersji obrazów do formatu PDF. Przede wszystkim służy do konwertowania skanów wykonanych np. za pomocą Scandal lub Scanquix do dokumentów PDF w określonych formatach wyjściowych, takich jak A3, A4, A5, Legal, Letter lub ImageSize, ale może być również używane do konwersji innych plików graficznych.

Zmiany w wersji 2.6:
- zaktualizowany plik instrukcji
- W systemach MorphOS i AROS plik instrukcji jest teraz kopiowany do szuflady instalacyjnej.
- W systemie MorphOS polecenie "Path" w s:user-startup jest teraz nieaktywne. Jeśli ma być aktywne, należy je ręcznie odkomentować, zapisać, a następnie zrestartować komputer
- dodano możliwość skalowania obrazów we wszystkich wybranych formatach
- dodano możliwość kompresji dokumentów PDF, gdy zainstalowany jest Ghostscript
- możliwość zmiany orientacji dokumentów PDF (nie w formacie ImageSize)
- można teraz ustawić margines wydruku
- użycie wiersza poleceń automatycznie dostosuje orientację (nie dotyczy formatu ImageSize)
- skompilowano pojedyncze wersje dla obsługiwanych platform
- usunięto aplet z archiwum
- dodano funkcję drukowania dokumentów PDF

![Image2PDF](/assets/img/image2pdf26.png)
*Image2PDF*

> ## [What IFF?](http://archives.aros-exec.org/?function=showfile&file=document/misc/whatiff3.13.nodemo.lha) (v. 3.13)
> (autorzy: A. Vaisey, I. Sorensen, J. Scolieri, K. Saunders, R. O'Malley, T. Paul)

Magazyn o tematyce amigowej wydawany w formacie Amigaguide. Numer 13 - kwiecień 2024.

![What IFF?](/assets/img/whatiff13.png)
*What IFF? - kwiecień 2024*

> ## [IcarosFix](http://archives.aros-exec.org/?function=showfile&file=development/utility/icaros_2.3_fix.lha) (v. 2.3.4)
> (autorzy: Aros, Third Part Dev)

Icaros to swego czasu najpopularniejsza dystrybucja AROSa. Niestety od kilku lat nieaktualizowana. W tym archiwum znajduje się zestaw poprawek dla Icaros 2.3. W celu instalacji należy nadpisać pliki. Jest to nieoficjalna poprawka.
