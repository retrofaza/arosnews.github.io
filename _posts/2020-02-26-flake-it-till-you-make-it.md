---
layout: post
title: AROS x86 - grudzień 2023
subtitle: podsumowanie miesiąca
lang: pl
ref: 1223
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

> ## [Pintor Web](http://archives.aros-exec.org/?function=showfile&file=graphics/convert/pintorweb.lha) (v. 4.00)
> (autor: Juan Carlos Herrán Martín)

Łatwy w obsłudze program do edycji zdjęć wykorzystywanych w projektach stron internetowych. Umożliwia zmianę rozmiaru, obrót, stosowanie efektów wizualnych, dodawanie znaku wodnego lub logo marki, zapisywanie w różnych formatach.

Zmiany w najnowszej wersji:
- Kompilacja z ostatnią wersją Hollywood 10.0.
- Dodano nowe efekty wizualne.
- Nowa instrukcja PDF z przykładami i wskazówkami.

![Pintor Web](/assets/img/pintor.jpg)
*Pintor Web*

> ## [Image2PDF](http://archives.aros-exec.org/?function=showfile&file=office/dtp/image2pdf.i386-aros.lha) (v. 2.4)
> (autor: Bernd Assenmacher)

Małe narzędzie do konwersji obrazów do formatu PDF. Przede wszystkim służy do konwertowania skanów wykonanych np. za pomocą Scandal lub Scanquix do dokumentów PDF w określonych formatach wyjściowych, takich jak
A3, A4, A5, Legal, Letter lub ImageSize, ale może być również używane do konwersji innych plików graficznych.

Zmiany w wersji 2.4:
- dodano funkcję "PDF2Image" (nie działa z Aros)
- dodano funkcję "PDF2PDF" (nie działa z Aros) 
- dodano funkcję "Skalowanie" --> Image2PDF, gdy "ImageSize" jest ustawiony jako format
- dodano funkcję "Skalowanie" --> PDF2Image 
- dodano funkcję "Skalowanie" --> Image2NewSize
- dodano funkcję "Jakość" --> PDF2Image, gdy "JP(E)G" jest ustawione jako format
- zmieniono metodę zliczania plików podczas zapisywania obrazów 
- Skrypt instalacyjny kopiuje teraz ikony i obrazki (MorphOS, AmigaOS3/4 i Aros)
- Skrypt instalacyjny instaluje teraz AmiKit, jeśli został wybrany
- Skrypt instalacyjny tworzy teraz szufladę o nazwie "Image2PDF" w wybranym miejscu docelowym (MorphOS, AmigaOS3/4 i Aros)
- wprowadzono kilka kosmetycznych zmian w graficznym interfejsie użytkownika
- zaktualizowano przewodnik 
- naprawiono kilka drobnych błędów

![Image2PDF](/assets/img/image2pdf.jpg)
*Image2PDF*

> ## [Font Tester](http://archives.aros-exec.org/?function=showfile&file=utility/text/fonttester.lha) (v. 2.00)
> (autor: Juan Carlos Herrán Martín)

Font Tester to narzędzie do testowania czcionek zainstalowanych w systemie. Za jego pomocą możemy w łatwy sposób sprawdzić jak dana czcionka prezentuje się na tle obrazka lub tesktury.

Zmiany w wersji 2.0:
- Skompilowany z ostatnią wersją Hollywood 10.0.
- Nowa grafika w intro.

![Font Tester](/assets/img/fonttester.jpg)
*Font Tester*

> ## [XPDF-GUI](http://archives.aros-exec.org/?function=showfile&file=office/dtp/xpdf-gui.i386-aros.zip) (v. 1.1)
> (autor: Yannick Buchy)

Jest to nowy graficzny interfejs użytkownika stworzony za pomocą Hollywood dla XPDF Suite. Interfejs ten wykorzystuje polecenia XPDF: pdfinfo, pdfdetach, pdffonts, pdftohtml, pdfimages, pdftopng, pdftoppm, pdftops i pdftotxt. Należy je skopiować do szuflady Bin/. Interfejs ułatwia konwertowanie i wyodrębnianie tekstu i obrazów z plików PDF.

Zmiany w wersji 1.1:
- naprawiono: okno informacyjne nie było czyszczone w niektórych warunkach
- dodano ścieżkę docelową
- poprawiono ikonę ikonyfikacji
- teraz wybór operacji zachowuje ten sam stan. Na przykład po wybraniu opcji "Pobierz Informacje", gdy następnie wybierzesz inny pliki PDF to od razu uzyskasz informacje o nowym pliku PDF. To samo dotyczy opcji "Pobierz listę osadzonych plików" i "Pobierz listę używanych czcionek".
- dodano skróty klawiszowe

![XPDF-GUI](/assets/img/xpdfgui.jpg)
*XPDF-GUI*

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

> ## [Black_White Icons](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/black_white_drawers.zip) (v. 1.0)
> (autor: Mike R.)

W tym archiwum znajdują się oryginalne obrazy i gotowe ikony dla obu zestawów ikon: czarnego i białego. Każdy zestaw ikon (czarny i biały) zawiera trzy warianty neonowych niebieskich, zielonych i żółtych świecących obramowań.

![Black_White Icons](/assets/img/blackwhite.jpg)
*Black_White Icons*

> ## [Icon Drop](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/icondrop_12-18-23.i386-aros.zip) (v. 1.0)
> (autor: Mike R.)

Icon Drop używa małego i prostego GUI GadTools do zapisywania obrazów ikon do nowej ikony docelowej.

![Icon Drop](/assets/img/icondrop.jpg)
*Icon Drop*

> ## [Apng](http://archives.aros-exec.org/?function=showfile&file=development/library/apng_amiga.lha) (v. 1.3)
> (autor: Andreas Falkenhahn)

Ta wtyczka umożliwia Hollywood ładowanie i zapisywanie animacji w formacie APNG (Animated Portable Network Graphics). Wielką zaletą formatu APNG jest to, że obsługuje on animacje wykorzystujące przezroczystość kanału alfa. Ani format IFF ANIM ani GIF ANIM nie obsługują przezroczystości kanału alfa. Ponadto, APNG może również obsługiwać dane ramek w prawdziwym kolorze. Formatem konkurencyjnym dla APNG jest MNG, ale APNG został wybrany, ponieważ obsługuje go więcej aplikacji.

Zmiany w wersji 1.3:
- Poprawka: Pliki APNG bez kanału przezroczystości nie były poprawnie ładowane (zgłoszone przez Juan Carlos Herrán Martín).
