---
layout: post
title: AROS x86 - styczeń 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 0124
---

W grudniu system AROS doczekał się wielu ciekawych zmian i ulepszeń, które zwiększają jego funkcjonalność i wydajność. Najważniejszą nowością jest wydanie przez **deadwood**'a nowej wersji bazowej 32-bitowego systemu dla x86 (ABIv0), która wprowadza blisko 1000 zmian od kilku programistów AROS, w tym ulepszenia wsparcia sprzętowego i pulpitu Wanderer, aktualizacje kilku bibliotek oraz wiele poprawek błędów. 

{: .box-success}
Aby pobrać ISO i zapoznać się z pełną listą zmian, odwiedź:  
[https://github.com/deadw00d/AROS/releases/tag/ABIv0_20211128-1](https://github.com/deadw00d/AROS/releases/tag/ABIv0_20211128-1)

Wydanie nowej wersji bazowej zaowocowało niemal natychmiast pojawieniem się zaktualizowanych dystrybucji. Wyszedł Tiny AROS v3.0 oraz AROS One v2.3.

![AROS One v2.3](/assets/img/arosone23.jpg)
*AROS ONE v2.3*

{: .box-success}
Pełna lista zmian dla AROS One v2.3:  
[https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1124&pid=3217#post_2876](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1124&pid=3217#post_2876)

W związku z ogromną ilością zmian nie jest wskazane nadpisywanie starego systemu nowym. Należy zainstalować nowy system "na czysto". Najlepiej na jednym z [rekomendowanych sprzętów](https://en.wikibooks.org/wiki/Aros/Platforms/x86_Complete_System_HCL#Recommended_hardware).

W grudniowej ankiecie na "Irytujący bug miesiąca" wybrany został problem ze zmianą nazwy pod Wandererem.

![Irytujący bug miesiąca](/assets/img/ibotm1223.jpg)
*Irytujący bug miesiąca - grudzień 2023*

Oczywiście bug został załatany przez **deadwooda** priorytetowo, a na styczeń pojawiła się już nowa ankieta. Zachęcamy do zarejestrowania sie na forum i wzięcia udziału w kolejnym głosowaniu.

Trwają już też prace nad kolejnym buildem ABIv0. Najważniejszą zmianą ma być przejście na nową bibliotekę C. Krok ten będzie wymagał ponownego przetestowania dużej części oprogramowania, więc, jeżeli masz ochotę, możesz pomóc w testach. Testowy build znajdziesz [w tym wątku](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1171&rowstart=0).

Na koniec jak zwykle nowości z AROS Archives. W tym miesiącu pojawiło się kilkanaście nowych pozycji, więc jest się czym bawić :) Poniżej szczegółowa lista.

> ## [Worm Wars](http://archives.aros-exec.org/?function=showfile&file=game/action/wormwars.i386-aros.zip) (v. 9.34)
> (autor: James Jacobs)

Jest to wersja AROS gry Worm Wars, darmowej gry zręcznościowej autorstwa Jamesa Jacobsa z Amigan Software. Funkcje obejmują: 37 typów obiektów, 37 typów stworzeń, 13 typów bonusowych poziomów, zintegrowany edytor poziomów, do 4 robaków, kontrola ludzka lub komputerowa nad wszystkimi robakami, zapisywane tabele najlepszych wyników, wsparcie podwójnej klawiatury, opcja tasowania poziomów, czułość trybu ekranowego, wsparcie lokalne, kod źródłowy, uruchamianie na własnym lub publicznym ekranie, itp.

Muzyka i joysticki nie są obecnie obsługiwane przez port AROS.

![Pintor Web](/assets/img/wormwars.jpg)
*Worm Wars*

> ## [Sacrificio Pagano](http://archives.aros-exec.org/?function=showfile&file=utility/misc/sacrificiopagano.lha) (v. 2.10)
> (autor: Juan Carlos Herrán Martín)

Prosty programik dla wierzących w magię ;) Umożliwia skonfigurowanie własnego ołtarzyka na ekranie komputera, co ma ułatwiać oddawanie się magicznym praktykom.

Zmiany w wersji 2.10 (02-01-2024):

- Nowa grafika (oryginalna wykonana z pomocą IA).
- Nowe darmowe czcionki.
- Drobne ulepszenia.
- Teraz program ma pogańskie tapety na pogański pulpit.

![Sacrificio Pagano](/assets/img/pagano210.jpg)
*Sacrificio Pagano*

> ## [Icon Drop](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/icondropx_12-29-23.i386-aros.zip) (v. 1.02)
> (autor: Mike R.)

Icon Drop używa małego i prostego GUI GadTools do zapisywania obrazów ikon do nowej ikony docelowej.

![Icon Drop](/assets/img/icondrop102.jpg)
*Icon Drop*

> ## [New Colored Disks](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/new_colored_disks.zip) (v. 1.0)
> ## [New Flash Disk Icons](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/new_flash_disk_icons.zip) (v. 1.0)
> ## [New Floppy Icons](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/new_floppy_icons.zip) (v. 1.0)
> ## [New Ram Disk Icons](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/new_ram_disk_icons.zip) (v. 1.0)
> (autor: Mike R.)

Zestawy nowych ikonek w stylu Kens Icons v4.

![Set of New Icons](/assets/img/newicons.jpg)
*Set of New Icons*

> ## [iConecta](http://archives.aros-exec.org/?function=showfile&file=network/misc/iconecta.lha) (v. 5.20)
> (autor: Juan Carlos Herrán Martín)

Mały i prosty program do testowania połączenia internetowego.

Zmiany w wersji 5.20:
- Nowa skórka: Cyborg.
- Nowe czcionki.
- Naprawiono drobne błędy.

![iConecta](/assets/img/iconecta52.jpg)
*iConecta*

> ## [WhatIFF](http://archives.aros-exec.org/?function=showfile&file=document/misc/whatiff2.12.lha) (v. 2.12)
> (autorzy: I. Sorensen, J. Scolieri, K. Saunders, R. O'Malley, and T. Paul)

Magazyn o tematyce amigowej wydawany w formacie Amigaguide. Numer 12 - Grudzień 2023.

![WhatIFF](/assets/img/whatiff212.jpg)
*WhatIFF*

> ## [ZoomIt](http://archives.aros-exec.org/?function=showfile&file=utility/misc/zoomit.i386-aros.lha) (v. 1.3)
> (autor: Stefan Blixth)

ZoomIT jest prostą aplikacją powiększającą opartą na MUI.

Zmiany w wersji 1.3:
- Usunięto wymagania dla CyberGraphX (będzie działać nawet na nie-RTG miejmy nadzieję).
- Dodano tłumaczenie na język turecki (dzięki Serkan Dursun).
- Dodano tłumaczenie na język hiszpański (dzięki Dámaso Domínguez).
- Usunięto tryb skali
- Usunięto tryb kolorów
- Usunięto powiększenia powyżej 1000%

![ZoomIt](/assets/img/zoomit.jpg)
*ZoomIt*

> ## [ZuneARC](http://archives.aros-exec.org/?function=showfile&file=utility/archive/zunearc.i386-aros.zip) (v. 1.6)
> (autor: Yannick Erb)

Interfejs Zune dla archiwizatorów.

![ZuneARC](/assets/img/zunearc.jpg)
*ZuneARC*

> ## [AmiTechGazette](http://archives.aros-exec.org/?function=showfile&file=utility/filetool/omanko.lha) (Nr 6)
> (autor: Eric Schwharz)

AMI Tech-Gazette to publikacja elektroniczna, której celem jest dostarczenie użytkownikom doświadczenie podobne do klasycznego biuletynu lokalnej grupy użytkowników komputerów, z osobistym, nie do końca profesjonalnym akcentem, obejmującym Amigę i jej krewnych (OS4, MorphOS, AROS, Apollo i nie tylko!) z okazjonalnym odchyleniem do gier, zabawek i życia w ogóle.

![AmiTechGazette](/assets/img/amitech6.jpg)
*AmiTechGazette*

> ## [AstralGame](http://archives.aros-exec.org/?function=showfile&file=utility/misc/astralgame.lha) (v. 4.0)
> (autor: Juan Carlos Herrán Martín)

Ten ezoteryczny program pozwala ci odkryć tajemnice swojej osobowości i związku z naturą. Dowiesz się, jakie znaki zodiaku astralnego, chińskiego, majów haab i tzolkin oraz celtyckiego odpowiadają twojej dacie urodzenia. Poznasz też swoją magiczną liczbę osobistą, która ma wpływ na twoje życie. Program pokazuje ci również fazę księżyca, która jest przydatna do sadzenia nasion, oraz celtycko-wiccańskie święta lub sabaty, które są związane z cyklem przyrody. Ponadto, informuje cię o różnych wydarzeniach, takich jak Boże Narodzenie, pory roku i wiele innych.

Zmiany w wersji 4.00:
- Okno programu jest teraz większe, z rozdzielczością 640x480 pikseli.
- Narzędzie jest teraz bardziej mroczne i poważne.
- Skompilowane z Hollywood 10.0.
- Nowa grafika stworzona z pomocą IA.
- Naprawiono duży błąd z obliczaniem faz księżyca.

![AstralGame](/assets/img/astral.jpg)
*AstralGame*

> ## [kensV4_Drawer_Games](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/drawer_games_unofficial_kensv4.zip) (v. 1.3)
> (autor: amiwell79)

Nieoficjalne ikony szuflad dla gier w stylu kens v4.

*Kens v4 to zestaw ikon dla Amigi, które mają dwa formaty PNG: jeden dla ekranów AGA, a drugi dla ekranów RTG. Są one inspirowane ikonami AmigaOS4, ale mają własny charakter i kolorystykę. Autor tych ikon to Ken Lester, który jest znanym grafikiem w świecie Amigi.*

![kensV4_Drawer_Games](/assets/img/kenv4.jpg)
*kensV4_Drawer_Games*

> ## [Apng](http://archives.aros-exec.org/?function=showfile&file=development/library/apng_amiga.lha) (v. 1.3)
> (autor: Andreas Falkenhahn)

Ta wtyczka umożliwia Hollywood ładowanie i zapisywanie animacji w formacie APNG (Animated Portable Network Graphics). Wielką zaletą formatu APNG jest to, że obsługuje on animacje wykorzystujące przezroczystość kanału alfa. Ani format IFF ANIM ani GIF ANIM nie obsługują przezroczystości kanału alfa. Ponadto, APNG może również obsługiwać dane ramek w prawdziwym kolorze. Formatem konkurencyjnym dla APNG jest MNG, ale APNG został wybrany, ponieważ obsługuje go więcej aplikacji.

Zmiany w wersji 1.3:
- Poprawka: Pliki APNG bez kanału przezroczystości nie były poprawnie ładowane (zgłoszone przez Juan Carlos Herrán Martín).
