---
layout: post
title: AROS x86 - styczeń-luty 2025
subtitle: podsumowanie miesiąca
lang: pl
ref: 0125
---

Początek roku w świecie AROSa to przygotowania do zapowiadanego przejścia na 64-bit. Równolegle odbywa się praca nad wersją bazową systemu, portowane jest oprogramowanie i przygotowywane są dystrybucje. Autorzy AROS One i Tiny AROS zapowiedzieli wydanie swoich dystrybucji po pojawieniu się stabilnego systemu 64-bit.

Deadwood cały czas pracuje nad nowym buildem x86_64 ABIv11. Wersje testowe są do pobrania na [forum ArosWorld](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1337). Zachęcamy do pobierania, testowania i zgłaszania napotkanych błędów. Najbliższym celem jest wydanie builda, który będzie działał na popularnych maszynach wirtualnych oraz na wybranym dedykowanym sprzęcie. 

W ostatnim czasie odświeżona została strona [www.aros.org](http://www.aros.org). "ThatGuyWithTheKids" przeniósł skrypty budujące stronę do Pythona 3, a Matthias "Mazze" Rustler wprowadził drobne poprawki i zaktualizował wiele informacji. Więcej na ten temat można poczytać we [wpisie na blogu Mazze](https://www.mazze-online.de/blogdir/2025/02/26/aros-website.html).

Ostatnie nowości w AROS Archives:  

> ## [Protrekkr](https://archives.aros-exec.org/?function=showfile&file=audio/tracker/protrekkr.x86_64-aros-v11.zip) (v. 2.8.2) `x86_64`
> ## [Protrekkr](https://archives.aros-exec.org/?function=showfile&file=audio/tracker/protrekkr.i386-aros.zip) (v. 2.8.2) `i386`
> (autor:	Franck "hitchhikr" Charlet)

Franck "hitchhikr" Charlet nieustaje w ulepszaniu swojego flagowego programu i w ostatnim czasie mieliśmy bardzo dużo aktualizacji. Ponadto, co mnie szczególnie cieszy, do dyspozycji mamy także wersję 64-bit. ProTrekkr to program typu tracker łączący w sobie syntezator programowy wraz z tradycyjnym trackerem sampli, który może (głównie) być używany do tworzenia muzyki elektronicznej (np. psytrance, trance goa, hard acid, IDM, chip, techno, jungle itp.) do małych intro, dem lub gier. Jest to mocno zmodyfikowana wersja starego NoiseTrekker 2, który został stworzony przez Juana Antonio Arguelles Rius aka Arguru.

Zmiany w najnowszych wersjach:

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

> ## [Cave Story](https://archives.aros-exec.org/?function=showfile&file=game/platform/cavestory.x86_64-aros-v11.zip) (v. 1.0.0.6) `x86_64`
> (autorzy: Daisuke Amaya, Caitlin Shaw)

Cave Story lub Doukutsu Monogatari to uznane przez krytyków dzieło niezależnego dewelopera Pixel, pierwotnie stworzone jako hołd dla gier takich jak Metroid i Castlevania. Cave Story to platformówka 2D z klasycznym, ratującym świat bohaterem i naciskiem na eksplorację oraz odkrywanie.

Wersja AROS jest portem NXEngine, kompletnego klona/przepisania Cave Story na licencji GPL open-source. Dołączona jest przetłumaczona na język angielski wersja danych gry, które zostało wykonane przez Aeon Genesis Translations. Jeśli chcesz grać w innym języku, pobierz inną zlokalizowaną wersję i nadpisz „Doukutsu.exe” i zawartość katalogu „data” przed pierwszym uruchomieniem gry.

W nowej kompilacji dla AROS `x86_64` NXEngine został zaktualizowany do wersji 1.0.0.6.

![Cave Story](/assets/img/0125/cavestory.png)
*Cave Story*

> ## [SQLite Manager](https://archives.aros-exec.org/?function=showfile&file=office/database/sqlman.i386-aros.lha) (v. 0.6) `i386`
> (autor: Lazar Zoltan)

SQLite Manager to aplikacja oparta na silniku bazy danych SQLite. Umożliwia tworzenie, przeglądanie i modyfikowanie baz danych. Obsługa bazy danych może odbywać się za pośrednictwem GUI lub powłoki poleceń SQL, aby zaspokoić wszelkie potrzeby. Dostępne jest wstępne wsparcie dla otwartych plików arkuszy kalkulacyjnych xml, które mogą być konwertowane do baz danych, a nawet do natywnych arkuszy kalkulacyjnych Amigi.

Zmiany w wersji 0.6:  

- zmiana: Moduł importu OS4Depot wymaga wtyczki HURL.hwp do komunikacji SSL HTTP.
- poprawka: niektóre poprawki OS3.x sprawiły, że działa z MUI3.8, ale nadal występują problemy
- dodanie: lista modułów jest wyświetlana w oknie informacji
- zmiana: zaktualizowano wtyczkę SQLite do wersji 1.2 w archiwum
- dodanie: dodano klasę balansu pomiędzy elementami GUI
- dodanie: ustawienie tytułu ekranu na nazwę i wersję programu
- zmiana: Błędy SQL nie zamykają bazy danych
- poprawka: identyfikatory mui nie mogą obsługiwać niektórych znaków niełacińskich, więc nazwy pól są konwertowane do unikalnych ciągów łacińskich w gui xml
- poprawka: importer xlsx - usunięto funkcję węgierskiego konwertera UTF8 wymaganą wcześniej przed pbsługą UTF8 w Hollywood
- poprawka: przycisk ArrowRight panelu zapytań został poprawnie wykonany z klasą imagebutton
- poprawka: Moduł importu OS4Depot - poprawiono funkcje surowych ciągów znaków względem UTF8
- poprawka: Moduł importu OS4Depot nie działał, jeśli brakowało podkategorii
- dodanie: wsparcie dropfile dla otwierania bazy danych z pierwszej ikony
- dodanie: okno informacji wyświetla wersję silnika sqlite3
- poprawka: importer dbf konwertuje ciągi do UTF8 w razie potrzeby          

![SQLite Manager](/assets/img/0125/sqlman.png)
*SQLite Manager*

> ## [Image2PDF](https://archives.aros-exec.org/?function=showfile&file=office/dtp/image2pdf.i386-aros.lha) (v. 2.8) `i386`
> (autor: Bernd Assenmacher)

Małe narzędzie do konwersji obrazów do formatu PDF. Przede wszystkim służy do konwertowania skanów wykonanych np. za pomocą Scandal lub Scanquix do dokumentów PDF w określonych formatach wyjściowych, takich jak A3, A4, A5, Legal, Letter lub ImageSize, ale może być również używane do konwersji innych plików graficznych.

Zmiany w wersji 2.8:

- Wykonana lokalizacja
- Dodano język niemiecki
- Dodano angielskie i niemieckie pliki katalogów do celów tłumaczenia, więc jeśli ktoś chce innego języka, wystarczy przetłumaczyć i utworzyć określony plik katalogu. 
- Naprawiono błąd, w którym plik przewodnika nie był znajdowany po naciśnięciu „F1” lub wybierając „Help(F1)” w menu.
- naprawiono podobny błąd, w którym pdftops nie był znajdowany podczas drukowania
- naprawiono błąd instalatora, w którym ścieżka nie była poprawnie ustawiona w s:user-startup na AmigaOS3/4, MorphOS i Aros
- wprowadzono inne drobne poprawki

![Image2PDF](/assets/img/0125/image2pdf.png)
*Image2PDF*

> ## [Piramide](https://archives.aros-exec.org/?function=showfile&file=game/card/piramide_aros.lha) (v. 1.0) `i386`
> (autor: Domenico Lattanzi)

Piramide to pasjans rozgrywany za pomocą kart francuskich. Nazwa gry jest włoskim tłumaczeniem słowa „piramida” i wzięła się z tego, że podczas gry karty są układane w kształcie trójkąta. Celem gracza jest usunięcie wszystkich kart, które tworzą piramidę.  

Uwaga! Trzeba pobrać zestaw kart (jest wiele różnych do wyboru) z zewnętrznej strony. Szczegóły w załączonym do archiwum pliku Guide.

![Piramide](/assets/img/0125/piramide.png)
*Piramide*

> ## [PuzzleTiles](https://archives.aros-exec.org/?function=showfile&file=game/puzzle/puzzletiles_aros.lha) (v. 1.0) `i386`
> (autor: Domenico Lattanzi)

W PuzzleTiles wybrany przez użytkownika obraz jest rozkładany na części, a następnie zadaniem gracza jest go ponownie złożyć w całość. "Puzzle" układamy za pomocą myszki, zamieniając miejscami dwa wskazane fragmenty.

Funkcje:

- Można użyć dowolnego obrazu w formacie rozpoznawanym przez system
- Możliwość dostosowania rozmiaru okna
- 5 poziomów trudności
- Dostępny jest pasek postępu informujący o osiągniętym punkcie przebudowy obrazu
- Możliwość podglądu ukończonego obrazu przez 5 sekund w celu uzyskania podpowiedzi
- Efekty dźwiękowe, które również pomagają użytkownikowi w odbudowie obrazu  

![PuzzleTiles](/assets/img/0125/puzzletiles.png)
*PuzzleTiles*

> ## [V.A.M.P.](https://archives.aros-exec.org/?function=showfile&file=video/play/vamp.lha) (v. 3.20) `i386`
> (autor:	Juan Carlos Herrán Martín)

V.A.M.P - Virtual Amiga Multimedia Player - wyświetla obecnie następujące formaty multimedialne:

- Amiga Anim formaty: anim, anim5, ham6, ham8, yafa.
- Format filmów MovieSetter.
- Formaty animacji internetowych: gif, apng.
- Wyświetlanie obrazów: jpg, png, gif, lbm, bmp, svg, jp2(jpeg 2000), tiff, pcx, webp (z Datatypes).
- Formaty wideo: cdxl, ogg, avi, mpeg, mpg, wmv, flv, mp4, mov, 3gp, m4v.
- Pliki muzyczne i dźwiękowe: mp3, mod, med, 8svx, 16sv, iff, aiff, wav, ac3, wave, riff, ogg, flac, m4a, wma, dbm, hvl, aiff, s3m, xm, sid.

Dostępny w następujących językach: hiszpański, angielski, włoski, francuski, fiński, szwedzki, polski, grecki.

Zmiany w tej wersji:

- Drobne ulepszenia i nowe logo.
- Naprawiono niektóre problemy ze specjalnymi rozmiarami wideo do odtwarzania filmów pobranych z: Facebook Reels, Tik Tok, CapCut, Instagram Reels, Kwai i Whatsapp.

UWAGA: Zalecane rozmiary wideo to 360xNN pikseli, rozmiary większe niż szerokość 360 będą odtwarzane wolno w zależności od szybkości procesora.

![V.A.M.P.](/assets/img/0125/vamp.png) 
*V.A.M.P.*

> ## [iConecta](https://archives.aros-exec.org/?function=showfile&file=network/misc/iconecta.lha) (v. 5.50) `i386`
> (autor:	Juan Carlos Herrán Martín)

Mały i prosty program do testowania połączenia internetowego. W tej wersji dodano:
- Nową grafikę intra
- Nowe motywy: Haker, Pirat i Kosmos
- Grafikę HD

![iConecta](/assets/img/0125/iconecta.png)
*iConecta*

Coraz więcej starszych aplikacji zostaje przekompilowywanych na x86_64. W ostatnim czasie do AROS Archives trafiły:

|----------|-----------------------------------------------------------------------------------------------|-------------------------------------|
| `x86_64` | [ZapperNG](https://archives.aros-exec.org/?function=showfile&file=utility/workbench/zapperng.x86_64-aros-v11.zip) | Change the behaviour of the zoom-button |
| `x86_64` | [Switch](https://archives.aros-exec.org/?function=showfile&file=utility/workbench/switch.x86_64-aros-v11.zip) | Screens/windows switcher commodity |
| `x86_64` | [Amigakeyremap](https://archives.aros-exec.org/?function=showfile&file=utility/misc/amigakeyremaper.x86_64-aros-v11.zip.zip) | Simple program that swaps left/right amiga keys |
| `x86_64` | [WildMIDI](https://archives.aros-exec.org/?function=showfile&file=audio/play/wildmidi.x86_64-aros-v11.zip) | Midi Player |
| `x86_64` | [CLS](https://archives.aros-exec.org/?function=showfile&file=utility/shell/cls.x86_64-aros-v11.zip) | Clear Screen command |
| `x86_64` | [Demac](https://archives.aros-exec.org/?function=showfile&file=audio/misc/demac.x86_64-aros-v11.zip) | Decoder for .ape files |
| `x86_64` | [7zDec](https://archives.aros-exec.org/?function=showfile&file=utility/archive/7zdec.x86_64-aros-v11.zip) | Unarchive 7zip files (.7z) |
| `x86_64` | [Zunearc](https://archives.aros-exec.org/?function=showfile&file=utility/archive/zunearc.x86_64-aros-v11.zip) | A Zune front end for archivers |
| `x86_64` | [UnRAR](https://archives.aros-exec.org/?function=showfile&file=utility/archive/unrar-v6.11.x86_64-aros-v11.zip) | UnRAR for AROS 64 v11 |
| `x86_64` | [Demoeffects](https://archives.aros-exec.org/?function=showfile&file=demo/misc/demoeffects.x86_64-aros-v11.zip) | Many Demo Effects |
| `x86_64` | [Sdllopan](https://archives.aros-exec.org/?function=showfile&file=game/board/sdllopan.x86_64-aros-v11.zip) | MahJong clone |
| `x86_64` | [Bad Apple](https://archives.aros-exec.org/?function=showfile&file=demo/misc/badapple.x86_64-aros-v11.zip) | The famous Bad Apple animation |
| `x86_64` | [UnTarka](https://archives.aros-exec.org/?function=showfile&file=utility/archive/untarka.x86_64-aros-v11.zip) | Unpack tar file |
| `x86_64` | [UnMount](https://archives.aros-exec.org/?function=showfile&file=utility/text/misc/unmount.x86_64-aros-v11.zip) | Device unmounting tool |
| `x86_64` | [UNLZX](https://archives.aros-exec.org/?function=showfile&file=utility/archive/unlzx.x86_64-aros-v11.zip) | Unpack lzx files |
| `x86_64` | [SidDump](https://archives.aros-exec.org/?function=showfile&file=audio/misc/siddump.x86_64-aros-v11.zip) | C64 music debug output utility |
| `x86_64` | [SFSObject](https://archives.aros-exec.org/?function=showfile&file=utility/misc/sfsobject.x86_64-aros-v11.zip) | Sets SFS object attributes |
| `x86_64` | [QLView](https://archives.aros-exec.org/?function=showfile&file=graphics/viewer/qlview.x86_64-aros-v11.zip) | Sinclair QL Screen viewer |
| `x86_64` | [Potrace](https://archives.aros-exec.org/?function=showfile&file=graphics/convert/potrace.x86_64-aros-v11.zip) | Transforming bitmaps into vector graphics |
| `x86_64` | [GNU-Grep](https://archives.aros-exec.org/?function=showfile&file=utility/misc/grep.x86_64-aros-v11.zip) | GNU Grep |
| `x86_64` | [TimeIT](https://archives.aros-exec.org/?function=showfile&file=utility/shell/timeit.x86_64-aros-v11.zip) | Shell command for timing other commands |
| `x86_64` | [TinySID](https://archives.aros-exec.org/?function=showfile&file=audio/play/tinysid.x86_64-aros-v11.zip) | A small, multiplatform SID player |
| `x86_64` | [Skandalfoclock](https://archives.aros-exec.org/?function=showfile&file=utility/workbench/skandalfoclock.x86_64-aros-v11.zip) | 	Advanced Analog Clock |
| `x86_64` | [Rescode](https://archives.aros-exec.org/?function=showfile&file=utility/misc/rescode.x86_64-aros-v11.zip) | Calculates resistor values (4 and 5 band) |
| `x86_64` | [Nomarch](https://archives.aros-exec.org/?function=showfile&file=utility/archive/nomarch.x86_64-aros-v11.zip) | Extract old .arc and .ark archives |
| `x86_64` | [JoyTest](https://archives.aros-exec.org/?function=showfile&file=utility/misc/joytest.x86_64-aros-v11.zip) | Joypad test prints lowlevel data to the shell |
| `x86_64` | [DiskUsage](https://archives.aros-exec.org/?function=showfile&file=utility/shell/diskusage.x86_64-aros-v11.zip) | Estimates file space usage |
| `x86_64` | [DirTree](https://archives.aros-exec.org/?function=showfile&file=utility/misc/dirtree.x86_64-aros-v11.zip) | Shell command displaying directory trees |
| `x86_64` | [Bin2Iso](https://archives.aros-exec.org/?function=showfile&file=utility/filetool/bin2iso.x86_64-aros-v11.zip) | Convert Bin File to ISO 9660 |
| `x86_64` | [Alac](https://archives.aros-exec.org/?function=showfile&file=audio/misc/alac.x86_64-aros-v11.zip) | Apple Lossless Audio Codec decoder |
| `x86_64` | [Dclock](https://archives.aros-exec.org/?function=showfile&file=utility/workbench/dclock.x86_64-aros-v11.lha) | Utilities Clock for Wanderer |
| `x86_64` | [WgetGui](https://archives.aros-exec.org/?function=showfile&file=network/misc/wgetgui.x86_64-aros-v11.zip) | Gui for Wget |
| `x86_64` | [ZuneCalc](https://archives.aros-exec.org/?function=showfile&file=office/misc/zunecalc.x86_64-aros-v11.zip) | Simple Calculator |
| `x86_64` | [ZuneView](https://archives.aros-exec.org/?function=showfile&file=graphics/viewer/zuneview.x86_64-aros-v11.tar) | Picture Viewer With Effect |
| `x86_64` | [ZunePaint](https://archives.aros-exec.org/?function=showfile&file=graphics/edit/zunepaint.x86_64-aros-v11.tar) | Bitmap Paint With Additional Effect |
