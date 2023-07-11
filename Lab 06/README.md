# Lab 6

1. Przyjmij następujący zbiór danych wejściowych:

   - bbb$
   - aabbabd
   - ababcd
   - abaababaabaabaabab$
   - losowy tekst o długości 100 znaków,
   - załączony plik.

2. Upewnij się, że każdy łańcuch na końcu posiada unikalny znak (marker), a jeśli go nie ma, to dodaj ten znak.
3. Zaimplementuj algorytm konstruujący strukturę trie, która przechowuje wszystkie sufiksy łańcucha danego na wejściu.
4. Zaimplementuj algorytm konstruujący drzewo sufiksów.
5. Upewnij się, że powstałe struktury danych są poprawne. Możesz np. sprawdzić, czy struktura zawiera jakiś ciąg znaków i porównać wyniki z algorytmem wyszukiwania wzorców.
6. Porównaj szybkość działania algorytmów konstruujących struktury danych dla danych z p. 1 w następujących wariantach:
   1. Trie - w wariancie, w którym kolejne sufiksy dodawane są przez przeszukiwanie głowy od korzenia drzewa (1p.),
   2. Trie - w wariancie, w którym kolejne sufiksy dodawane są poprzez dodanie kolejnej litery tekstu (1p.),
   3. Drzewo sufiksów - algorytm Ukkonena (3p).
7. Dla załączonego tekstu czas wariantów 1 i 2 może być nieakceptowalnie długi - w tej sytuacji pomiń wyniki pomiarów dla tego tekstu.
8. Oczekiwany wynik ćwiczenia to kod źródłowy oraz raport w formie PDF.
