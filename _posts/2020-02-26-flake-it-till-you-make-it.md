---
layout: post
title: AROS x86 - maj 2025
subtitle: podsumowanie miesiąca
lang: pl
ref: 0525
---


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

> ## [GICriptoFileX](https://archives.arosworld.org/?function=showfile&file=utility/misc/gicriptofilex.i386-aros.zip) (v. 1.0) `i386`
> (autor:	Giovanni Iacobelli)

GICriptoFileX

![GICriptoFileX](/assets/img/0425/gicriptofilex.png)
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

Video Slot Machine

![Video Slot Machine](/assets/img/0525/videoslotmachine.jpg)
*Video Slot Machine*

