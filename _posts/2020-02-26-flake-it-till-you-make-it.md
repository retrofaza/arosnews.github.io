---
layout: post
title: AROS x86 - listopad 2023
subtitle: podsumowanie miesiąca
lang: pl
ref: 1123
---



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

AstralGame

![AstralGame](/assets/img/astral.jpg)
*AstralGame*

> ## [kensV4_Drawer_Games](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/drawer_games_unofficial_kensv4.zip) (v. 1.3)
> (autor: amiwell79)

kensV4_Drawer_Games

![kensV4_Drawer_Games](/assets/img/kensv4.jpg)
*kensV4_Drawer_Games*

> ## [Black_White Icons](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/black_white_drawers.zip) (v. 1.0)
> (autor: Mike R.)

Black_White Icons

![Black_White Icons](/assets/img/blackwhite.jpg)
*Black_White Icons*

> ## [Icon Drop](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/icondrop_12-18-23.i386-aros.zip) (v. 1.0)
> (autor: Mike R.)

IconDrop

![Icon Drop](/assets/img/icondrop.jpg)
*Icon Drop*

> ## [Apng](http://archives.aros-exec.org/?function=showfile&file=development/library/apng_amiga.lha) (v. 1.3)
> (autor: Andreas Falkenhahn)

Ta wtyczka umożliwia Hollywood ładowanie i zapisywanie animacji w formacie APNG (Animated Portable Network Graphics). Wielką zaletą formatu APNG jest to, że obsługuje on animacje wykorzystujące przezroczystość kanału alfa. Ani format IFF ANIM ani GIF ANIM nie obsługują przezroczystości kanału alfa. Ponadto, APNG może również obsługiwać dane ramek w prawdziwym kolorze. Formatem konkurencyjnym dla APNG jest MNG, ale APNG został wybrany, ponieważ obsługuje go więcej aplikacji.

Zmiany w wersji 1.3:
- Poprawka: Pliki APNG bez kanału przezroczystości nie były poprawnie ładowane (zgłoszone przez Juan Carlos Herrán Martín).
