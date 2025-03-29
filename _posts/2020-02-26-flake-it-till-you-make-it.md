---
layout: post
title: AROS x86 - marzec 2025
subtitle: podsumowanie miesiąca
lang: pl
ref: 0325
---

Wydarzeniem marca jest wydanie przez Deadwood'a nowej 32-bitowej wersji bazowej systemu (AROS ABIv0 20250313). Aktualizacja ta doprowadza 32-bitowe jądro do tego samego poziomu, co nadchodzące wydanie 64-bitowe, nad którym nieustannie trwają prace. Ponadto wersja 68k również otrzymuje poprawki. W świecie AROS-a wciąż wiele się dzieje, a osoby zainteresowane użytkowaniem systemu Amigi w tym wydaniu nie mogą narzekać na nudę!

Nowa wersja 32-bitowego systemu bazowego AROS (ABIv0 20250313) jest już dostępna do pobrania. W tej wersji zawarto wszystkie zmiany z ostatnich trzech lat rozwoju systemu, a także wprowadzono wiele ulepszeń. Główne zmiany obejmują:

- Ulepszone wsparcie dla nowszego sprzętu, w tym obsługa ACPI.
- Ulepszona stabilność i wsparcie dla sterowników dysków i sieci.
- Ponad 60 poprawek błędów w programach i bibliotekach systemowych.
- Stabilizacja sterowników dla wirtualizacji (VirtualBox, VMware i QEMU), co umożliwia testowanie systemu w środowiskach wirtualnych przed zakupem odpowiedniego sprzętu.
- Aktualizacje podstawowych bibliotek systemowych.

