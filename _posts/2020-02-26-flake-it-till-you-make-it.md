---
layout: post
title: AROS x86 - marzec 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 0324
---



Nowości w AROS Archives z marca:

> ## [GLFW](http://archives.aros-exec.org/?function=showfile&file=development/library/glfw3_4.i386-aros.zip) (v.3.4)
> (autor: serk118)

GLFW to wieloplatformowa biblioteka Open Source do tworzenia aplikacji OpenGL, OpenGL ES i Vulkan. Zapewnia proste, niezależne od platformy API do tworzenia okien, kontekstów i powierzchni, odczytu danych wejściowych, obsługi zdarzeń itp.

![GLFW](/assets/img/glfw34.jpg)
*GLFW 3.4*

> ## [Raylib](http://archives.aros-exec.org/?function=showfile&file=development/library/raylib5.i386-aros.zip) (v. 5.0)
> (autor: serk118)

Raylib to prosta i łatwa w użyciu biblioteka do programowania gier wideo. Raylib jest silnie inspirowany biblioteką graficzną Borland BGI i frameworkiem XNA i szczególnie dobrze nadaje się do prototypowania, narzędzi, aplikacji graficznych, systemów wbudowanych i edukacji. Dzięki serk118 mamy tę bibliotekę na AROSie w najnowszej wersji 5.0.

Więcej na temat GLFW i Raylib dla AROS znajdziecie na stronie autora portu:
http://serk118.blogspot.com/

![Raylib](/assets/img/raylib5.png)
*Raylib 5*

> ## [Nano demo](http://archives.aros-exec.org/?function=showfile&file=demo/scene/nano.i386-aros.zip) (v. 1.2)
> ## [Arrakis demo](http://archives.aros-exec.org/?function=showfile&file=demo/scene/arrakis.i386-aros.zip) (v. 1.0)
> (autorzy: Kakiarts/TRBL)

Nano i Arrakis to porty dla AROSa dwóch dem wydanych oryginalnie na Apple iPod Nano G1. Porty skompilował dla AROSa Farox.

Demoscenowa grupa Kakiarts wydała Nano na demoparty EVOKE w 2006 r. Było ich pierwsze demo dla Apple iPod Nano G1. Dekadę później na demoparty Nordlicht 2016 grupa wydała drugie demo - Arrakis.

Porty dla Arosa używają SDL 1.2 do uruchomienia i działają z rozdzielczością nieco mniejszą niż 800x600 przy użyciu 4x upscalera zakodowanego przez oryginalnego autora. Ponieważ rozdzielczość używana przez iPoda to 176x132, więc na AROSie dema działają w rozdzielczości 704x528.

![Arrakis](/assets/img/arrakis.png)
*Dema Nano i Arrakis*

> ## [Feedback](http://archives.aros-exec.org/?function=showfile&file=demo/music/void-fb14-aros.i386-aros.zip) (nr 14)
> (autor: Void)

Ten music-pack zawiera większość zgłoszeń z 4-kanałowego Amiga music-compo na GERP 2023, demo-party zorganizowanym w Szwecji w styczniu 2023 roku. W porównaniu z packami nr 10 i 11 prezentowanymi w zeszłym miesiącu, wydanie nr 14 posiada także nową oprawę graficzną.

![Feedback](/assets/img/fb14.png)
*Feedback nr 14*


> ## [Bars & Pipes](http://archives.aros-exec.org/?function=showfile&file=audio/edit/barsnpipesaros.lha) (v. 1.0)
> ## [Bars & Pipes Dev_Tools](http://archives.aros-exec.org/?function=showfile&file=audio/edit/bp_dev_tools_accessories.zip) (v. 1.0)
> (autorzy: Blue Ribbon, Alfred Faust)

Bars & Pipes to sekwencer MIDI o bardzo kreatywnych możliwościach. Wrzucając narzędzia do Pipelines, można łatwo eksperymentować bez wprowadzania trwałych zmian w nagranym utworze.

Po tym, jak Franck Charlet - jeden z głównych deweloperów AROS - zadał sobie trud napisania sterownika, który jest łącznikiem między camd.library i camdusbmidi.class stosu USB Poseidon, Alfred Faust ukończył implementację Bars & Pipes na AROS-ie. Sterownik jest pierwszym, który jest naprawdę dobrze funkcjonującym MIDI dla AROS-a. Zawsze działa z JEDNYM interfejsem MIDI. Może on jednak mieć kilka portów - do 16. Teoretycznie, z 16-portowym interfejsem USB-MIDI, można zaadresować 16x16 = 256 niezależnych kanałów MIDI (instrumentów).

Alfred Faust zintegrował tę nową opcję z Bars & Pipes dla AROS. Dostępnych jest 16 nowych niezależnych narzędzi MIDI-IN i MIDI-OUT. Udało się zaimplementować 138 narzędzi (w tym 32 narzędzia MIDI) i 1 akcesorium dla AROS-a. Do implementacji wykorzystana została najnowsza wersja dystrybucji AROSone z AROS w wersji Build ABI_V0 z 30 stycznia 2024 roku.

Archiwum Bars & Pipes zawiera również wszystkie wymagane pliki:
- pliki programu (BarsnPipes, narzędzia, akcesoria, 64-kolorowy interfejs itp.)
- nowe pliki systemowe (camd.library, camdusbmidi.class, usbmidi - nowy sterownik)
- różne czcionki dla programu
- wiele instrukcji, w tym instrukcje dla Bars&Pipes Pro 2.5 Pro

![Bars&Pipes](/assets/img/barspipes.jpg)
*Bars & Pipes*

> ## [IcarosFix](http://archives.aros-exec.org/?function=showfile&file=utility/misc/icarosfix.zip) (v. 2.3.2)
> (autorzy: Aros, Third Part Dev)

Icaros to swego czasu najpopularniejsza dystrybucja AROSa. Niestety od kilku lat nieaktualizowana. W tym archiwum znajduje się zestaw poprawek dla Icaros 2.3. W celu instalacji należy nadpisać pliki. Jest to nieoficjalna poprawka.

![IcarosFix](/assets/img/icarosfix.jpg)
*IcarosFix - Małe poprawki dla Icaros v2.3*
