---
layout: post
title: AROS x86 - listopad 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 1124
---

Minął już rok, odkąd zacząłem prowadzić bloga poświęconego nowościom w świecie AROSa. Moje pierwsze doświadczenia z tym systemem, kilka lat temu, nie należały do najbardziej udanych. Z czasem jednak coraz bardziej przekonywałem się do jego możliwości. Można powiedzieć, że przeszedłem długą drogę – od umiarkowanego sceptyka do osoby absolutnie zakochanej w tym rozwiązaniu :) Dziś AROS to dla mnie najlepsza wersja Amigi NG. Śledzenie jego rozwoju i testowanie nowych funkcji sprawia mi ogromną satysfakcję. Serdecznie zachęcam was, byście sami spróbowali!

W listopadzie dostaliśmy nowe wydanie 64-bitowej wersji bazowej systemu (ABIv11 20241102-1). Ta nowa wersja wprowadza wiele ulepszeń do Wanderera i Zune, a także ponad 60 poprawek błędów, które zostały wdrożone od marca 2023 roku. **Aktualnie do pobrania jest wersja przeznaczona do uruchomienia w środowisku linuks hosted. Wersji działającej na natywnym sprzęcie możemy spodziewać się najwcześniej w przyszłym roku.**

Pełną listę zmian można znaleźć tutaj:  
[https://axrt.org/release-notes?id=aros-abiv11-20241102-1](https://axrt.org/release-notes?id=aros-abiv11-20241102-1)  

Nową wersję można pobrać z:  
[https://github.com/deadwood2/AROS/releases/tag/ABIv11_20241102-1](https://github.com/deadwood2/AROS/releases/tag/ABIv11_20241102-1)  
[https://axrt.org/downloads-aros-64bit](https://axrt.org/downloads-aros-64bit)  

Jednocześnie wydana została **64-bitowa wersja przeglądarki internetowej Odyssey w wersji 2.1** (wymaga do działania najnowszej wersji systemu). W porównaniu z wydaną niedawno wersją 32-bit, wersja 64-bitowa oferuje akcelerację JavaScript za pomocą kompilatora JIT dla większej wydajności, a także możliwości wykorzystania wielu rdzeni procesora podczas uruchamiania w AxRuntime.
  
<div class="embed-container">
<iframe width="700" height="480" src="https://www.youtube.com/watch?v=haT1RsF7ZyM" frameborder="0"> </iframe>
</div>  

Jeśli chcesz wypróbować Odyssey, przygotowaliśmy kilka samouczków:  

Korzystanie z Odyssey w systemie AROS linux:  
[https://arosnews.github.io/OWB-aros-linux-hosted/](https://arosnews.github.io/OWB-aros-linux-hosted/)

Korzystanie z Odyssey w systemie Windows:  
[https://arosnews.github.io/OWB-axrt-wsl2/](https://arosnews.github.io/OWB-axrt-wsl2/)

Korzystanie z Odyssey pod Linuksem:  
[https://arosnews.github.io/OWB-axrt-linux/](https://arosnews.github.io/OWB-axrt-linux/)

Na forum Aros World Deadwood przedstawił zaktualizowany [plan rozwoju](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1114&rowstart=20#post_6834) AROSa. Jak się dowiadujemy, nacisk zostanie położony na przyspieszenie synchronizacji źródeł wersji 32-bitowej (ABIv0) z najnowszą wersją 64-bitową systemu (ABIv11). Dalszy plan pozostaje niezmieniony, więc możemy się spodziewać emulatora 32-bit dla ABIv11 i AxRuntime (którego prototyp już działa!), a następnie wydania natywnej wersji systemu 64-bit.  

Nastąpiła aktualizacja używanego w AROSie kompilatora GCC. Dzięki ciężkiej pracy @thatguywiththekids domyślny kompilator został zaktualizowany z GCC 6.5.0 do GCC 10.5.0 zarówno dla x86_64, jak i m68k!

Pozostałe nowości w AROS Archives:  

> ## [FastTracker2 Clone](https://archives.aros-exec.org/?function=showfile&file=audio/tracker/ft2clone166.i386-aros.zip) (v. 1.66)
> (autor:	Olaf Sørensen, port by Farox & Deremon)

Legendarny demoscenowy tracker, którego główną innowacją było wprowadzenie formatu plików XM (Extended Module). Teraz dzięki wysiłkowi Faroxa i Deremona mam także jego port na AROSie. 

![FastTracker2 Clone](/assets/img/1124/ft2clone.png)
*FastTracker2 Clone*

> ## [SilkRAW](https://archives.aros-exec.org/?function=showfile&file=graphics/misc/silkraw_aros.lha) (v. 3.0)
> (autor:	Domenico Lattanzi)

SilkRAW to program umożliwiający pracę z plikami RAW generowanymi przez lustrzanki cyfrowe, działający jako interfejs do programu dcRAW napisanego przez Dave'a 
Coffina (Należy ściągnąć [dcRAW](https://archives.aros-exec.org/?function=showfile&file=graphics/convert/dcraw.i386-aros.zip) i umieścić go w szufladzie programu SilkRAW). 

Funkcje:  
- Eksport miniatur, pojedynczych plików RAW lub grup, z metadanymi możliwości wyodrębniania i obracania 
- 25 obsługiwanych opcji dcRAW
- Przetwarzanie wsadowe plików RAW z zapisem w formatach TIFF, PPM, JPG, PNG, ILBM
- Dalsze przetwarzanie poza dcRAW  

![SilkRAW](/assets/img/1124/silkraw.png)
*SilkRAW*

> ## [Sacrificio Pagano](https://archives.aros-exec.org/?function=showfile&file=utility/misc/sacrificiopagano.lha) (v. 3.0)
> (autor: Juan Carlos Herrán Martín)

Prosty programik dla wierzących w magię. Umożliwia skonfigurowanie własnego ołtarzyka na ekranie komputera, co ma ułatwiać oddawanie się magicznym praktykom.

W wersji 3.0 mamy przede wszystkim poprawioną warstwą wizualną programu.


![Sacrificio Pagano](/assets/img/1124/spagano.jpg)
*Sacrificio Pagano*

> ## [UHCTools](https://archives.aros-exec.org/?function=showfile&file=utility/misc/uhctools.i386-aros.lha) (v. 1.8)
> (autorzy: Patrik Axelsson, David Eriksson)

Jest to zbiór programów i skryptów dla komputerów Amiga i ich pochodnych, aby uprościć codzienne użytkowanie i uczynić Amigę bardziej niezależną.