Pakiety są dostępne do pobrania na [GitHubie](https://github.com/deadwood2/AROS/releases/tag/ABIv0_20250313-1). Udostępniono także [aktualizację](https://github.com/deadwood2/AROS/releases/download/ABIv0_20220318-1/AROS-20220318-1-U3-any-i386-update.zip) dla osób, które mają już zainstalowaną poprzednią wersję systemu AROS (20220318-1). Dodatkowo dostępna jest [lista rekomendowanego sprzętu](https://en.wikibooks.org/wiki/Aros/Platforms/x86_Complete_System_HCL#Recommended_hardware_(32-bit)) na WikiBooks, która może pomóc przy doborze odpowiedniego urządzenia.

Carlo Spadoni (AMIGASYSTEM) zapowiedział, że w oparciu o nowy system wkrótce pojawi się kolejne wydanie 32-bitowej dystrybucji AROS One. Równocześnie trwają prace nad jej pierwszą wersją 64-bitową. Dodatkowo, AROS One 68k dla procesorów Motorola ma otrzymać aktualizację do wersji 2.0 – już teraz dostępna jest wersja testowa.  

Tymczasem Olaf Schönweiß jest na ostatniej prostej w pracach nad dystrybucją **AROS Vision** dla architektury 68k, a jej oficjalne wydanie powinno nastąpić w najbliższym czasie.

Zmienił się adres strony AROS Archives. Domena archives.aros-exec.org, która przez lata kierowała do AROSowego repozytorium wygasła. Nowy adres to: [https://archives.arosworld.org](https://archives.arosworld.org).

W marcu AROS Archives został w dużej mierze zdominowany przez porty gier przeznaczone dla przyszłych 64-bitowych dystrybucji. Większość z nich była już wcześniej dostępna na 32-bitowej wersji systemu, jednak w niektórych przypadkach nowe porty pojawiły się w nowszych wersjach.

> ## [Hocoslamfy](https://archives.arosworld.org/?function=showfile&file=game/misc/hocoslamfy.x86_64-aros-v11.zip) (v. 2016) `x86_64`
> (autorzy:	Nebuleon Fumika, hi-ban, jxv)

Hocoslamfy to prosta gra zręcznościowa, w której gracz steruje małą pszczołą, unikając bambusowych pędów wyrastających z góry i dołu ekranu. Celem jest przelatywanie przez przestrzenie między pędami, zdobywając punkty za każdy udany przelot. Gra kończy się, gdy pszczoła zderzy się z przeszkodą lub krawędzią ekranu. 

![Hocoslamfy](/assets/img/0325/hocoslamfy-2.png)
*Hocoslamfy*

> ## [Mini Metal Slug](https://archives.arosworld.org/?function=showfile&file=game/action/minislug.x86_64-aros-v11.zip) (v. 2.0.0.04) `x86_64`
> (autor: Clément Corde)

"Mini Metal Slug" to nieoficjalny hołd dla klasycznej serii gier "Metal Slug", stworzony przez fana Clementa Corde. Gra składa się z trzech misji, z których każda podzielona jest na kilka poziomów. Gracze wcielają się w rolę żołnierza, który musi pokonać fale wrogów, uwalniać zakładników oraz zdobywać nowe rodzaje broni i zdrowie. Charakteryzuje się szybkim tempem rozgrywki oraz humorem nawiązującym do oryginalnej serii.

![Mini Metal Slug](/assets/img/0325/minimetalslug-2.png)
*Mini Metal Slug*

> ## [Tinytris](https://archives.arosworld.org/?function=showfile&file=game/puzzle/tinytris.x86_64-aros-v11.zip) (v. 2.3) `x86_64`
> (autor: Daniel Champagne)

Tinytris to minimalistyczna wersja klasycznej gry Tetris. Charakteryzuje się prostą grafiką i klimatyczną muzyką. W Tinytris gracze układają spadające klocki w taki sposób, aby tworzyć pełne linie, które następnie znikają, przyznając punkty. Rozgrywka staje się coraz szybsza w miarę postępów, co zwiększa poziom trudności.      

![Tinytris](/assets/img/0325/tinytris-2.png)
*Tinytris*

> ## [OpenJazz](https://archives.arosworld.org/?function=showfile&file=game/platform/openjazz.x86_64-aros-v11.zip) (v. 20240919) `x86_64`
> (autor: AlisterT)

OpenJazz to open-source’owy silnik umożliwiający uruchamianie gry Jazz Jackrabbit, klasycznej platformówki z 1994 roku stworzonej przez Epic MegaGames. Nie zawiera oryginalnych plików gry – użytkownik musi posiadać oryginalne dane z Jazz Jackrabbit, aby uruchomić OpenJazz. Można je zdobyć legalnie, korzystając z platformy GOG lub innych legalnych źródeł.

![OpenJazz](/assets/img/0325/openjazz-2.png)
*OpenJazz*

> ## [Biniax 2](https://archives.arosworld.org/?function=showfile&file=game/puzzle/biniax2.x86_64-aros-v11.zip) (v. 1.3) `x86_64`
> (autor: Jordan Tuzsuzov)

Biniax 2 to gra logiczna stworzona przez Jordana Tuzsuzova, będąca kontynuacją gry Biniax. Gra została wydana w 2007 roku i zdobyła uznanie za swoją unikalną rozgrywkę oraz dostępność na wielu platformach.​

Gracz steruje elementem o określonym kolorze, poruszając się po planszy wypełnionej parami kolorowych elementów. Celem jest dopasowanie i usunięcie par tych samych kolorów, co przynosi punkty. Gra kończy się, gdy nie ma już dostępnych ruchów. 

![Biniax 2](/assets/img/0325/Biniax2-2.png)
*Biniax 2*

> ## [GNU Robbo](https://archives.arosworld.org/?function=showfile&file=game/puzzle/gnurobbo.x86_64-aros-v11.zip) (v. 0.68) `x86_64`
> (autor: Arkadiusz Lipiec)

GNU Robbo to darmowa, otwartoźródłowa reimplementacja klasycznej gry logiczno-zręcznościowej "Robbo", stworzonej przez Janusza Pelca i wydanej przez firmę LK Avalon w 1989 roku na komputery Atari XE/XL. ​

Zmiany w rozgrywce w porównaniu do oryginału:
- Usunięcie systemu żyć: zamiast tego wprowadzono możliwość restartu poziomu.​
- Brak systemu punktacji: celem jest przejście kolejnych poziomów.​
- Poprawiona logika przeciwników: np. niedźwiedzie nie kręcą się bez końca wokół siebie.​
- Zmiany w mechanice gry: np. kapsuły nie pojawiają się z znaków zapytania, a lasery nie pozostają aktywne po zniszczeniu działa.   ​

![GNU Robbo](/assets/img/0325/GNURobbo-2.png)
*GNU Robbo*

> ## [Blips](https://archives.arosworld.org/?function=showfile&file=game/puzzle/blips.x86_64-aros-v11.zip) (v. 1.0) `x86_64`
> (autor:	Willems Davy, Bryant Brownell)

"Blips" to gra logiczna w stylu sokobana, stworzona pierwotnie przez Bryanta Brownella na platformę DOS. W grze gracze wcielają się w postać, której celem jest zebranie wszystkich monet na danym poziomie. Aby to osiągnąć, należy przesuwać skrzynie, tworząc ścieżki do monet, a także korzystać z dynamitu do niszczenia przeszkód. Gra składała się z 26 poziomów, oferując wyzwanie dla miłośników łamigłówek.

Nowa wersja zachowuje podstawowe mechaniki oryginału, jednocześnie wprowadzając ulepszoną grafikę i dostosowanie do współczesnych platform. Remake oferuje również edytor poziomów, pozwalając graczom na tworzenie własnych wyzwań. 

![Blips](/assets/img/0325/Blips-2.png) 
*Blips*

> ## [Hydra Castle Labyrinth](https://archives.arosworld.org/?function=showfile&file=game/platform/hydracastle.x86_64-aros-v11.zip) (v. 02/2024) `x86_64`
> (autorzy:	E. Hashimoto, ptitSeb)

"Hydra Castle Labyrinth" to darmowa gra z gatunku metroidvania, stworzona przez japońskiego twórcę E. Hashimoto, znanego również jako Buster, i wydana w 2011 roku. Gracz wciela się w rycerza eksplorującego rozległy, labiryntowy zamek w poszukiwaniu skarbów i potężnych artefaktów, walcząc z różnorodnymi przeciwnikami i bossami.

Gra oferuje rozległy świat pełen ukrytych przedmiotów i sekretów, zachęcając do dokładnego badania każdego zakątka zamku.​ Podczas przygody gracz zdobywa różnorodne przedmioty, takie jak broń, tarcze czy klucze, które umożliwiają dostęp do nowych obszarów i ułatwiają walkę z przeciwnikami.​ W zamku znajduje się osiem lochów, z których każdy kończy się starciem z unikatowym bossem. Pokonanie ich jest kluczowe dla postępu w grze.

![Hydra Castle Labyrinth](/assets/img/0325/hydracastlelabyrinth-2.png)
*Hydra Castle Labyrinth*

> ## [Sokoban GP2X](https://archives.arosworld.org/?function=showfile&file=game/puzzle/sokobangp2x.x86_64-aros-v11.zip) (v. 08032025) `x86_64`
> (autor:	Willems Davy)

Sokoban GP2X to remake klasycznej gry logicznej Sokoban, stworzony przez Willemsa Davy'ego dla przenośnej konsoli GP2X. W grze gracz wciela się w postać, której zadaniem jest przesuwanie skrzyń na wyznaczone miejsca w labiryncie. Po umieszczeniu wszystkich skrzyń na właściwych pozycjach poziom zostaje ukończony.

Gra oferuje ponad 800 poziomów, podzielonych na różne zestawy, takie jak "Microcosmos", "Minicosmos", "Nabokosmos", "Picokosmos", "Polycosmos", "Lomas", "Gameboy Boxxle (1+2)", "Sokevo" i "Sokhard". ​Wbudowane narzędzie pozwala graczom tworzyć własne zestawy poziomów.
- Możliwość dostosowywania grafiki oraz kolorów menu dla każdego zestawu poziomów.​
- Obsługa do 25 własnych plików muzycznych w formatach MOD lub OGG, które można odtwarzać podczas rozgrywki.​
- Możliwość cofnięcia do 1000 ostatnich ruchów, co jest pomocne przy rozwiązywaniu trudniejszych łamigłówek.

![Sokoban GP2X](/assets/img/0325/sokobangp2x-2.png)
*Sokoban GP2X*

> ## [Open Tyrian](https://archives.arosworld.org/?function=showfile&file=game/platform/hydracastle.x86_64-aros-v11.zip) (v. 02/2024) `x86_64`
> (autor:	Carl W. Reinke)

OpenTyrian to open-source’owy port klasycznej strzelanki Tyrian, pierwotnie wydanej w 1995 roku przez Eclipse Software i Epic MegaGames. OpenTyrian opiera się na otwartym silniku, który umożliwia uruchamianie gry na współczesnych systemach operacyjnych.

Gracz wciela się w pilota Trenta Hawkinsa, który walczy przeciwko złowrogiej korporacji Microsol, chcącej przejąć kontrolę nad galaktyką. W trakcie gry można ulepszać swój statek, dodając nowe bronie, osłony i systemy pomocnicze.

OpenTyrian wiernie odwzorowuje oryginalne mechaniki gry, oferując dynamiczną rozgrywkę typu shoot 'em up. Usuwa ograniczenia sprzętowe DOS i dodaje wsparcie dla nowoczesnych kontrolerów oraz wyższych rozdzielczości. Gra oferuje Kampanię fabularną i tryb Arcade, w którym gracze mogą szybko wskoczyć do akcji. Oryginalne pliki gry zostały udostępnione jako freeware, więc OpenTyrian można pobrać i grać legalnie.

![Open Tyrian](/assets/img/0325/opentyrian-2.png)
*Open Tyrian*

> ## [xRick](https://archives.arosworld.org/?function=showfile&file=game/platform/xrick.x86_64-aros-v11.zip) (v. 021212) `x86_64`
> (autor:	BigOrno)

XRick to open-source’owy port klasycznej gry platformowej Rick Dangerous, wydanej pierwotnie w 1989 roku przez Core Design.

W grze wcielamy się w postać Rick Dangerousa, archeologa inspirowanego Indianą Jonesem. Akcja rozpoczyna się w Amazonii, gdzie Rick musi uciec przed tubylcami. Podczas swojej przygody odwiedza m.in. egipskie piramidy, bazę nazistów oraz tajną kwaterę wulkaniczną. Gracz eksploruje poziomy, unika pułapek i walczy z wrogami, używając pistoletu oraz dynamitu.

![xRick](/assets/img/0325/xRick-2.png)
*xRick*

> ## [REminiscence](https://archives.arosworld.org/?function=showfile&file=game/platform/reminiscence.x86_64-aros-v11.zip) (v. 0.3.2) `x86_64`
> (autor:	Gregory Montoir)

REminiscence to port gry "Flashback" – klasycznej gry akcji i platformowej z 1992 roku, stworzonej przez Delphine Software. Jest to projekt open-source, który pozwala na uruchomienie oryginalnej gry Flashback na współczesnych systemach operacyjnych bez potrzeby emulacji.

Flashback opowiada historię Conrada B. Harta, który budzi się na obcej planecie z utratą pamięci. Jego zadaniem jest ucieczka przed niebezpieczeństwem i odkrycie tajemnicy, która stoi za jego amnezją. Gra oferuje różnorodne poziomy, pełne akcji, rozwiązywania zagadek i unikania pułapek.

![REminiscence](/assets/img/0325/REminiscence-2.png)
*REminiscence*

> ## [filesysbox.library](https://archives.arosworld.org/?function=showfile&file=library/misc/filesysbox.i386-aros.lha) (v. 54.5) `i386`
> (autorzy:	Leif Salomonsson, Fredrik Wikstrom)

Filesysbox.library to warstwa systemu plików zgodna z FUSE. Pierwotnie opracowana przez przez Leifa Salomonssona. Zarządza blokadami, powiadomieniami, uchwytami plików, pakietami, limitami czasu aktualizacji i nie tylko, uwalniając system plików od tych zadań. Wersja 0.730 biblioteki została wydana jako open source i została wykorzystana jako podstawa dla tej wersji.  

