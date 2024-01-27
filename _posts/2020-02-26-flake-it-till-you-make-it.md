---
layout: post
title: AROS x86 - styczeń 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 0124
---

Styczeń stał pod znakiem wdrażania **nowej biblioteki C** w AROS x86. Ta zmiana ma za zadanie ułatwić życie przede wszystkim samym programistom AROSa. Wersja 32-bitowa będzie bardziej zgodna z wersją 64-bitową, więc utrzymanie dwóch linii rozwojowych stanie się łatwiejsze. W dłuższej perspektywie jest to także krok przybliżający AROSa do całkowitego przejścia na wersję 64-bit.

Aktualnie nadal trwają testy kompatybilności oprogramowania, niektóre rzeczy wymagają ponownego przekompilowania. Wszystko to sprawia, że nowego stabilnego builda możemy się spodziewać nie wcześniej niż pod koniec lutego. Jest za to duża szansa, że wraz z nim dostaniemy nieco odświeżoną wersję przeglądarki internetowej OWB.

Na blogu zamieściłem [tutorial o przygotowaniu nośnika USB z ABIv0](https://arosnews.github.io/jak-przygotowac-pendrive-usb-aros/). Robi się to trochę inaczej niż w innych systemach, więc wierzę, że ta instrukcja będzie przydatna dla początkujących.

W styczniowej ankiecie na "Irytujący bug miesiąca" wybrany został problem z zapisem ustawień parametrów rozruchu.

![Irytujący bug miesiąca](/assets/img/ibotm0124.jpg)
*Irytujący bug miesiąca - styczeń 2024*

Bug został już poprawiony, w najnowszym buildzie można konfigurować parametry rozruchu w preferencjach. Jeśli chcesz mieć wpływ na kolejność naprawy błędów, zachęcam do zarejestrowania sie na forum i wzięcia udziału w [kolejnym głosowaniu](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1191&pid=3842).

Styczniowych nowości w AROS Archives nie ma zbyt wiele, ale jest jeden program, któremu zdecydowanie warto się przyjrzeć. **RNOEffects**, napisany w Hollywood i dostępny na wszystkie Amigi NG, rozwija się bardzo prężnie i z pewnością może być przydatny w codziennym użytkowaniu. Pełna lista nowych programów poniżej.

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

> ## [Image2PDF](http://archives.aros-exec.org/?function=showfile&file=office/dtp/image2pdf.i386-aros.lha) (v. 2.50)
> (autor: Bernd Assenmacher)

Małe narzędzie do konwersji obrazów do formatu PDF. Przede wszystkim służy do konwertowania skanów wykonanych np. za pomocą Scandal lub Scanquix do dokumentów PDF w określonych formatach wyjściowych, takich jak A3, A4, A5, Legal, Letter lub ImageSize, ale może być również używane do konwersji innych plików graficznych.

Zmiany w wersji 2.50:
- zmieniono GUI, aby było bardziej intuicyjne
- stopiono docelowe requestery do jednego docelowego requestera
- dodano źródłowy requester plików PDF do GUI dla PDF2Image i PDF2PDF
- dodano funkcję "Image2Image" do zmiany formatu obrazów
- dodano funkcję "scan file(s)" do określania atrybutów obrazu(ów)
- dodano funkcję "rem (dup)" do usuwania zduplikowanych wpisów z widoku listy
- dodano funkcję "check" do sprawdzania, czy podane obrazy są prawidłowe do
  przetwarzania i czyszczenia widoku listy z nieprawidłowych plików graficznych    
- dodano możliwość skalowania obrazów do ustalonego rozmiaru
- dodano więcej formatów dla Image2PDF (B4, B5, US, Executive, Comm10)
- instalator automatycznie ustawia teraz system operacyjny (dzięki Daniel ;-))
- klawisz F1 otwiera teraz również plik przewodnika jako pomoc
- zaktualizowane podpowiedzi
- zoptymalizowane komunikaty wyjściowe
- naprawiono błąd, w którym "odczyt źródła" czasami nie działał poprawnie 
- wiele usprawnień "pod maską" ... ;-)

