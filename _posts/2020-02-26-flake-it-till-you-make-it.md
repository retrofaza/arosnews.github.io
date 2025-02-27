---
layout: post
title: AROS x86 - styczeń-luty 2025
subtitle: podsumowanie miesiąca
lang: pl
ref: 0125
---



Pozostałe nowości w AROS Archives:  

> ## [Protrekkr](https://archives.aros-exec.org/?function=showfile&file=audio/tracker/protrekkr.x86_64-aros-v11.zip) (v. 2.8.2) `x86_64`
> ## [Protrekkr](https://archives.aros-exec.org/?function=showfile&file=audio/tracker/protrekkr.i386-aros.zip) (v. 2.8.2) `i386`
> (autor:	Franck "hitchhikr" Charlet)

v2.8.2

- Patterny czasami nie przewijały się po rozpoczęciu odtwarzania, naprawiono.
- Głośność nut z kanałów (kolumny głośności i efekty 03) są teraz obsługiwane w prędkości wysyłanej do wyjścia midi.
- Zmieniono LCTRL + F1 / F2 (zmniejszanie / zwiększanie kroku edycji) na LCTRL + F2 / F4 ze względu na „zakłócanie” systemu Mac OS.
- Poprawiono obsługę Midi w systemach Linux i Mac OS.
- Poprawiono skróty klawiaturowe w systemie Mac OS.
- Literówki w instrukcji: Skróty transpozycji do 1 oktawy wyżej to LCTRL + K i LCTRL + LSHIFT + K.
- Zastąpiono różowy szum falą trójkątną w syntezatorze.
- Biały szum jest teraz dwa razy głośniejszy, aby dorównać głośności innych przebiegów.
- Dodano funkcję twardej synchronizacji OSC 1 z OSC 2.
- Wstawianie lub usuwanie ścieżki nie modyfikowało danych innych patternów.
- Naprawiono brzydki błąd wizualny, który występował podczas zmiany kolorów podczas odtwarzania.
- Dodano modyfikator koloru pierwszego planu nagłówka ścieżek.
- Suboscylator może być teraz skalowany od oscylatora 1 o półtony.
- Funkcje sumatora matematycznego są również używane dla oscylatora podrzędnego.
- Naprawiono różne błędy tu i ówdzie.
- Mierniki VU są teraz wyświetlane w jednej linii i są znacznie mniej czułe.
- Usunięto obsługę przedpotopowych modułów i instrumentów NoiseTrekker 1/2, były one obsługiwane tylko do celów ratunkowych i konwersji.
- Zapisywanie patternu bez aktualnie wybranego bloku spowoduje zapisanie całego patternu do pliku.
- Nowe logo!

v2.8.1

- Nośniki LFO kanałów są teraz prawidłowo resetowane przy starcie odtwarzania.
- Dane LFO kanałów mogą być teraz wysyłane do odcięcia filtra kanału, głośność i panoramowanie.
- Dodano skaler częstotliwości LFO kanału.
- Dodano następujące efekty:
  - 43: Ustawianie częstotliwości LFO kanału.
  - 44: Ustawianie współczynnika skali częstotliwości LFO kanału.
  - 45: Ustawianie ilości LFO kanału do wysłania do odcięcia filtra kanału.
  - 46: Ustawianie ilości LFO kanału wysyłanej do głośności kanału.
  - 47: Ustaw ilość LFO kanału, aby wysłać do panoramy kanału.
- Naprawiono bardzo stary błąd NoiseTrekker, w którym wartości LFO wysyłane do kanałów były tracone, ponieważ były zbyt duże i zaciśnięte.
- Naprawiono nieprzyjemną regresję, która występowała w 64-bitowych wersjach skompilowanych.  

