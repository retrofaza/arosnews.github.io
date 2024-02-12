---
layout: post
title: AROS x86 - luty 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 0224
---

Styczeń stał pod znakiem wdrażania **nowej biblioteki C** w AROS x86. Ta zmiana ma za zadanie ułatwić życie przede wszystkim samym programistom AROSa. Wersja 32-bitowa będzie bardziej zgodna z wersją 64-bitową, więc utrzymanie dwóch linii rozwojowych stanie się łatwiejsze. W dłuższej perspektywie jest to także krok przybliżający AROSa do całkowitego przejścia na wersję 64-bit.

Aktualnie nadal trwają testy kompatybilności oprogramowania, niektóre rzeczy wymagają ponownego przekompilowania. Wszystko to sprawia, że nowego stabilnego builda możemy się spodziewać nie wcześniej niż pod koniec lutego. Jest za to duża szansa, że wraz z nim dostaniemy nieco odświeżoną wersję przeglądarki internetowej OWB.

Na blogu zamieściłem [tutorial na temat cross-kompilowania dla AROS pod Windows z WSL2](https://arosnews.github.io/jak-cross-kompilowac-aros-hosted-wsl/). Może będzie inspiracją dla nowych twórców oprogramowania? :)

Tradycją już staje się cykliczna ankieta na "Irytujący bug miesiąca". Tym razem społeczność zdecydowała, że dobrze byłoby rozszerzyć opcje w preferencjach sieci o możliwość łatwego włączenia tetheringu USB.

![Irytujący bug miesiąca](/assets/img/ibotm0224.jpg)
*Irytujący bug miesiąca - luty 2024*

Dzięki tetheringowi możemy korzystać z internetu na AROSie przy pomocy telefonu z androidem podłączonego kablem USB. Pozwala to cieszyć się siecią nawet na urządzeniach, które nie posiadają wspieranej karty sieciowej. Tethering USB był obecny w AROS od dawna, ale przez brak opcji do łatwej aktywacji wielu użytkowników nie miało o jego istnieniu pojęcia. Teraz dzięki **deadwood**'owi można odpowiednią opcję "wyklikać".

![Tethering USB](/assets/img/tethering.jpg)
*Tethering USB*

Jeśli chcesz mieć wpływ na kolejność naprawy błędów, zachęcam do zarejestrowania sie na forum i wzięcia udziału w [kolejnym głosowaniu](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1191&pid=3842).

Styczniowych nowości w AROS Archives nie ma zbyt wiele, ale jest jeden program, któremu zdecydowanie warto się przyjrzeć. **RNOEffects**, napisany w Hollywood i dostępny na wszystkie Amigi NG, rozwija się bardzo prężnie i z pewnością może być przydatny w codziennym użytkowaniu. Pełna lista nowych programów poniżej.

> ## [Feedback](http://archives.aros-exec.org/?function=showfile&file=demo/music/void-fb8-aros.i386-aros.zip) (nr 8)
> ## [Feedback](http://archives.aros-exec.org/?function=showfile&file=demo/music/void-fb11-aros.i386-aros.zip) (nr 11)
> (autor: Void)

Puni z demoscenowej grupy Void skompilował dla AROSa dwa music dyski swojej grupy. Są to Feedback wydanie 8 z 2019 r. oraz Feedback wydanie 11 z 2021 r. Oba music dyski zawierają po 10 utworów różnych autorów i zdecydowanie warto ich posłuchać. Jak zapewnia Puni wkrótce na AROS powinny pojawić się nowe produkcje od Void. Czekamy z niecierpliwością :)   

![Feedback](/assets/img/feedback11.jpg)
*Feedback 8 & 11*

> ## [Protrekkr 2](http://archives.aros-exec.org/?function=showfile&file=audio/tracker/ptk_v2.6.4.i386-aros.zip) (v. 2.6.4)
> (autor: Franck "hitchhikr" Charlet)

Protrekkr 2

![Protrekkr 2](/assets/img/ptk.jpg)
*Protrekkr 2*

> ## [BOH](http://archives.aros-exec.org/?function=showfile&file=game/action/boh.i386-aros.lha) (v. 2.3)
> (autor: Simone Bevilacqua "Saimo")

BOH

![BOH](/assets/img/boh.jpg)
*BOH*

> ## [Odyssey Web Browser](http://archives.aros-exec.org/?function=showfile&file=network/browser/owb-1.26.i386-aros.zip) (v. 1.26)
> (autorzy: WebKit Team, Fabien Coeurjoly, Krzysztof Śmiechowicz)

OWB

![OWB](/assets/img/owb126.jpg)
*Odyssey Web rowser*

> ## [WCS](http://archives.aros-exec.org/?function=showfile&file=graphics/raytrace/wcs.multi-aros.lha) (v. 2.031)
> (autor: Alexander Fritsch “Selco”)

World Construction Set

![WCS](/assets/img/wcs.jpg)
*WCS - World Construction Set*