![Image2PDF](/assets/img/image2pdf25.jpg)
*Image2PDF*

> ## [RNOEffects](http://archives.aros-exec.org/?function=showfile&file=graphics/edit/rnoeffects.i386-aros.lha) (v. 2.0)
> (autor: jPV^RNO)

RNOEffects to prosty program do przetwarzania obrazów z naciskiem na dobre opcje konwersji wsadowej, efekty oparte na kanale alfa i edycję pikseli.

Zmiany w wersji 2.0:
- Dodano narzędzie "Edytor pikseli" z konfigurowalnymi opcjami rysowania pikseli dla lewego, środkowego i prawego przycisku myszy
- Dodano narzędzie "Color picker" do wyświetlania informacji o kolorze pod wskaźnikiem myszy oraz do tymczasowego wybierania i przechowywania wielu wartości kolorów
- Dodano narzędzie "Selektor obszaru", które może być używane do stosowania określonych efektów na ograniczonym obszarze obrazu
- Dodano narzędzie "Przybornik", aby ograniczyć korzystanie z menu rozwijanego.
- Dodano obsługę zapisywania obrazów w trybie palety (1-8 bitów), opcjonalnie z 16 predefiniowanymi paletami, w tym paletą MagicWB.
- Palety mogą być zapisywane w formatach IFF, ILBM, RGB32, LoadRGB4 i LoadRGB32.
- Obrazy palety mogą być zapisywane jako duże dane
- Dane obrazu Chunky i oddzielne palety mogą być zapisywane jako kod źródłowy C.
- Dodano opcję użycia mapy krycia do częściowego zastosowania efektu (działa z efektami Blur, Contrast, Draw/Brush, Gamma, Modulate, Monochrome i Tint)
- Dodano efekty "Klucz chrominancji" i "Klucz luminescencji", aby zakresy kolorów były przezroczyste.
- Konwertowane wsadowo obrazy mogą być zapisywane jako wideo
- Dodano obsługę MagicWB dla zapisywania ikon
- Dodano informacje o stanie programu w tytule okna
- Dodano przycisk Cofnij w oknach efektów
- Skróty klawiszy funkcyjnych mogą być używane do zapisywania obrazów w kilku formatach
- Dodano opcję zamiany obrazu głównego z obrazem bufora.
- Efekt mapy krycia może używać obrazu bufora jako mapy krycia.
- Dodano opcję odwracania efektu mapy krycia.
- Dodano przykłady map krycia w katalogu OpacityMaps
- Zmieniono nazwę efektu "Zmniejsz alfa" na "Zmień alfa" i dodano opcję usunięcia całego kanału alfa z obrazu
- Obrazy tła mogą być wyśrodkowane w efekcie tła
- Dodano opcję wyczyszczenia bieżącego obrazu.
- Bufor cofania nie był inicjowany podczas ładowania obrazu przy uruchamianiu.
- Naprawiono wybieranie kolorów przy skalowanych obrazach
- Poprawiono efekty Węgiel i Krawędź dla obrazów z przezroczystością.
- Lepsza zmiana rozmiaru okna podczas ładowania obrazów
- Pomijanie operacji klawisza strzałki, jeśli jednocześnie naciśnięto klawisz polecenia, aby nie wpływać na sterowanie wskaźnikiem myszy za pomocą klawiatury.
- Uporządkowanie efektów w menu według kategorii
- Dodano wtyczki JPEG2000, PCX i TIFF
- Dodano obsługę zapisywania obrazów w formatach JPEG2000 i TIFF
- Wybór konkretnego obrazu/stanu do załadowania ikony z wieloma obrazami
- Dodano ustawienie ładowania właściwości ikon i używania ich w opcjach zapisywania ikon
- Pliki mogą być przeciągane i upuszczane na listę plików konwersji wsadowej
- Okna narzędzi otwierają się podczas uruchamiania, jeśli były otwarte podczas zapisywania ustawień
- Inne drobne poprawki

![RNOEffects](/assets/img/rnoeffects20.jpg)
*RNOEffects*
