# Tworzenie oferty

Źródło: `biblioteka_promptow/05_oferta_od_zera.md` (W2 · P3A). Treść skopiowana bez zmian.
Dostosowanie do pracy na komputerze: zasady w `miro.md`.

## Treść promptu

~~~~text
@coo ## CEL
Stworzymy Twój plik [**oferta.md**](http://oferta.md "http://oferta.md") - kompletny opis Twojego produktu/usługi.
Opis powstaje z 10 elementów (lista niżej). Nie pytam o to, co już wiem z tej rozmowy.
\---
\## METODOLOGIA
\### KROK 0: PRZECZYTAJ PLIKI I TĘ ROZMOWĘ
Czytam:
1\. [**profil.md**](http://profil.md "http://profil.md") - Twoje kompetencje, zasoby
2\. [**persona.md**](http://persona.md "http://persona.md") - Twój klient + TOP 10 problemów
3\. **Tę rozmowę** - czy wyżej są wyniki generatora pomysłów?
\---
\### KROK 0.5: JEŚLI W TEJ ROZMOWIE SĄ POMYSŁY Z GENERATORA
1\. Pytam tylko: "Który pomysł rozwijamy? (jeśli nie wskażesz, biorę REKOMENDACJĘ #1)"
2\. Z karty wybranego pomysłu WYPEŁNIAM SAM elementy: nazwa, dla kogo, problem, format, co klient dostaje, cena, czas realizacji. NIE zadaję pytań o rzeczy, które są w karcie pomysłu.
3\. Dopytuję TYLKO o braki, zwykle: tagline, gwarancja, pozycjonowanie. Plus jedno pytanie kontrolne: "Coś z karty pomysłu zmieniamy (np. cenę)?"
4\. Przechodzę od razu do KROKU 2 (generowanie pliku).
Jeśli w rozmowie NIE ma pomysłów z generatora, przechodzę do KROKU 1 i zadaję wszystkie pytania po kolei.
\---
\### KROK 1: 10 PYTAŃ (tylko gdy nie ma pomysłów w rozmowie)
**Odpowiadaj krótko - 1-3 zdania na pytanie.**
\---
\#### PYTANIE 1: NAZWA
Jak nazywa się Twój produkt/usługa? (max 5 słów, chwytliwe)
\---
\#### PYTANIE 2: TAGLINE
Co klient dostaje w 1 zdaniu? (konkretny rezultat)
Przykład: "Automatyzacja raportów w 7 dni" / "Strategia content w 90 minut"
\---
\#### PYTANIE 3: DLA KOGO
Kto jest idealnym klientem? (1 zdanie)
Przykład: "Właściciele małych firm, którzy tracą 5h/tydzień na raporty"
\---
\#### PYTANIE 4: PROBLEM
Jaki główny ból rozwiązujesz? (z [persona.md](http://persona.md "http://persona.md"))
\---
\#### PYTANIE 5: FORMAT
Jaki format?
\- A) Usługa 1:1 (konsulting, coaching)
\- B) Produkt cyfrowy (ebook, szablon, kurs)
\- C) Warsztat (live, grupowy)
\- D) Done-for-you (robisz za klienta)
\- E) Subskrypcja (recurring)
\- F) Inny: [opisz]
\---
\#### PYTANIE 6: CO DOSTAJESZ
Co KONKRETNIE klient otrzymuje? (3-5 punktów)
Przykład:
\- Szablon raportu (Google Sheets)
\- Instrukcja wideo (30 min)
\- Prompt do AI
\- 1h konsultacji live
\---
\#### PYTANIE 7: CENA
Ile kosztuje? (PLN)
Model: jednorazowa / miesięczna / roczna?
\---
\#### PYTANIE 8: CZAS
Ile trwa realizacja? (od zakupu do dostarczenia)
Przykład: "7 dni" / "2 tygodnie" / "natychmiast"
\---
\#### PYTANIE 9: GWARANCJA
Czy oferujesz gwarancję? Jaką?
Przykład: "100% zwrotu w 14 dni" / "Poprawki do skutku" / "Brak gwarancji"
\---
\#### PYTANIE 10: POZYCJONOWANIE
Czym różnisz się od konkurencji? (1-2 zdania)
Przykład: "Jedyny kurs po polsku" / "Gwarancja rezultatu" / "10 lat doświadczenia w branży"
\---
\### KROK 2: GENEROWANIE [oferta.md](http://oferta.md "http://oferta.md")
Z odpowiedzi (i karty pomysłu, jeśli była) generuję plik:
\`\`\`markdown
\# OFERTA: [NAZWA]
\## TAGLINE
[tagline z odpowiedzi]
\## DLA KOGO
[dla kogo z odpowiedzi]
\## PROBLEM KTÓRY ROZWIĄZUJE
[problem z odpowiedzi]
Cytat persony: "[cytat z [persona.md](http://persona.md "http://persona.md")]"
\## FORMAT
[format z odpowiedzi]
\## CO KLIENT DOSTAJE
\- [punkt 1]
\- [punkt 2]
\- [punkt 3]
\- [punkt 4]
\- [punkt 5]
\## CENA
**[cena] PLN** ([model płatności])
\## CZAS REALIZACJI
[czas z odpowiedzi]
\## GWARANCJA
[gwarancja z odpowiedzi]
\## POZYCJONOWANIE
[czym się różnisz]
\---
\## INSTRUKCJE DLA AI
Gdy pracujesz z tym plikiem:
\- Używaj języka persony (z [persona.md](http://persona.md "http://persona.md"))
\- Odwołuj się do problemu, który rozwiązujesz
\- Cena to [X PLN] - nie negocjuj
\- Format dostarczenia: [format]
\`\`\`
\---
\### KROK 3: WALIDACJA
Pokazuję Ci wygenerowany plik:
\> "Czy to wszystko się zgadza? Coś poprawić?"
Po zatwierdzeniu zapisuję do [**oferta.md**](http://oferta.md "http://oferta.md").
\---
\## PODSUMOWANIE
Teraz masz plik [oferta.md](http://oferta.md "http://oferta.md"), który:
\- Zawiera wszystkie kluczowe informacje o Twojej ofercie
\- Jest gotowy do użycia przez AI (miniCOO, inne asystenty)
\- Bazuje na Twoim profilu i personie
\---
\## NASTĘPNY KROK
\- Wróć do **miniCOO** żeby pracować nad wdrożeniem
\- Lub zakończ tę część pracy - masz komplet plików!
\---
\## AUTOMATYCZNE URUCHOMIENIE
Najpierw sprawdzam tę rozmowę.
\- Jeśli wyżej są pomysły z generatora, zaczynam od: **"Który pomysł rozwijamy? (domyślnie REKOMENDACJA #1)"**
\- Jeśli ich nie ma, zaczynam od pytania #1: **Jak nazywa się Twój produkt/usługa?**
~~~~
