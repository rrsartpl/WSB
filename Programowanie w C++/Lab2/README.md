# Laboratorium 2 – Ciąg dalszy podstaw 

## Poruszane tematy z Sylabusa: 

* [Rekurencja](http://www.algorytm.edu.pl/rekurencja.html)

* [Sortowanie tablic ](https://pl.wikibooks.org/wiki/Kody_%C5%BAr%C3%B3d%C5%82owe/Sortowanie_b%C4%85belkowe)

* [Konwersje wartości różnych typów danych, rzutowanie](https://pl.wikibooks.org/wiki/C%2B%2B/Zmienne#Rzutowanie)

* [Używanie i deklarowanie przestrzeni nazw](https://pl.wikibooks.org/wiki/C%2B%2B/Przestrzenie_nazw)

* [Struktury danych](https://pl.wikibooks.org/wiki/C/Typy_z%C5%82o%C5%BCone#Struktury)

* [Funkcje inline](https://pl.wikibooks.org/wiki/C%2B%2B/Funkcje_inline)



## Zadania (10 pkt): 

1. (1 pkt) (1 pkt) Używając [rekurencji](http://www.algorytm.edu.pl/rekurencja.html), napisz program wyliczający silnię na podstawie liczby całkowitej wprowadzonej przez użytkownika. 

2. (2 pkt) Zdefiniuj strukturę o nazwie _Student_ i polach _Imie_ (typu _string_) i _NrIndeksu_ (typu _int_). W programie zainicjuj strukturę swoimi wartościami. Następnie zdefiniuj zmienną typu _float_ do której zrzutuj _NrIndeksu_ (używając _static_cast<>_, a nie rzutowania "w stylu C") i podziel przez 97. Wynik wyświetl na ekranie. 

3. (2 pkt) Napisz program, w którym zdefiniujesz swoją własną [przestrzeń nazw](https://pl.wikibooks.org/wiki/C%2B%2B/Przestrzenie_nazw), a w niej zdefiniujesz funkcję o nazwie _cout_ wyświetlającą na ekranie konsoli dowolny tekst (więcej niż jednowyrazowy) w kolorze czerwonym. Poproś użytkownika o podanie tego tekstu w konsoli, a następnie wypisz go z wykorzystaniem swojej funkcji _cout_  (w kolorze czerwonym) jak i z biblioteki standardowej _cout_ (w kolorze domyślnym). _Podpowiedź_: Pomocne może się okazać użycie funkcji [_std::getline()_](http://www.cplusplus.com/reference/string/string/getline/) i zapoznanie się z [forum](https://stackoverflow.com/questions/9158150/colored-output-in-c), jak koloryzować standardowe wyjście. 

4. (2 pkt) Stwórz 2 funkcje (_func1_ i _func2_), które mają identyczną definicję (np. rekurencyjne wyliczanie silni z _zadania 1_), ale niech _func1_ będzie zadeklarowana jako [_inline_](https://pl.wikibooks.org/wiki/C%2B%2B/Funkcje_inline), a _func2_ jako normalna (nie _inline_).  Następnie wywołaj w programie każdą z nich w pętli np. po 100 tysięcy razy. Użyj funkcji [_clock()_](https://pl.wikibooks.org/wiki/C/clock) ze standardowej biblioteki _<time>_ żeby zmierzyć czasy egzekucji każdej z funkcji. Wypisz oba czasy. Nie przejmuj się, że niekiedy _func1_ będzie szybsza, a niekiedy wolniejsza (obecne kompilatory mają optymalizacje, które powodują, że funkcje inline niekoniecznie są szybsze).  

5. (3 pkt) Zmodyfikuj program z _Zadania 4_ z _Laboratorium 1_ w taki sposób, aby po wczytaniu liczb wyświetlił na ekranie: 

    a) Tylko parzyste liczby 

    b) Wszystkie podane liczby, uszeregowane od najmniejszej do największej. _Podpowiedź_: Skorzystaj z [Sortowania Bąbelkowego](https://pl.wikibooks.org/wiki/Kody_%C5%BAr%C3%B3d%C5%82owe/Sortowanie_b%C4%85belkowe) 
