---
layout: post
title: AROS x86 - listopad 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 1124
---

Mija rok odkąd zacząłem prowadzić bloga opisującego nowości w AROSie. Moje pierwsze kroki z systemem kilka lat temu nie były zbyt udane. Jednak z czasem zacząłem przekonywać się do niego coraz bardziej. Można powiedzieć, że przeszedłem długą drogę od "umiarkowanego sceptyka" do człowieka zakochanego po uszy w tym rozwiązaniu :) Obecnie, dla mnie osobiście, AROS jest najlepszą Amigą NG. Śledzenie jego rozwoju i testowanie nowych elementów daje mi dużo satysfakcji. Zachęcam was do tego samego! 

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



Pozostałe nowości w AROS Archives:  

> ## [FastTracker2 Clone](https://archives.aros-exec.org/?function=showfile&file=audio/tracker/ft2clone166.i386-aros.zip) (v. 1.66)
> (autor:	Olaf Sørensen, port by Farox & Deremon)

FastTracker2 Clone

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

Sacrificio Pagano

![Sacrificio Pagano](/assets/img/1124/spagano.jpg)
*Sacrificio Pagano*

> ## [UHCTools](https://archives.aros-exec.org/?function=showfile&file=utility/misc/uhctools.i386-aros.lha) (v. 1.8)
> (autorzy: Patrik Axelsson, David Eriksson)

Jest to zbiór programów i skryptów dla komputerów Amiga i ich pochodnych, aby uprościć codzienne użytkowanie i uczynić Amigę bardziej niezależną.

