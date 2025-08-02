---
layout: post
title: AROS x86 - lipiec 2025
subtitle: podsumowanie miesiąca
lang: pl
ref: 0725
---

Lato to dla deweloperów AROSa czas wypoczynku wśród palm, gorącego piasku i... pięknych commitów. Nawet podczas wakacyjnego relaksu potrafią znaleźć chwilę, by wprowadzić zmiany do kodu. Co przyniósł nam więc lipiec?

Nick „Kalamatee” Andrews jak zwykle nie próżnował. Wprowadził całą serię poprawek w różnych częściach systemu – od systemu kompilacji, przez bibliotekę C, datatypy, aż po sterowniki. Lista zmian jest naprawdę imponująca, dlatego wszystkich ciekawych szczegółów zapraszam do [pełnego zestawienia na GitHubie](https://github.com/aros-development-team/AROS/commits?author=Kalamatee&since=2025-07-01&until=2025-07-31).

Jednym z jego najnowszych projektów jest QuickPart – świeże narzędzie do partycjonowania dysków. Na razie działa w trybie tylko do odczytu, co oznacza, że można przeglądać istniejące partycje, ale jeszcze ich nie modyfikować. Zapowiada się jednak na naprawdę praktyczne i nowoczesne rozwiązanie!

![Quickpart](/assets/img/0725/quickpart.png)  
*AROS Quick Part*

Osobiście najbardziej ucieszyła mnie wiadomość o rozpoczęciu prac nad portem biblioteki SDL2 dla AROSa. Dotychczasowy SDL 1.2, choć zasłużony, swoje lata już ma – i nie da się ukryć, że AROS w tym aspekcie został nieco w tyle. Przejście na SDL2 otwiera drzwi do całej fali nowych portów gier i aplikacji, które z tej biblioteki korzystają. Zapowiada się świetna zabawa – zwłaszcza dla programistów! Już teraz można testować pierwsze wersje (choć wsparcie dla OpenGL nie jest jeszcze dostępne). 

<iframe width="700" height="480" src="https://www.youtube.com/embed/VzzCPzGYTVs" title="AROS64 UEFI Test" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>  
*https://www.youtube.com/@Kalamatee*
<a href="https://github.com/sponsors/NAZWA_UZYTKOWNIKA" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Sponsoruj_na_GitHub-💖-pink?logo=github" alt="Sponsoruj na GitHub" style="height: 40px;">
</a>

![GitHub Sponsors](https://img.shields.io/github/sponsors/:Kalamatee)



Nie próżnują też inni deweloperzy – coś się kroi i niewykluczone, że wkrótce zostaniemy miło zaskoczeni. A tymczasem zobaczmy, co nowego trafiło w czerwcu do AROS Archives:

> ## [InstallerLG](https://archives.arosworld.org/?function=showfile&file=utility/installerlg-v1.0.3.x86_64-aros-v11.zip) (v. 1.0.3) `x86_64`
> (autor:	Ola Söder)

InstallerLG

> ## [HivelyReplayer](https://archives.arosworld.org/?function=showfile&file=audio/play/hivelyreplay.x86_64-aros-v11.zip) (v. 0.2) `x86_64`
> (autor:	Peter Gordon)

HivelyReplayer

> ## [UHCTools](https://archives.arosworld.org/?function=showfile&file=utility/misc/uhctools.i386-aros.lha) (v. 2.1) `i386`
> (autorzy:	Patrik Axelsson / David Eriksson)

UHCTools

> ## [V.A.M.P.](https://archives.arosworld.org/?function=showfile&file=video/play/vamp.lha) (v. 3.25) `i386`
> (autorzy:	Templario & Samo79)

libmikmod

