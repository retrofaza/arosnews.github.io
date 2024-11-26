---
layout: post
title: AROS x86 - listopad 2024
subtitle: podsumowanie miesiąca
lang: pl
ref: 1124
---


{: .box-success}
Aby pobrać ISO systemu oraz update 2 i zapoznać się z pełną listą zmian, odwiedź:  
[https://github.com/deadwood2/AROS/releases/tag/ABIv0_20220318-1](https://github.com/deadwood2/AROS/releases/tag/ABIv0_20220318-1)


<div class="embed-container">
<iframe width="700" height="480" src="https://www.youtube.com/watch?v=haT1RsF7ZyM" frameborder="0"> </iframe>
</div>


Pozostałe nowości w AROS Archives:  

> ## [SilkRAW](https://archives.aros-exec.org/?function=showfile&file=graphics/misc/silkraw_aros.lha) (v. 3.0)
> (autor:	Domenico Lattanzi)

SilkRAW to program umożliwiający pracę z plikami RAW generowanymi przez lustrzanki cyfrowe, działający jako interfejs do programu dcRAW napisanego przez Dave'a 
Coffina (Należy ściągnąć [dcRAW](https://archives.aros-exec.org/?function=showfile&file=graphics/convert/dcraw.i386-aros.zip) i umieścić go w szufladzie programu SilkRAW). 

Funkcje:  
- Eksport miniatur, pojedynczych plików RAW lub grup, z metadanymi możliwości wyodrębniania i obracania 
- 25 obsługiwanych opcji dcRAW
- Przetwarzanie wsadowe plików RAW z zapisem w formatach TIFF, PPM, JPG, PNG, ILBM
- Dalsze przetwarzanie poza dcRAW  

![SilkRAW](/assets/img/1124/silkraw.png)
*SilkRAW*

> ## [UHCTools](https://archives.aros-exec.org/?function=showfile&file=utility/misc/uhctools.i386-aros.lha) (v. 1.8)
> (autorzy: Patrik Axelsson, David Eriksson)

Jest to zbiór programów i skryptów dla komputerów Amiga i ich pochodnych, aby uprościć codzienne użytkowanie i uczynić Amigę bardziej niezależną.

![UHCTools](/assets/img/1124/uhctools.png)
*UHCTools*

> ## [Legadon](https://home.alb42.de/files/Legadon03_AROS.lha) (v. 0.3)
> (autor: ALB42)

Prosty czytnik ePub dla AROS. ePuby to po prostu pliki zip z plikami XML i HTML, które opisują książkę elektroniczną. Legadon wyodrębnia tekst z HTML i pokazuje go użytkownikowi jako plain tekst w polu tekstowym.

> ## [CabExtract](https://archives.aros-exec.org/?function=showfile&file=utility/archive/cabextract1.11.i386-aros.zip) (v. 1.11)
> (autor: Stuart Caie, port by Farox)

Program do rozpakowywania plików Microsoft Cabinet. Pliki Cabinet (`.CAB`) są formą archiwum, którego Microsoft używa do dystrybucji swojego oprogramowania i rzeczy takich jak Windows Font Packs. Program cabextract rozpakowuje te pliki.

> ## [Unshield](https://archives.aros-exec.org/?function=showfile&file=utility/archive/unshield.i386-aros.zip) (v. 1.5.1)
> (autor:	David Eriksson, port by Farox)

Narzędzie do wyodrębniania plików `.CAB` z pliku `.exe` InstallShield.

> ## [SetScreenMode](https://archives.aros-exec.org/?function=showfile&file=utility/shell/setscreenmode.i386-aros.zip) (v. 1.0)
> (autor:	Nigel Tromans)

Set_Screen_Mode to mała aplikacja Hollywood do automatycznego ustawiania tryb ekranu podczas uruchamiania z wcześniej ustawionej listy.  

Uwaga: Set_Screen_Mode jest przydatny tylko wtedy, gdy instalacja AROS jest wykorzystuje natywną grafikę.  

Została stworzona, aby umożliwić maszynom, które są przenoszone między różnymi wyświetlaczami (takimi jak laptopy z wewnętrznym ekranem i zewnętrznie podłączonymi monitorami) automatycznie uruchamiać się w preferowanym trybie ekranu dla każdego z tych wyświetlaczy, a także pomóc w wyświetlaniu ekranu na ekranach, które są trudne do w użyciu (na przykład takich, które nie są w stanie wyświetlić domyślnego trybu 640x480).  

Set_Screen_Mode odczyta dostępne tryby ekranu dostarczone przez przez wyświetlacz i porówna je z trybami wybranymi przez użytkownika na uporządkowanej liście. Możliwe jest również wymuszenie trybu, nawet jeśli nie ma go na liście lub całkowicie zignorować tryby ustawione dla Set_Screen_Mode.  


