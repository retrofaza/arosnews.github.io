---
layout: post
title: AROS x86 - sierpień 2025
subtitle: podsumowanie miesiąca
lang: pl
ref: 0825
---

Lato to dla deweloperów AROSa czas wypoczynku wśród palm, gorącego piasku i... pięknych commitów. Nawet podczas wakacyjnego relaksu potrafią znaleźć chwilę, by wprowadzić zmiany do kodu. Co przyniósł nam więc lipiec?

Nick **Kalamatee** Andrews jak zwykle nie próżnował. Wprowadził całą serię poprawek w różnych częściach systemu – od systemu kompilacji, przez bibliotekę C, datatypy, aż po sterowniki. Lista zmian jest naprawdę imponująca, dlatego wszystkich ciekawych szczegółów zapraszam do [pełnego zestawienia na GitHubie](https://github.com/aros-development-team/AROS/commits?author=Kalamatee&since=2025-07-01&until=2025-07-31).

Jednym z jego najnowszych projektów jest **QuickPart** – świeże narzędzie do partycjonowania dysków. Na razie działa w trybie tylko do odczytu, co oznacza, że można przeglądać istniejące partycje, ale jeszcze ich nie modyfikować. Zapowiada się jednak na naprawdę praktyczne i nowoczesne rozwiązanie!

![Quickpart](/assets/img/0725/quickpart.png)  
*AROS Quick Part*

Osobiście najbardziej ucieszyła mnie wiadomość o rozpoczęciu prac nad portem biblioteki **SDL2 dla AROSa**. Dotychczasowy SDL 1.2, choć zasłużony, swoje lata już ma – i nie da się ukryć, że AROS w tym aspekcie został nieco w tyle. Przejście na SDL2 otwiera drzwi do całej fali nowych portów gier i aplikacji, które z tej biblioteki korzystają. Zapowiada się świetna zabawa – zwłaszcza dla programistów! Już teraz można testować pierwsze wersje (choć wsparcie dla OpenGL nie jest jeszcze dostępne).  

Kalamatee na pewno będzie miło, jeśli wesprzesz jego pracę na Githubie:  
[![GitHub Sponsors](https://img.shields.io/github/sponsors/Kalamatee)](https://img.shields.io/github/sponsors/Kalamatee?style=flat
)  
<iframe width="700" height="480" src="https://www.youtube.com/embed/VzzCPzGYTVs" title="AROS64 UEFI Test" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
*https://www.youtube.com/@Kalamatee*

Krzysztof **Deadwood** Śmiechowicz, oprócz intensywnych prac nad nową wersją przeglądarki Odyssey, podjął się realizacji kolejnego ambitnego przedsięwzięcia. Rozpoczął prace nad portem emulatora klasycznej **Amigi** na 64-bitowy system AROS. Projekt znajduje się na wczesnym etapie rozwoju, a jego fundamentem najprawdopodobniej będą źródła emulatora Amiberry.

![Quickpart](/assets/img/0725/amiberry3.png)  
*AROS Amiberry*

**Deadwood**, jak co kwartał, przedstawił zaktualizowany plan rozwoju systemu 64-bit, z którym można [zapoznać się tutaj](https://www.arosworld.org/infusions/forum/viewthread.php?thread_id=1114&rowstart=40&pid=8777#post_8769). W krótkim terminie opiera się on na trzech kierunkach:

Po pierwsze, trwają intensywne prace nad przeglądarką Odyssey – celem jest jej unowocześnienie, aby stabilnie i szybko obsługiwała współczesne usługi online, co pozwoli zastąpić brakujące aplikacje ich internetowymi odpowiednikami.

Po drugie, uzupełniane są braki w oprogramowaniu – poprzez rekompilację lub emulację dodawane są niezbędne funkcjonalności, tak aby w każdej kategorii dostępne było przynajmniej jedno dobrze działające narzędzie.

Po trzecie, poprawiana jest obsługa sprzętu – obecnie system 64-bitowy nie wspiera jeszcze części urządzeń dostępnych w wersji 32-bitowej (np. kart NVidia). Celem jest przywrócenie tego wsparcia oraz rozszerzenie go o nowszy, łatwo dostępny sprzęt z drugiej ręki.

Timothy **Terminills** Deters zapowiedział wydanie własnej 64-bitowej dystrybucji AROS (ABIv1). Mocną stroną ma być załączenie do niej pełnej wersji **FinalWritera**. Na razie nie jest jeszcze ujawniona nazwa nowej dystrybucji, czekamy na dalsze informacje w tym temacie.

**Amigamia**, administrator forum **AROSWorld**, przywrócił z kopii zapasowej archiwalne fora dyskusyjne poświęcone AROS-owi. To prawdziwa skarbnica wiedzy — można tam nie tylko powspominać, jak wyglądały dawne rozmowy społeczności, ale też znaleźć wiele przydatnych informacji, które wciąż pozostają aktualne.

Dostępne archiwa (tylko do odczytu):
- [aros-exec.arosworld.org](https://aros-exec.arosworld.org/)
- [ae.arosworld.org](https://ae.arosworld.org/)

Przypominam, że aktywne i aktualne forum AROS-a działa pod adresem: [www.arosworld.org](https://www.arosworld.org/) — serdecznie zapraszam do udziału w dyskusji!

Sezon wakacyjny daje o sobie znać szczególnie w AROS Archives – tym razem nowych pozycji jest tak niewiele, że można je policzyć na palcach jednej ręki. Miejmy jednak nadzieję, że w przyszłym miesiącu zaległości zostaną nadrobione z nawiązką :)


> ## [Super-Haxagon](https://archives.arosworld.org/?function=showfile&file=game/action/super-haxagon.x86_64-aros-v11.zip) (v. 3.9.1) `x86_64`
> (autor:	AJ Walter)

Super Hexagon to intensywna i niezwykle wymagająca minimalistyczna gra zręcznościowa autorstwa Terry'ego Cavanagha. Gracz steruje niewielkim trójkątem, omijając nadciągające przeszkody w rytm hipnotycznej, elektronicznej ścieżki dźwiękowej Chipzela. Jej psychodeliczna, pulsująca estetyka i perfekcyjne zsynchronizowanie muzyki z działaniem tworzą wciągające, choć bezlitosne doświadczenie. Dostępna na PC i urządzenia mobilne, gra słynie z przytłaczająco pozytywnych recenzji, a jej nieubłagany poziom trudności i mechanika „jeszcze jednej próby” stanowią idealny test refleksu i koncentracji. Wersja dla AROS oparta jest o otwartoźródłową implementację gry (Super-Haxagon) autorstwa AJ Waltera.

![Super-Haxagon](/assets/img/0825/haxagon.png)
*Super-Haxagon*

> ## [TBFTSS: The Pandora War](https://archives.arosworld.org/?function=showfile&file=game/action/tbftss.x86_64-aros-v11.zip) (v. 1.5.1) `x86_64`
> (autor:	Stephen J Sweeney)

"The Battle for the Solar System: The Pandoran War" to dwuwymiarowy space shooter osadzony w uniwersum science fiction znanym z serii powieści. Rozgrywka, rozgrywająca się pomiędzy tomami książkowej trylogii, pozwala pilotować różnorodne statki kosmiczne – w tym kultowe jednostki z sagi oraz zupełnie nowe modele – w ponad 60 nieliniowych misjach. Gracz angażuje się w intensywne potyczki, wykorzystując zdolności taktyczne i współpracując z AI, aby stawić czoła piratom, zdrajcom oraz potężnej armii Pandory. Dzięki systemowi trofeów, bogatej fabule, gra stanowi gratkę zarówno dla miłośników klasycznych strzelanin, jak i fanów głębokiego, literackiego science-fiction. 

![TBFTSS](/assets/img/0825/tbftss.png)
*The Battle for the Solar System: the Pandora War*

> ## [Tilt-N-Roll](https://archives.arosworld.org/?function=showfile&file=game/action/tiltnroll.x86_64-aros-v11.zip) (v. 1.2.0) `x86_64`
> (autor:	Greg Kennedy)

Tilt-n-Roll to trójwymiarowa wersja klasycznej gry z kulką, stworzona w technologii OpenGL. Kierujesz kątem nachylenia poziomu za pomocą myszki lub klawiatury. Obracając świat, możesz poprowadzić kulkę przez różne przeszkody do wyjścia. Gra ma wbudowany edytor poziomów - może być używany do tworzenia i dystrybucji poziomów wśród znajomych. Świetna propozycja dla tych, którzy szukają nietypowego, lekkiego wyzwania z ciekawym pomysłem na sterowanie.

![Tilt-N-Roll](/assets/img/0825/tiltnroll.png)
*Tilt-N-Roll*

> ## [RNOSoundboard](https://archives.arosworld.org/?function=showfile&file=audio/play/rnosoundboard.i386-aros.lha) (v. 1.0) `i386`
> (autor:	jPV^RNO)

RNOSoundboard

![RNOSoundboard](/assets/img/0825/rnosoundboard.jpg)
*RNOSoundboard*


|----------|-----------------------------------------------------------------------------------------------|-------------------------------------|
| `x86_64` | [InstallerLG v.1.0.3](https://archives.arosworld.org/?function=showfile&file=utility/installerlg-v1.0.3.x86_64-aros-v11.zip) | Commodore Installer replacement |
| `x86_64` | [HivelyReplayer v.0.2](https://archives.arosworld.org/?function=showfile&file=audio/play/hivelyreplay.x86_64-aros-v11.zip) | Replayer from HivelyTracker (AHI) |
| `i386` | [UHCTools v.2.1](https://archives.arosworld.org/?function=showfile&file=utility/misc/uhctools.i386-aros.lha) | a collection of program and scripts |
| `i386` | [V.A.M.P. v.3.25](https://archives.arosworld.org/?function=showfile&file=video/play/vamp.lha) | Virtual Amiga Multimedia Player |

