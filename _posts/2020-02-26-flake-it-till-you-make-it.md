---
layout: post
title: AROS x86 - lipiec 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 0724
---

W lipcu Deadwood rozpoczął prace nad aktualizacją przeglądarki OWB (zgodnie z [Development plan](https://arosworld.org/infusions/forum/viewthread.php?thread_id=1114&rowstart=20&pid=5871#post_5869)). Na forum AROS World założone są tematy dotyczące zarówno 32-bitowej jak i 64-bitowej wersji przeglądarki. Można tam pobrać najnowszą wersję deweloperską i uczestniczyć w testach, do czego mocno zachęcam. Jednocześnie wypuszczona została publiczna wersja AROS 64-bit na której można pracować z 64-bitową Oddysey Web Browser.

Na blogu zamieściłem serię tutoriali, jak zainstalować Oddysey Web Browser w różnych środowiskach:
- [Oddysey Web Browser w AROS Linux hosted](https://arosnews.github.io/oddysey-web-browser-aros-linux-hosted/)  
- [Oddysey Web Browser w AxRT Linux](https://arosnews.github.io/oddysey-web-browser-axrt-linux/)  
- [Oddysey Web Browser w AxRT Windows 11 (WSL2)](https://arosnews.github.io/oddysey-web-browser-axrt-wsl2/)  

Została zaktualizowana dystrybucja Tiny AROS do wersji 3.3. Najważniejsza zmiana to Wanderer jako domyślne środowisko desktopowe (wcześniej domyślnym środowiskiem był Magellan). Zmiana ta zapewne została podyktowana poprawkami, które spotkały Wanderera w ostatnich miesiącach. Pełną listę zmian w załączonym oprogramowaniu można znaleźć na [stronie projektu](https://www.tinyaros.it/).

![TinyAROS](/assets/img/tiny33.jpg)
*Tiny AROS 3.3*

W serwisie YouTube na kanale Amiten TV jest do obejrzenia zapis blisko 3 godzinnego [live streama](https://www.youtube.com/watch?v=KigowKD1Aag) z przeglądu funkcji i oprogramowania AROS One 2.5. **Amiten TV** używa w pełni obsługiwanego komputera PC, karty graficznej 3D, karty dźwiękowej, karty sieciowej. Film jest w języku hiszpańskim. Polecam!

Na [OSNews.com](https://www.osnews.com/story/140225/package-amigaos-software-for-linux-and-windows-with-axruntime/) został zauważony AROS w wersji AXRuntime. Warto zapoznać się z tym wpisem oraz komentarzami zamieszonymi pod nim.

W ankiecie na Irytujący bug miesiąca mieliśmy w lipcu remis. Równą liczbę głosów otrzymały zgłoszenia:  
*#144 (Graphical artifacts when dragging an icon)*  
*#25 (Shell won't open from icon that leave out)*

![IBOTM 07.2024](/assets/img/ibotm0724.png)
*Irytujący Bug Miesiąca - lipiec 2024*

Naprawiony przez **Deadwooda** został bug *#25*, a [poprawka](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1279&pid=5842#post_5811) ta zasadniczo rozwiązuje również problem buga *#26 Multiple copying of the "Shell" icon when it's deleted*. Więc w lipcu mamy naprawione dwa Irytujące bugi, a bug *#144* przechodzi na sierpień. 

W AROS Archives czuć sezon wakacyjny, bo nowych programów niewiele, ale nawet z tej ilości można wybrać coś ciekawego :)

> ## [Pintor Web](http://archives.aros-exec.org/?function=showfile&file=graphics/convert/pintorweb.lha) (v. 5.0)
> (autor: Juan Carlos Herrán Martín)

Łatwy w obsłudze program do edycji zdjęć wykorzystywanych w projektach stron internetowych. Umożliwia zmianę rozmiaru, obrót, stosowanie efektów wizualnych, dodawanie znaku wodnego lub logo marki, zapisywanie w różnych formatach.

Zmiany w najnowszej wersji:
- Zmieniona okładka programu, aby uniknąć jednego problemu z wersją AROS.
- Poprawiony i ulepszony efekt Polaroid.
- Naprawiono błędy.
- Nowe efekty korekcji.
- Nowe efekty wizualne.
- Zoptymalizowano kod.
- Przepisana instrukcja PDF.

![Pintor Web](/assets/img/pintorweb5.jpg)
*Pintor Web*

> ## [Crono](http://archives.aros-exec.org/?function=showfile&file=graphics/misc/crono_aros.lha) (v. 3.0)
> (autor: Domenico Lattanzi)

Generatore kalendarzy do wydrukowania.  

Najnowsza wersja umożliwia:
- Tworzenie kalendarzy w formacie strony DIN A4 lub A3, w orientacji pionowej lub poziomej
- Kalendarze miesięczne lub roczne
- Stylizowane jako siatki lub listy
- Możliwość dostosowania poprzez dodanie zdjęcia, wybór czcionki i kolorów
- 26 obsługiwanych języków
- Wybór pomiędzy niedzielą a poniedziałkiem jako pierwszym dniem tygodnia
- Oznaczanie poszczególnych dni jako dni wolnych od pracy
- Wyjście do formatu PDF

![Crono](/assets/img/crono.png)
*Crono*

> ## [Terri-Fried](http://archives.aros-exec.org/?function=showfile&file=game/platform/terri-fried.i386-aros.zip) (v. 1.0)
> (autor: PolyMars)

Czy pomożesz przetrwać temu jajku? Kliknij prawym przyciskiem myszy i przeciągnij, aby utworzyć trajektorię, a następnie zwolnij przycisk myszy, aby wysłać bohatera w powietrze. Gra kończy się, gdy jajko wpadnie do wrzącej lawy. Aby uzyskać wysoki wynik, celuj w spadające platformy i zbierz jak najwięcej monet!

![Terri-Fried](/assets/img/terri.png)
*Terri-Fried*

> ## [Cards Making Kit](http://archives.aros-exec.org/?function=showfile&file=game/utility/cardsmakingkit.lha) (v. 2.0)
> (autor: Juan Carlos Herrán Martín)

Jest to małe narzędzie do tworzenia własnych talii do gier karcianych:  
    - HLE Poker Card (High-Low-Equal Poker Card).  
    - BlackJuan.  
    - Siete y Media.  
    - Baccarat.  
    - BlackIvan Card.  

![Cards Making Kit](/assets/img/cardsmakingkit.jpg)
*Cards Making Kit*

> ## [GI Master Mind](http://archives.aros-exec.org/?function=showfile&file=game/board/gimastermindaros.i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

Gra na inteligencję, która polega na odgadnięciu tajnej kombinacji kolorów. W tym wydaniu można zmierzyć się z komputerem, próbując odgadnąć 4 z pośród 8 kolorów. Liczba prób jest nieograniczona.

![GI Master Mind](/assets/img/gimastermind.png)
*GI Master Mind*

> ## [GI Puzzle Balls](http://archives.aros-exec.org/?function=showfile&file=game/puzzle/gipuzzleballs-i386-aros.zip) (v. 1.0)
> (autor: Giovanni Iacobelli)

Gra typu "match 3". Gracz musi łączyć co najmniej trzy identyczne elementy (w tym przypadku spadające kulki) w linii prostej, aby je usunąć z planszy. 

![GI Puzzle Balls](/assets/img/gipuzzleballs.png)
*GI Puzzle Balls*

> ## [Donkey Kong](http://archives.aros-exec.org/?function=showfile&file=game/board/donkeykong_net_arosx86.lha) (v. 1.83)
> (autor: Anbjorn Myren)

Remake gry LCD z serii Game&Watch stworzonej przez Nintendo. 

![DonkeyKong](/assets/img/donkeykong.jpg)
*Donkey Kong*

> ## [EuroChamp](http://archives.aros-exec.org/?function=showfile&file=document/misc/eurochamp.lha) (v. 1.44)
> (autor: Pasi Ylinen)

Dokument w formacie Amigaguide przedstawiający statystyki Mistrzostw Europy od 1960 do 2024 roku. Najnowsze wersja została uzupełniona o składy i wyniki z Euro 2024. Pozycja obowiązkowa dla każdego miłośnika piłki nożnej!  

![EuroChamp](/assets/img/euro.png)
*EuroChamp*

> ## [icons_pack_kensv4](http://archives.aros-exec.org/?function=showfile&file=graphics/icon/more_icons_kensv4.zip) (v.2)
> (autor: amiwell79)

Zestaw nieoficjalnych ikon w stylu kensv4 dla aplikacji i szuflad.

![icons_pack_kensv4](/assets/img/iconspackkensv4.png)
*icons_pack_kensv4*