v2.8.0
- Dodano funkcję negacji bieżącej palety.
- Dodano dwie funkcje do obracania bieżącej palety w lewo lub w prawo.
- Przearanżowano bitchbiker.ptk i dodano go do oficjalnej listy modułów.
- Zmieniono zachowanie trybu pojedynczego kroku, odtwarzanie zatrzymuje się tylko wtedy, gdy wciśnięty jest klawisz enter (lub return) i odtwarzany jest tylko bieżący pattern (naciśnij lewy Shift, aby przejść do trybu utworu).
- Dodano funkcję transpozycji zakresu instrumentów.
- Funkcje modyfikacji patternów są aktywne tylko wtedy, gdy włączony jest tryb edycji.
- Funkcje transpozycji śledzą teraz ostatnio używane instrumenty, aby móc transponować odpowiednie nuty używane bez instrumentów.
- Zatrzymanie trybu krokowego spowoduje, że tryb edycji pozostanie nienaruszony.
- Próbka „Maksymalizuj” (Max) jest teraz nazywana „Normalizuj” (Norm) w edytorze próbek.
- Więcej wizualnych informacji zwrotnych dla aktualnie odtwarzanego sampla w edytorze sampli.
- Dodano opcję pokazywania/usuwania wiodących cyfr zerowych we wzorach.
- Dodano tryb edycji suwaków patternów (sprawdź instrukcję, aby uzyskać wyjaśnienia). Uwaga: Tryb ten może być dość obciążający dla procesora.
- Naprawiono różne błędy w edycji patternów.
- Mierniki VU kanałów były rysowane zbyt wiele razy nad sobą, naprawiono.
- Poprawiono poziomy audio mierników VU kanałów.
- Zmodyfikowano pogłos (powinien brzmieć lepiej (?)) i dodano parametr tłumienia (z tego powodu musiałem przerobić niektóre moduły).
- Dodano efekt 2C: Ustawianie współczynnika tłumienia pogłosu.
- Poprawiono narastanie głośności.
- Dodano skróty klawiaturowe LCTRL + LALT + HOME / END (przeskok do górnej/pierwszej ścieżki lub dolnej/ostatniej ścieżki patternu).
- Dodano klawisze Enter lub Return do odtwarzania pojedynczych kroków.
- Poprawiono alokacje kanałów polifonii.
- Naprawiono przełączanie trybu pełnoekranowego w AROS.
- Dodano plik wykonywalny OpenGL w dystrybucji AROS (ptk_aros_ogl) z jakiegoś powodu, którego nie wyjaśniam, może być wolniejszy niż zwykły, przebieg może się różnić.

![Protrekkr](/assets/img/0125/protrekkr.png)
*Protrekkr*

> ## [SQLMan](https://archives.aros-exec.org/?function=showfile&file=office/database/sqlman.i386-aros.lha) (v. 0.6) `i386`
> (autor: Lazar Zoltan)

SQLMan

![SQLMan](/assets/img/0125/sqlman.jpg)
*SQLMan*

> ## [Image2PDF](https://archives.aros-exec.org/?function=showfile&file=office/dtp/image2pdf.i386-aros.lha) (v. 2.8) `i386`
> (autor: Bernd Assenmacher)

Image2PDF

![Image2PDF](/assets/img/0125/image2pdf.jpg)
*Image2PDF*

> ## [Cave Story](https://archives.aros-exec.org/?function=showfile&file=game/platform/cavestory.x86_64-aros-v11.zip) (v. 1.0.0.6) `x86_64`
> (autorzy: Daisuke Amaya, Caitlin Shaw)

Cave Story

![Cave Story](/assets/img/0125/cavestory.jpg)
*Cave Story*

> ## [Piramide](https://archives.aros-exec.org/?function=showfile&file=game/card/piramide_aros.lha) (v. 1.0) `i386`
> (autor: Domenico Lattanzi)

Piramide

![Piramide](/assets/img/0125/piramide.jpg)
*Piramide*

> ## [PuzzleTiles](https://archives.aros-exec.org/?function=showfile&file=game/puzzle/puzzletiles_aros.lha) (v. 1.0) `i386`
> (autor: Domenico Lattanzi)

PuzzleTiles

![PuzzleTiles](/assets/img/0125/puzzletiles.jpg)
*PuzzleTiles*

> ## [V.A.M.P.](https://archives.aros-exec.org/?function=showfile&file=video/play/vamp.lha) (v. 3.20) `i386`
> (autor:	Juan Carlos Herrán Martín)

V.A.M.P.

![V.A.M.P.](/assets/img/0125/vamp.png) 
*V.A.M.P.*

> ## [iConecta](https://archives.aros-exec.org/?function=showfile&file=network/misc/iconecta.lha) (v. 5.50) `i386`
> (autor:	Juan Carlos Herrán Martín)

iConecta  

![iConecta](/assets/img/0125/iconecta.png)
*iConecta*

