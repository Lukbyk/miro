# Podstrony i RODO

Źródło: `biblioteka_promptow/28_w6_prywatnosc_strony.md` (W6 · P7). Treść: wersja wklejona przez użytkownika 2026-10-12, zgodna z biblioteką.
Dostosowanie do pracy na komputerze: zasady w `miro.md`.

## Treść promptu

~~~~text
@coo

Pomóż mi przygotować elementy prywatności strony. To materiał edukacyjny do weryfikacji prawnej, nie zapewnienie zgodności z RODO. Sam baner nie oznacza zgodności. Nie wymyślaj danych firmy, podstaw prawnych, okresów przechowywania ani dostawców.

Pracuj w folderze strony z zadania 2. Przeczytaj index.html, strona.md, README.md, istniejące podstrony i publikacja.md. Potrzebne dane firmy odczytaj z profil.md i oferta.md, ale nie kopiuj całych plików na stronę.

Sprawdź faktyczne działanie: formularze, płatności, analitykę, piksele, filmy, czat, zewnętrzne zasoby, cookies i localStorage. Zapytaj tylko o brakujące dane firmy i kontakt, kraj działalności, hosting, odbiorców danych, używane usługi i istniejącą zatwierdzoną politykę. Rozróżnij kod, który widzisz, od konfiguracji hostingu, której nie możesz sprawdzić.

Przygotuj:

1. polityka-prywatnosci.html i cookies.html, dopasowane do potwierdzonych funkcji. Zachowaj moje zatwierdzone dokumenty zamiast zastępować je szablonem; wskaż zmiany do sprawdzenia. Braki oznacz w wersji roboczej i zatrzymaj publikację do ich rozstrzygnięcia.
2. Względne linki do podstron w stopce i powrót na stronę główną. Zachowaj ofertę, obrazy i wygląd; bez pustych linków #.
3. Dla narzędzi wymagających zgody zaproponuj mechanizm rzeczywiście sterujący uruchamianiem. Jeśli brak takich narzędzi, nie dodawaj fikcyjnych kategorii i banera tylko dla wyglądu; opisz ustalenie i zakres do weryfikacji prawnej.

Jeśli wdrażamy baner:

- Krótki opis i link do informacji o cookies. Przyciski „Akceptuj wszystkie”, „Tylko niezbędne”, „Ustawienia” równie łatwo dostępne, bez sugerowania zgody wyglądem.
- Kategorie odpowiadają faktycznym narzędziom, opcjonalne domyślnie wyłączone. Nie uznawaj narzędzia za niezbędne tylko dlatego, że pomaga firmie.
- Przed zgodą i po odmowie nie ładuj skryptów ani osadzeń wymagających zgody. Sam zapis w localStorage i ukrycie banera nie wystarczą.
- Zapis i odczyt wyboru oraz „Ustawienia cookies” w stopce pozwalające równie łatwo zmienić lub wycofać zgodę. Po wycofaniu zatrzymaj dalsze uruchamianie opcjonalnych narzędzi; usuń dostępne własne identyfikatory. Nie obiecuj usunięcia danych u dostawcy bez odpowiedniego procesu.
- Obsługa klawiatury, telefonu i błędu localStorage; błąd zapisu nie może zmienić braku zgody w zgodę. Nie zasłaniaj na stałe treści.

Przed zapisem pokaż zmiany, braki i ograniczenia. Zapytaj o zgodę, zrób kopię zmienianych plików poza paczką publikacji, następnie zapisz. Nie podłączaj nowych dostawców i nie publikuj przy tej zgodzie.

Sprawdź nową wizytę bez wyboru, odmowę, zgodę na wybraną kategorię, zmianę i wycofanie zgody, odświeżenie, linki oraz telefon. Sprawdź żądania sieciowe, nie sam wygląd banera. Jeśli nie możesz, nazwij brak weryfikacji i poproś mnie o test w przeglądarce.

Pokaż, co powstało i co wymaga sprawdzenia przez prawnika. Zaktualizuj po mojej zgodzie README.md. Skieruj mnie do zadania 6: przebuduj strona.zip z index.html, assets/ i obiema zatwierdzonymi podstronami. Ponowna publikacja wymaga osobnej zgody; nie kończ na lokalnym zapisie.
~~~~
