Zadanie 3. Słowa
=================

W pliku `slowa.txt` podane jest n (1 <= n <= 500000) słów złożonych z małych liter alfabetu angielskiego. Suma długości słów nie przekracza 10000000. Napisz program, dający odpowiedzi do poniższych zadań. Uzyskane odpowiedzi wypisz w konsoli lub zapisz w pliku `wyniki.txt`.

### Zadanie 1
Podaj, w ilu spośród podanych słów znajduje się trójliterowy fragment "k?t", gdzie ? oznacza dowolną pojedynczą literę (taki fragment występuje na przykład w słowach "alamakota", albo "brokat", ale nie w słowa "krata").

### Zadanie 2
Alfabet angielski zawiera 26 liter. Kodowanie ROT13 zamienia każdą literę na literę, która jest na pozycji o 13 miejsc dalej w alfabecie (a &rarr; n, b &rarr; o itd.), przy czym po przekroczeniu "z" liczymy z powrotem od "a" (czyli m &rarr; z, ale n &rarr; a, o &rarr; b i tak dalej).

Słowo **aren** ma ciekawą własność &mdash; po zakodowaniu za pomocą ROT13 staje się słowem **nera**, czyli tym samym słowem czytanym od tyłu. Podaj, ile w pliku `slowa.txt` jest słów, które mają tę własność. 

Jako odpowiedź podaj:
W pierwszym wierszu &mdash; liczbę słów w pliku `slowa.txt`, które mają taką własność.
W drugim wierszu &mdash; najdłuższe, spośród tych słów. 

### Zadanie 3
Znajdź i wypisz z pliku `slowa.txt` wszystkie takie słowa, w których ta sama litera występuje na co najmniej połowie pozycji.

Przykładowo: 
* w słowie "owocowo" litera "o" ma 4 wystąpienia na ogólną liczbę 7 liter w słowie, zatem spełnia podany warunek
* w słowie "ambaras" litera "a" ma tylko 3 wystąpienia na 7 liter, więc nie spełnia podanego warunku

Słowa te wypisz, w kolejności występowania i każde w osobnej linijce.