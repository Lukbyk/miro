# Aktualizacja oferty i planu po wycenie

Źródło: `biblioteka_promptow/09_aktualizacja_oferty_po_wycenie.md` (W3 · P3). Treść skopiowana bez zmian.
Dostosowanie do pracy na komputerze: zasady w `miro.md`.

## Treść promptu

~~~~text
\## CEL
Przeanalizuj wyniki Deep Research, a potem pomóż mi zdecydować, czy zmienić:
1\. `oferta.md`, czyli opis oferty, cenę, bonusy, pozycjonowanie albo uzasadnienie wartości.
2\. `plan.md`, czyli najbliższe działania wynikające z nowej ceny albo nowego pozycjonowania.
Nie aktualizuj nic automatycznie.
Najpierw pokaż rekomendację i zapytaj o zgodę.
Dopiero po mojej zgodzie wygeneruj pełną nową treść `oferta.md` i pełną nową treść `plan.md`.
\---
\## WAŻNE ZASADY
1\. Nie usuwaj niczego z oryginalnego `oferta.md`.
2\. Nie usuwaj niczego z oryginalnego `plan.md`.
3\. Jeśli coś trzeba zmienić, zachowaj oryginalną treść i dodaj aktualizację albo wyraźnie oznaczoną nową wersję sekcji.
4\. Jeśli aktualizujesz cenę, pokaż, z czego wynika zmiana.
5\. Jeśli aktualizujesz plan, dodaj działania wynikające z wyceny, na przykład test ceny, poprawa stacku, rozmowy z klientami, aktualizacja strony albo decyzja o pakietach.
6\. Nie wymyślaj cen, konkurentów, opinii, wyników ani terminów.
7\. Jeśli wynik Deep Research nie daje podstaw do zmiany ceny, powiedz to i nie wymuszaj aktualizacji.
\---
\## MATERIAŁY, KTÓRE MASZ WYKORZYSTAĆ
Przeczytaj:
1\. `oferta.md`, całość, bez skracania.
2\. `plan.md`, całość, bez skracania.
3\. Wyniki Deep Research wklejone na końcu tej instrukcji.
Jeśli nie widzisz `oferta.md`, poproś o wklejenie pełnej treści.
Jeśli nie widzisz `plan.md`, poproś o wklejenie pełnej treści.
Jeśli na końcu instrukcji nie ma wyników Deep Research, poproś o ich wklejenie.
\---
\## KROK 1: KRÓTKA ANALIZA WYNIKÓW
Na podstawie raportu z Deep Research pokaż:
\`\`\`markdown
\## ANALIZA WYCENY
1\. Obecna cena z [oferta.md](http://oferta.md "http://oferta.md"): [...]
2\. Rekomendowana cena z researchu: [...]
3\. Przedział bezpieczny: [...]
4\. Przedział premium: [...]
5\. Najważniejsze dowody z rynku:
   1\. [...]
   2\. [...]
   3\. [...]
6\. Największe ryzyko: [...]
7\. Mój wniosek: [...]
\`\`\`
Jeśli jakaś liczba nie ma źródła w Deep Research albo w plikach, oznacz ją jako `brak źródła`.
\---
\## KROK 2: REKOMENDACJA DECYZJI
Pokaż jedną rekomendację:
\`\`\`markdown
\## REKOMENDACJA
Decyzja: [zostawić cenę / zmienić cenę / zrobić pakiety / przetestować cenę]
Dlaczego:
1\. [...]
2\. [...]
3\. [...]
Co zmienić w [oferta.md](http://oferta.md "http://oferta.md"):
1\. [...]
2\. [...]
3\. [...]
Co dopisać do [plan.md](http://plan.md "http://plan.md"):
1\. [...]
2\. [...]
3\. [...]
\`\`\`
Nie proponuj wielu wariantów, jeśli jeden wariant jest wyraźnie najlepszy.
Jeśli sytuacja jest niejednoznaczna, pokaż maksymalnie dwa warianty.
\---
\## KROK 3: PYTANIE O ZGODĘ
Po rekomendacji zapytaj:
\`\`\`text
Czy mam przygotować nowe wersje `oferta.md` i `plan.md` na podstawie tej rekomendacji?
Odpowiedz:
1\. Tak, przygotuj oba pliki.
2\. Tak, ale zmień tylko [oferta.md](http://oferta.md "http://oferta.md").
3\. Tak, ale zmień tylko [plan.md](http://plan.md "http://plan.md").
4\. Nie, zostawiam bez zmian.
\`\`\`
Nie generuj nowych plików przed moją odpowiedzią.
\---
\## KROK 4: JEŚLI ZGODZĘ SIĘ NA [OFERTA.MD](http://OFERTA.MD "http://OFERTA.MD")
Wygeneruj pełną nową treść `oferta.md`.
Zasady:
1\. Zachowaj wszystkie istniejące sekcje.
2\. Zachowaj wszystkie istniejące informacje.
3\. Nie skracaj oryginalnej oferty.
4\. Nie usuwaj starej ceny bez śladu.
5\. Jeśli cena się zmienia, dodaj sekcję `Aktualizacja po analizie ceny`.
6\. Jeśli zmieniają się bonusy albo stack, dodaj je jako uzupełnienie, nie jako kasowanie poprzednich elementów.
7\. Jeśli czegoś nie da się ustalić, wpisz `do potwierdzenia`.
Format odpowiedzi:
\`\`\`markdown
\# NOWA TREŚĆ [oferta.md](http://oferta.md "http://oferta.md")
[pełna treść pliku [oferta.md](http://oferta.md "http://oferta.md") po aktualizacji]
\`\`\`
\---
\## KROK 5: JEŚLI ZGODZĘ SIĘ NA [PLAN.MD](http://PLAN.MD "http://PLAN.MD")
Wygeneruj pełną nową treść `plan.md`.
Zasady:
1\. Zachowaj wszystkie istniejące sekcje.
2\. Zachowaj wszystkie istniejące działania.
3\. Nie usuwaj starych celów ani notatek.
4\. Dodaj tylko rzeczy wynikające z analizy ceny i oferty.
5\. Najbezpieczniej dopisz krótką sekcję `Aktualizacja po wycenie`.
6\. Jeśli plan ma sekcje `Najbliższe 30 dni`, `Ten tydzień` albo `Dzisiaj`, możesz dopisać do nich nowe punkty, ale niczego nie kasuj.
7\. Nowe działania mają być konkretne i krótkie.
Przykładowe działania po wycenie:
1\. Przetestować nową cenę w rozmowie z klientem.
2\. Zaktualizować argumenty wartości w ofercie.
3\. Dodać brakujący bonus, jeśli wzmacnia obietnicę.
4\. Sprawdzić, czy persona akceptuje nowy poziom ceny.
5\. Przygotować wariant strony albo wiadomości sprzedażowej pod nową cenę.
Format odpowiedzi:
\`\`\`markdown
\# NOWA TREŚĆ [plan.md](http://plan.md "http://plan.md")
[pełna treść pliku [plan.md](http://plan.md "http://plan.md") po aktualizacji]
\`\`\`
\---
\## KROK 6: KONTROLA KOŃCOWA
Przed pokazaniem nowych treści sprawdź:
1\. Czy nic nie zniknęło z oryginalnego `oferta.md`.
2\. Czy nic nie zniknęło z oryginalnego `plan.md`.
3\. Czy każda nowa cena albo rekomendacja wynika z Deep Research.
4\. Czy plan zawiera działania, a nie tylko opis.
5\. Czy mogę od razu użyć wygenerowanej treści jako nowego `oferta.md` i nowego `plan.md`.
\---
\## WYNIKI DEEP RESEARCH
Wklej poniżej cały raport z Deep Research.
\`\`\`markdown
[TUTAJ WKLEJ WYNIKI DEEP RESEARCH]
\`\`\`
\## NA KONIEC
Pod każdym nowym plikiem napisz w dwóch, trzech punktach, co dodałeś i co zmieniłeś. Nowa cena jest hipotezą do sprawdzenia z klientem, nie faktem.
~~~~
