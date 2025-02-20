---
layout: post
title: AROS x86 - styczeń 2025
subtitle: podsumowanie miesiąca
lang: pl
ref: 0125
---



Pozostałe nowości w AROS Archives:  

> ## [Protrekkr](https://archives.aros-exec.org/?function=showfile&file=audio/tracker/protrekkr.i386-aros.zip) (v. 2.8.2)
> (autor:	Franck "hitchhikr" Charlet)

v2.8.2

- Patterns wouldn't scroll sometimes when starting to play, fixed.
- Note volume from channels (volume columns and effects 03) are now handled in the velocity sent to midi output.
- Changed LCTRL + F1 / F2 (Decrease / Increase editing step) to LCTRL + F2 / F4 due to Mac OS "interfering".
- Fixed Midi handling on Linux and Mac OS.
- Fixed the keyboard shortcuts on Mac OS.
- Typos in the manual: Transpose to 1 octave higher shortcuts are LCTRL + K and LCTRL + LSHIFT + K.
- Replaced pink noise with triangle waveform in synth.
- White noise is now twice as loud to be on par with other waveforms loudness.
- Added a function to hard sync OSC 1 to OSC 2.
- Inserting or deleting a track didn't modify the other patterns data.
- Fixed an ugly visual bug that occured when changing colors during playing.
- Added tracks header foreground color modifier.
- Sub oscillator can now be scaled from oscillator 1 by semitones.
- Maths combiner functions are also used for sub oscillator.
- Fixed various bugs here and there.
- VU meters are now displayed on a single line and a much less sensitive.
- Removed support for antediluvian NoiseTrekker 1/2 modules & instruments, they were only supported for salvage and conversion purposes.
- Saving a pattern without any currently selected block will save the entire pattern into the file.
- New logo !

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
- Funkcje modyfikacji wzorców są aktywne tylko wtedy, gdy włączony jest tryb edycji.
- Funkcje transpozycji śledzą teraz ostatnio używane instrumenty, aby móc transponować odpowiednie nuty używane bez instrumentów.
- Zatrzymanie trybu krokowego spowoduje, że tryb edycji pozostanie nienaruszony.
- Próbka „Maksymalizuj” (Max) jest teraz nazywana „Normalizuj” (Norm) w edytorze próbek.
- Więcej wizualnych informacji zwrotnych dla aktualnie odtwarzanego sampla w edytorze sampli.
- Dodano opcję pokazywania/usuwania wiodących cyfr zerowych we wzorach.
- Dodano tryb edycji suwaków wzorców (sprawdź instrukcję, aby uzyskać wyjaśnienia). Uwaga: Tryb ten może być dość obciążający dla procesora.
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

> ## [Image2PDF](https://archives.aros-exec.org/?function=showfile&file=office/dtp/image2pdf.i386-aros.lha) (v. 2.8)
> (autor: Bernd Assenmacher)

Image2PDF

![Image2PDF](/assets/img/0125/image2pdf.jpg)
*Image2PDF*

> ## [PuzzleTiles](https://archives.aros-exec.org/?function=showfile&file=game/puzzle/puzzletiles_aros.lha) (v. 1.0)
> (autor: Domenico Lattanzi)

PuzzleTiles

![PuzzleTiles](/assets/img/0125/puzzletiles.jpg)
*PuzzleTiles*

> ## [iConecta](https://archives.aros-exec.org/?function=showfile&file=network/misc/iconecta.lha) (v. 5.50)
> (autor:	Juan Carlos Herrán Martín)

iConecta  

![iConecta](/assets/img/0125/iconecta.png)
*iConecta*

