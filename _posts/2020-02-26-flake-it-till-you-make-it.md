---
layout: post
title: AROS x86 - maj 2025
subtitle: podsumowanie miesiąca
lang: pl
ref: 0525
---

W tym miesiącu wydany został **[AROS Portable](https://arosnews.github.io/aros-portable)**. Umożliwia uruchomienie i wypróbowanie AROSa na praktycznie każdym nowoczesnym komputerze PC. To rozwiązanie (mające pod spodem linuksa i AROS One) daje możliwość łatwego startu z AROSem bez potrzeby inwestowania w dedykowany sprzęt, czy uruchamiania samodzielnie maszyn wirtualnych. Wystarczy nagrać obraz na pendrive i można zacząć używać AROSa - prościej już się nie da! Z pierwszych komentarzy wiemy, że rozwiązanie spotkało się z ciepłym przyjęciem. Dziękujemy redakcji **The Register** za [artykuł opisujący AROS Portable](https://www.theregister.com/2025/05/22/aros_live), dzięki któremu informacja o AROSie dotarła do wielu ludzi poza amigową sceną.  

Kolejną świetną wiadomością jest rozpoczęcie przez **Kalamatee** prac nad przeportowaniem dla AROSa kompilatora GCC w wersji 15. Nowszy kompilator umożliwi portowanie nowszego oprogramowania, między innymi Webkita z którego korzysta przeglądarka OWB.

Skoro jesteśmy przy Odyssey Web Browser, to **Deadwood** udostępnił do testów betę nowej wersji przeglądarki dla systemu x86_64. Najnowsza beta jest oparta o silnik Webkit 2.32.4 i poprawia obsługę wielu stron. Dostajemy między innymi lepsze renderowanie Githuba, możliwość przeglądania wiadomości w GMailu, możliwość zalogowania się na Discord. Wersję testową można [pobrać stąd](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1175&rowstart=40#post_8342).

Tymczasem garść nowości z AROS Archives:

> ## [Protrekkr](https://archives.arosworld.org/?function=showfile&file=audio/edit/protrekkr.x86_64-aros-v11.zip) (v. 2.8.3PRE) `x86_64`
> (autor:	Franck “hitchhikr” Charlet)

ProTrekkr to program trackerowy, który łączy w sobie syntezator programowy z tradycyjnym trackerem sampli, który może (głównie) służyć do tworzenia muzyki elektronicznej (np. psytrance, trance goa, hard acid, IDM, chip, techno, jungle itp.) do małych intro, dem lub gier.

Zmiany i nowości w wersji v2.8.3 PRE 2:

- Można teraz wybrać rozdzielczość trybu pełnoekranowego.
- Dodano 4 parametryzowalne filtry opóźnienia stereo.
- Nowe efekty:
  - 2D: Ustawianie typu filtra opóźnienia stereo.
  - 2E: Ustawienie odcięcia filtra opóźnienia stereo.
  - 2F: Ustawienie rezonansu filtra opóźnienia stereo.
- Zakres danych midi jest teraz poprawnie skalowany: dane wiersza FF będą wysyłane jako 127.
- Ptk wysyła teraz zdarzenia Midi start/cont/stop i Midi clock.
- Dodano 2 funkcje w sekwencerze do przesuwania pozycji w górę lub w dół.
- Globalne głośności kanałów są teraz używane również dla nut midi.
- Dodano funkcję sekwencera do ponownego mapowania/zamiany i zmiany numerów i wartości efektów.
- Naprawiono kilka błędów z funkcjami transpozycji nut.
- Przyspieszono śledzenie i odtwarzanie.
- Usunięto splajny, kanały mogą być teraz indywidualnie odszumiane (lub nie) z tego powodu dodano ten efekt:
  - 30: Kontrola siły odszumiania kanałów (informacje o parametrach można znaleźć w instrukcji).
- Zmieniono nazwę dystrybucji Mac OS 64 bit z ia64 na x86_64 (i x86 na x86_32).
- Naprawiono awarię podczas uruchamiania w niektórych wersjach systemu macOS.
- Wersja MorphOS jest teraz oficjalnie obsługiwana.

![Protrekkr](/assets/img/0525/protrekkr.jpg)
*Protrekkr*

> ## [Arrakis demo](https://archives.arosworld.org/?function=showfile&file=demo/scene/arrakis.x86_64-aros-v11.zip) (v. 1.0) `x86_64`
> ## [Nano demo](https://archives.arosworld.org/?function=showfile&file=demo/scene/nano.x86_64-aros-v11.zip) (v. 1.2) `x86_64`
> (autorzy: Kakiarts/TRBL)

Nano i Arrakis to porty dla AROSa dwóch dem wydanych oryginalnie na Apple iPod Nano G1. Porty skompilował dla AROSa **Farox** tym razem na platformę 64-bitową!

Demoscenowa grupa Kakiarts wydała Nano na demoparty EVOKE w 2006 r. Było ich pierwsze demo dla Apple iPod Nano G1. Dekadę później na demoparty Nordlicht 2016 grupa wydała drugie demo - Arrakis.

Porty dla AROSa używają SDL 1.2 do uruchomienia i działają z rozdzielczością nieco mniejszą niż 800x600 przy użyciu 4x upscalera zakodowanego przez oryginalnego autora. Ponieważ rozdzielczość używana przez iPoda to 176x132, więc na AROSie dema działają w rozdzielczości 704x528.

![Arrakis i Nano](/assets/img/0525/arrakisnano.png)
*Dema Nano i Arrakis*

> ## [GICriptoFileX](https://archives.arosworld.org/?function=showfile&file=utility/misc/gicriptofilex.i386-aros.zip) (v. 1.0) `i386`
> (autor:	Giovanni Iacobelli)

GICriptoFile Cross Edition to program do szyfrowania naszych plików przy użyciu zastrzeżonego 128-bitowego algorytmu klucza symetrycznego. Algorytm ten nie jest udostępniany publicznie.

![GICriptoFileX](/assets/img/0525/gicriptofile.jpg)
*GICriptoFileX*

> ## [BOH](https://archives.arosworld.org/?function=showfile&file=game/action/boh.i386-aros.lha) (v. 2.5) `i386`
> (autor:	Simone Bevilacqua "Saimo")

BOH to dungeon crawler, w którym musisz rozwiązywać zagadki, zbierać przedmioty, otwierać przejścia, unikać pułapek, zabijać Evil Masters i generowanych przez nich sługusów i ostatecznie wyjść z labiryntów w jednym kawałku. Zachowaj zimną krew, unikaj wrogów tak bardzo, jak to możliwe, skup się na labiryntach, a ostatecznie dotrzesz do końca.

Zmiany w wersji 2.5:
- Poprawiono deskryptor misji "Tribute to Asimov" zawartej w pakietach AmigaOS i AROS.
- Naprawiono i zaktualizowano podręcznik (zawierał nieaktualne informacje).

![BOH](/assets/img/boh.jpg)
*BOH*

> ## [Polar Paint](https://archives.arosworld.org/?function=showfile&file=graphics/edit/polarpaint_aros.lha) (v. 1.057) `i386`
> ## [Polar Paint_Small](https://archives.arosworld.org/?function=showfile&file=graphics/edit/polarpaint_small_aros.lha) (v. 1.057) `i386`
> (autor:	Anbjørn Myren)

PolarPaint to narzędzie graficzne stworzone przy użyciu środowiska Hollywood, oferujące możliwość pracy jednocześnie aż na ośmiu niezależnych obszarach roboczych. Każda z przestrzeni może mieć osobne ustawienia dotyczące historii zmian, z konfigurowalną liczbą poziomów cofania i ponawiania (Undo/Redo) – od 10 aż do 100 kroków.

Program udostępnia podstawowe funkcje edycji grafiki, a także obsługę przezroczystości w dwóch różnych trybach działania. Z uwagi na zaawansowaną funkcjonalność, aplikacja stawia stosunkowo wysokie wymagania sprzętowe – do poprawnego działania niezbędny jest szybki komputer, zdolny do wyświetlenia rozdzielczości co najmniej 1440x900 w 16-bitowej głębi kolorów oraz posiadający minimum 40 MB wolnej pamięci.

Każdy aktywny obszar roboczy zużywa około 4 MB pamięci RAM, podobnie jak poziomy Undo/Redo, co oznacza, że dostępna ilość pamięci ma bezpośredni wpływ na liczbę możliwych kroków historii i jednoczesnych przestrzeni pracy. Aby zminimalizować wpływ na pamięć, autor zaimplementował mechanizm zapisywania nieaktywnych obszarów roboczych i historii edycji na dysku. Rozwiązanie to pozwala na korzystanie z pełnych możliwości programu nawet przy ograniczonej ilości RAM, choć kosztem spadku wydajności ze względu na częsty dostęp do dysku.

W wersji **Polar Paint small** zostały ograniczone obszar rysowania oraz okno programu, aby działał na mniejszych zasobach.

![Polar Paint](/assets/img/0425/polarpaint.jpg)
*Polar Paint*

> ## [Video Slot Machine](https://archives.arosworld.org/?function=showfile&file=game/board/videoslotmachine.lha) (v. 1.20) `i386`
> (autor:	Juan Carlos Herrán Martín)

Symulator automatu hazardowego. Automat możesz spersonalizować za pomocą własnych filmików video, które będą odtwarzane, gdy wygrywasz wirtualne pieniądze.

Zmiany w wersji 1.20:
- Naprawione błędy.
- Nowa grafika tła wykonana z pomocą IA na ekranie monitora.
- Melodie w tle stworzone z pomocą IA.
- Dodano język hiszpański.
- Teraz gra może odtwarzać do 9 filmów.
- Nowa okładka gry.

![Video Slot Machine](/assets/img/0525/vsm.jpg)
*Video Slot Machine*

