# Kodowanie według projektu

Źródło: `biblioteka_promptow/26_w6_kodowanie_strony.md` (W6 · P5). Treść: wersja wklejona przez użytkownika 2026-10-12, zgodna z biblioteką.
Dostosowanie do pracy na komputerze: zasady w `miro.md`.

## Treść promptu

~~~~text
@coo

Zbuduj moją stronę wiernie według projektu graficznego. Nie projektuj od nowa w kodzie.

Pracuj w folderze strony ustalonym w zadaniu 2. Najpierw przeczytaj strona.md, styl-strony.md i obejrzyj pliki w projekt/: wybrany wariant całej strony, projekty sekcji, ilustracje. Jeśli nie możesz oglądać obrazów, poproś mnie o załączenie ich w obsługiwanej formie i nie deklaruj odwzorowania projektu bez jego obejrzenia.

Zasady:
1. Układ, kolejność sekcji, proporcje, kolory, typografia i nastrój pochodzą z projektu. Tekst pochodzi z strona.md. Skopiuj wyłącznie użyte ilustracje z projekt/ do assets/ i wstaw je jako obrazy ze względnymi ścieżkami assets/nazwa-pliku. Nie używaj makiety całej sekcji jako obrazka zamiast prawdziwego tekstu i przycisków.
2. Nie dodajesz sekcji, napisów ani elementów, których nie ma w projekcie. Nie wymyślasz opinii, liczb, klientów, wyników ani gwarancji.
3. Optymalizuj kopie w assets/, nie oryginały w projekt/ (cel: ilustracja do 300 KB, szerokość do 1600 px, bez widocznego pogorszenia). Powiedz, co zrobiłeś; brak narzędzia zgłoś zamiast udawać wykonanie.
4. Bez mojej osobnej zgody nie dodawaj analityki, pikseli, osadzonych filmów, zewnętrznych fontów, formularzy wysyłających dane ani płatności. Brak docelowego adresu CTA oznacz do ustalenia; nie twórz pozornie działającego przycisku. Przed publikacją musi być rozstrzygnięty.

Wymagania dla index.html:

1. Strona ma używać treści z strona.md, nie placeholderów.
2. Jeśli w materiałach nie ma opinii, logotypów, wyników, ROI, terminów albo limitów, nie wymyślaj ich.
3. Strona ma odwzorowywać projekt z projekt/ i kierunek ze styl-strony.md.
4. Wariant strony: standard.
5. Sekcje:
1. Hero z nagłówkiem, podtytułem i przyciskiem.
2. Problem klienta.
3. Rozwiązanie.
4. Co klient dostaje.
5. Cena i warunki.
6. FAQ.
7. Finalne CTA.
8. Stopka z miejscem na politykę prywatności i kontakt.
6. CSS i prosty JavaScript są wewnątrz index.html; obrazy są osobnymi plikami w assets/. Do publikacji potrzeba obu, nie samego HTML.
7. Strona ma działać po zwykłym otwarciu pliku w przeglądarce.
8. Design ma być prosty, czytelny i profesjonalny, ale nie generyczny. Ma być widoczny wybór stylu z styl-strony.md.
9. Hero ma mieć dopracowaną hierarchię: mocny nagłówek, czytelny podtytuł, wyraźny CTA i jeden gest wizualny zgodny z briefem.
10. Jeśli brief przewiduje ikony, użyj spójnych ikon SVG inline albo prostych symboli graficznych w jednym stylu. Nie mieszaj stylów ikon.
11. Jeśli brief przewiduje karty, każda karta ma mieć stabilny układ, spójne odstępy i czytelną hierarchię.
12. Jeśli brief przewiduje tło, zastosuj je subtelnie. Tło nie może utrudniać czytania.
13. Jeśli brief przewiduje animacje, dodaj tylko lekkie animacje wejścia albo hover. Nie rób efektów, które przeszkadzają w czytaniu.
14. Strona ma dobrze wyglądać na telefonie.
15. Nie używaj emoji.
16. Używaj wyłącznie zatwierdzonych ilustracji, skopiowanych z projekt/ do assets/. Żadnych ścieżek file:// ani odwołań do dysku komputera.
17. Unikaj wyglądu "AI template": przypadkowych gradientów, zbyt wielu świecących efektów, losowych ikon, zbyt dużych nagłówków i sekcji bez rytmu.

Przed zapisem index.html:
1. Pokaż mi listę sekcji i przy każdej: z którego pliku projektu ją odwzorowujesz i jaki tekst wstawiasz.
2. Zapytaj: "Czy zapisać pierwszą wersję strony?"
3. Zapisz dopiero po mojej zgodzie, do projekty/[nazwa-projektu]/strona/index.html.

Po zapisie, porównanie z projektem:
1. Otwórz stronę w podglądzie i zrób zrzut całej strony na szerokości komputera i telefonu, jeśli potrafisz (jeśli nie, powiedz mi, jak zrobić zrzut i poproś o wklejenie).
2. Porównaj zrzut z wybranym wariantem i projektami sekcji: wypisz różnice sekcja po sekcji (układ, proporcje, kolory, brakujące elementy).
3. Zaproponuj poprawki, zapytaj o zgodę, popraw i porównaj ponownie. Zatrzymaj się, gdy zrzut wygląda jak projekt albo gdy powiem, że wystarczy.

Po zapisie:

1. Powiedz mi, gdzie zapisałeś styl-strony.md i index.html.
2. Utwórz albo zaktualizuj plik projekty/[nazwa-projektu]/strona/README.md, żeby mój COO w przyszłości wiedział, jak pracować z tą stroną.
3. W README.md zapisz:
1. co to jest za strona,
2. gdzie jest główny plik strony,
3. gdzie jest tekst strony,
4. gdzie jest brief stylu,
5. jak otworzyć stronę lokalnie,
6. jak uruchomić lokalny podgląd, jeśli potrafisz podać prostą komendę,
7. gdzie zapisywać kolejne wersje albo backupy,
8. że publiczne pliki to index.html i użyte pliki assets/, a projekt/, pliki .md i kopie zapasowe pozostają lokalne.
4. Pokaż mi treść README.md i zapytaj: "Czy zapisać instrukcję uruchomienia strony dla COO?"
5. Zapisz README.md dopiero po mojej zgodzie.
6. Powiedz mi, jak otworzyć plik w przeglądarce.
7. Jeśli potrafisz, uruchom lokalny podgląd i podaj mi adres.
8. Zapytaj mnie, co widzę na ekranie i czy tekst oferty jest poprawny.
9. Po akceptacji skieruj mnie do zadania 6. Jeśli są nierozstrzygnięte dane, CTA albo działające integracje zbierające dane, nie kieruj do publikacji: wskaż brak i w razie potrzeby zadanie 7 do wykonania przed upublicznieniem.
~~~~
