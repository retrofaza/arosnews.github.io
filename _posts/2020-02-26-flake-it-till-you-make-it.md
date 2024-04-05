---
layout: post
title: AROS x86 - kwiecień 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 0424
---



![Irytujący bug miesiąca](/assets/img/ibotm0324.png)
*Irytujący bug miesiąca - marzec 2024*

Jak zwykle zachęcam do wzięcia udziału w kolejnym głosowaniu. Tym razem dla uczczenia pół roku działalności ankiety czeka nas niespodzianka - aż dwa błędy zostaną wytypowane i naprawione :) [Link do aktualnej ankiety](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1228&pid=4744). 

Nowości w AROS Archives z kwietnia:

> ## [ScummVM](http://archives.aros-exec.org/?function=showfile&file=emulation/misc/scummvm-1.9.0-1.i386-aros.zip) (v.1.9.0)
> (autorzy: Max Horn, Eugene Sandulenko i wielu innych)

ScummVM

![ScummVM](/assets/img/scummvm.png)
*ScummVM 1.9.0*

> ## [ResidualVM](http://archives.aros-exec.org/?function=showfile&file=emulation/misc/residualvm-0.3.1-1.i386-aros.zip) (v. 0.3.1)
> (autorzy: Thomas Allen, Torbjorn Andersson i wielu innych)

ResidualVM

![ResidualVM](/assets/img/residualvm.png)
*ResidualVM*

> ## [ScummVM_Kens](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/scummvm_kens.lha) (v. 0.5)
> ## [ResidualVM-Kens](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/residualvm-kens.lha) (v. 0.5)
> (autor: amiwell79)

Nieoficjalne ikony szuflad w stylu Kens dla ScummVM, ResidualVM oraz gry Myst 3.

![Kens](/assets/img/kens.jpg)
*Zestaw ikon w stylu Kens*

> ## [ADoom3](http://archives.aros-exec.org/?function=showfile&file=game/fps/adoom3-1.5.3.i386-aros.zip) (v. 1.5.3)
> (autor: Nick "Kalamatee" Andrews)

ADoom 3

![ADoom3](/assets/img/adoom3.jpg)
*ADoom 3*


> ## [Bars & Pipes](http://archives.aros-exec.org/?function=showfile&file=audio/edit/barsnpipesaros.lha) (v. 1.0)
> ## [Bars & Pipes Dev_Tools](http://archives.aros-exec.org/?function=showfile&file=audio/edit/bp_dev_tools_accessories.zip) (v. 1.0)
> (autorzy: Blue Ribbon, Alfred Faust)

Bars & Pipes to sekwencer MIDI o bardzo kreatywnych możliwościach. Wrzucając narzędzia do Pipelines, można łatwo eksperymentować bez wprowadzania trwałych zmian w nagranym utworze.

Po tym, jak Franck Charlet - jeden z głównych deweloperów AROS - zadał sobie trud napisania sterownika, który jest łącznikiem między camd.library i camdusbmidi.class stosu USB Poseidon, Alfred Faust ukończył implementację Bars & Pipes na AROS-ie. Sterownik jest pierwszym, który jest naprawdę dobrze funkcjonującym MIDI dla AROS-a. Zawsze działa z JEDNYM interfejsem MIDI. Może on jednak mieć kilka portów - do 16. Teoretycznie, z 16-portowym interfejsem USB-MIDI, można zaadresować 16x16 = 256 niezależnych kanałów MIDI (instrumentów).

Alfred Faust zintegrował tę nową opcję z Bars & Pipes dla AROS. Dostępnych jest 16 nowych niezależnych narzędzi MIDI-IN i MIDI-OUT. Udało się zaimplementować 138 narzędzi (w tym 32 narzędzia MIDI) i 1 akcesorium dla AROS-a. Do implementacji wykorzystana została najnowsza wersja dystrybucji AROSone z AROS w wersji Build ABI_V0 z 30 stycznia 2024 roku.

Archiwum Bars & Pipes zawiera również wszystkie wymagane pliki:
- pliki programu (Bars & Pipes, narzędzia, akcesoria, 64-kolorowy interfejs itp.)
- nowe pliki systemowe (camd.library, camdusbmidi.class, usbmidi - nowy sterownik)
- różne czcionki dla programu
- wiele instrukcji, w tym instrukcje dla Bars & Pipes Pro 2.5

![Bars&Pipes](/assets/img/barspipes.png)
*Bars & Pipes*

> ## [IcarosFix](http://archives.aros-exec.org/?function=showfile&file=utility/misc/icarosfix.zip) (v. 2.3.3)
> (autorzy: Aros, Third Part Dev)

Icaros to swego czasu najpopularniejsza dystrybucja AROSa. Niestety od kilku lat nieaktualizowana. W tym archiwum znajduje się zestaw poprawek dla Icaros 2.3. W celu instalacji należy nadpisać pliki. Jest to nieoficjalna poprawka.
