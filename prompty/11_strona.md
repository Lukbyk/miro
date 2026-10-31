# Tekst strony sprzedażowej

Źródło: `biblioteka_promptow/10_tekst_strony.md` (W3 · P4). Treść skopiowana bez zmian.
Dostosowanie do pracy na komputerze: zasady w `miro.md`.

## Treść promptu

~~~~text
@coo   @coo    ## CEL
Stwórz gotowy tekst strony sprzedażowej.
Na końcu masz wygenerować gotową treść `strona.md`, którą można skopiować, pobrać albo wkleić do narzędzia do budowy strony.
Masz użyć:
1\. `oferta.md`, czyli co sprzedaję, za ile i z jaką obietnicą.
2\. `persona.md`, czyli do kogo mówię i co tę osobę boli.
3\. `profil.md`, czyli dlaczego mam prawo sprzedawać tę ofertę.
4\. Opcjonalnie: `checklistab2b.md`, `checklistab2c.md`, `checklista-copy-na-strone.md`, jeśli są dostępne.
Nie zapisuj nic automatycznie.
\---
\## ZASADY
1\. Nie wymyślaj case studies, opinii, logo klientów, wyników, ROI, miejsc, terminów ani limitów.
2\. Jeśli czegoś brakuje, wpisz `Do uzupełnienia` albo zapytaj o brakującą informację.
3\. Jeśli w plikach nie ma dowodów społecznych, nie udawaj, że są.
4\. Jeśli w plikach nie ma danych do ROI, nie licz ROI.
5\. Jeśli cena albo stack są w `oferta.md`, użyj ich dokładnie.
6\. Jeśli `oferta.md` ma aktualizację po wycenie, użyj aktualnej wersji ceny i uzasadnienia.
7\. Pisz językiem klienta z `persona.md`, ale nie cytuj zdań, których tam nie ma.
8\. Strona ma pomagać sprzedaży, nie wyglądać jak ćwiczenie z copywritingu.
\---
\## KROK 1: SPRAWDŹ MATERIAŁY
Najpierw przeczytaj:
1\. `oferta.md`
2\. `persona.md`
3\. `profil.md`
Jeśli widzisz checklisty, użyj ich jako kryteriów jakości.
Jeśli ich nie widzisz, użyj prostych zasad z tej instrukcji.
Pokaż krótkie podsumowanie:
\`\`\`markdown
\## MATERIAŁY
Oferta: [widzę / nie widzę]
Persona: [widzę / nie widzę]
Profil: [widzę / nie widzę]
Checklisty: [widzę / nie widzę]
\`\`\`
Jeśli brakuje `oferta.md`, `persona.md` albo `profil.md`, zatrzymaj się i poproś o brakujący materiał.
\---
\## KROK 2: WYBIERZ TYP STRONY
Jeśli z `persona.md` albo `oferta.md` jasno wynika, czy to B2B czy B2C, wybierz samodzielnie i wyjaśnij jednym zdaniem.
Jeśli nie wynika, zapytaj:
\`\`\`text
Do kogo sprzedajesz tę ofertę?
1\. B2B, czyli do firm.
2\. B2C, czyli do osób prywatnych.
\`\`\`
\---
\## KROK 3: WYCIĄGNIJ KONTEKST
Przed pisaniem zbierz tylko najważniejsze dane:
\`\`\`markdown
\## KONTEKST STRONY
Nazwa oferty: [...]
Dla kogo: [...]
Najważniejszy problem klienta: [...]
Najważniejsza obietnica: [...]
Cena: [...]
Co klient dostaje: [...]
Dowody społeczne: [są / brak danych]
Gwarancja: [...]
Najważniejszy argument z profilu: [...]
\`\`\`
Nie dopisuj własnych liczb ani obietnic.
\---
\## KROK 4: WYGENERUJ STRONĘ
Wygeneruj gotową treść `strona.md`.
Dla B2B użyj tej struktury:
\`\`\`markdown
\# STRONA SPRZEDAŻOWA: [nazwa oferty]
\## 1. HERO
[Nagłówek z konkretną obietnicą]
[Podtytuł: dla kogo, jaki problem, jaki rezultat]
[CTA]
\## 2. PROBLEM
[3 do 5 punktów językiem klienta]
\## 3. DLACZEGO TO TERAZ WAŻNE
[Konsekwencje braku działania, bez wymyślonych liczb]
\## 4. ROZWIĄZANIE
[Opis oferty prostym językiem]
\## 5. CO DOSTAJESZ
[Stack z [oferta.md](http://oferta.md "http://oferta.md")]
\## 6. DLACZEGO JA
[Krótki argument z [profil.md](http://profil.md "http://profil.md")]
\## 7. DOWODY ALBO BRAKI
[Opinie, case studies, loga tylko jeśli są w plikach. Jeśli nie ma: Do uzupełnienia.]
\## 8. CENA I WARUNKI
[Cena, płatność, gwarancja, warunki z [oferta.md](http://oferta.md "http://oferta.md")]
\## 9. FAQ
[5 pytań i odpowiedzi na bazie oferty i persony]
\## 10. FINALNE CTA
[Jedno konkretne wezwanie do działania]
\`\`\`
Dla B2C użyj tej samej logiki, ale:
1\. Pisz bardziej bezpośrednio.
2\. Mocniej pokaż zmianę w życiu klienta.
3\. Nie używaj żargonu biznesowego.
4\. Nie udawaj dowodów społecznych, jeśli ich nie ma.
\---
\## KROK 5: KONTROLA JAKOŚCI
Po stronie dodaj krótką kontrolę:
\`\`\`markdown
\## KONTROLA JAKOŚCI
1\. Czy nagłówek mówi konkretnie, co klient zyska? [tak / do poprawy]
2\. Czy problem jest opisany językiem persony? [tak / do poprawy]
3\. Czy oferta jest jasna? [tak / do poprawy]
4\. Czy cena ma uzasadnienie? [tak / do poprawy]
5\. Czy nie ma wymyślonych dowodów, liczb ani opinii? [tak / do poprawy]
\## DO UZUPEŁNIENIA PRZEZ CZŁOWIEKA
1\. [...]
2\. [...]
3\. [...]
\`\`\`
\---
\## AUTOMATYCZNE URUCHOMIENIE
Zaczynam od KROKU 1: sprawdzam `oferta.md`, `persona.md` i `profil.md`, a potem generuję gotową treść `strona.md`.
\## SPRAWDZENIE CENY I OBIETNICY
Używaj tylko ceny i warunków zatwierdzonych w `oferta.md`; jeśli w ofercie są dwie różne ceny, pokaż obie i zapytaj, która obowiązuje. Miejsca oznaczone `Do uzupełnienia` to braki do wypełnienia przez człowieka przed publikacją.
~~~~
