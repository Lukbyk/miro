# Trzy projekty całej strony

Źródło: `biblioteka_promptow/24_w6_brief_i_warianty_strony.md` (W6 · P3). Treść: wersja wklejona przez użytkownika 2026-10-12, zgodna z biblioteką.
Dostosowanie do pracy na komputerze: zasady w `miro.md`.

## Treść promptu

~~~~text
@coo

Chcę dobrać styl mojej strony i dostać gotowy prompt do wygenerowania projektu całej strony jako grafiki. Nie buduj jeszcze żadnego kodu.

Pracuj w folderze projekty/[nazwa-projektu]/strona/. Jeśli nie wiesz, jaka jest nazwa projektu, zapytaj mnie. Jeśli folder strony nie istnieje, zatrzymaj się i powiedz: "Najpierw zrób Krok 2". Brak strona.md nie jest blokerem, jeśli mam oferta.md.

Najpierw przeczytaj:

1. strona.md, jeśli istnieje.

2. oferta.md, jeśli istnieje.

3. Jeśli istnieją, profil.md i persona.md z głównego folderu.

4. Jeśli istnieje wcześniejszy plik styl-strony.md, przeczytaj go i powiedz, że możesz go zaktualizować, a nie zaczynać od zera.

Jeśli nie ma strona.md, ale jest oferta.md:

1. Powiedz: "Nie widzę strona.md, więc zrobię roboczy tekst strony z oferta.md."

2. Pokaż mi krótką mapę, co z oferta.md trafi na stronę:

1. hero,

2. problem,

3. rozwiązanie,

4. co klient dostaje,

5. cena i warunki,

6. FAQ,

7. CTA,

8. braki do uzupełnienia.

3. Zapytaj: "Czy mogę utworzyć roboczy strona.md z tych elementów?"

4. Jeśli powiem tak, przygotuj projekty/[nazwa-projektu]/strona/strona.md.

5. Nie wymyślaj opinii, liczb, klientów, wyników, ROI, terminów, limitów ani gwarancji.

6. Jeśli czegoś brakuje, wpisz Do uzupełnienia.

7. Pokaż treść strona.md i zapytaj o zgodę przed zapisem.

8. Zapisz dopiero po mojej zgodzie.

Jeśli nie ma ani strona.md, ani oferta.md, zatrzymaj się i powiedz: "Nie mam tekstu strony ani oferty. Wklej tekst strony z W03 albo uzupełnij oferta.md."

Powiedz mi w kilku punktach:

1. jaka jest nazwa oferty,

2. dla kogo jest oferta,

3. jaka jest główna obietnica,

4. jaka cena albo warunki są w materiale,

5. czego brakuje i trzeba oznaczyć jako Do uzupełnienia.

Potem dobierz ze mną styl strony. Nie rób długiej ankiety. Zadaj tylko kilka pytań, a resztę decyzji projektowych dobierz sam na podstawie mojego produktu, tekstu strony i poniższych zasad.

Zapytaj mnie po kolei:

1. Kto ma wejść na tę stronę: klient B2B, klient indywidualny, osoba z polecenia, zimny lead, uczestnik warsztatu czy ktoś inny?

2. Jak ta osoba ma się poczuć po wejściu na stronę: bezpiecznie, zainspirowana, zaciekawiona, zmotywowana, spokojna, gotowa do zakupu?

3. Jakie 3 słowa mają opisywać markę, na przykład: ekspercka, ciepła, odważna, luksusowa, konkretna, nowoczesna, naturalna?

4. Czy są kolory, logo, fonty albo przykład strony, których mam się trzymać? Jeśli nie ma, dobierz sam.

5. Czego zdecydowanie unikać w wyglądzie?

Na podstawie odpowiedzi dobierz szczegółowy kierunek. Masz sam przełożyć odpowiedzi na decyzje projektowe. Nie zostawiaj pól ogólnych typu "ładnie", "nowocześnie", "profesjonalnie". Każda decyzja ma mówić, co realnie trafi do HTML i CSS.

Użyj poniższych zasad jako wbudowanej wiedzy o tym, jak robić stronę, żeby efekt był mniej generyczny i mniej "AI".

ZASADY DESIGNU DO ZASTOSOWANIA PRZEZ AGENTA

Styl wizualny:

1. Wybierz jeden spójny kierunek wizualny, nie mieszaj kilku estetyk naraz.

2. Dla usług B2B domyślnie wybieraj spokojny, ekspercki, czytelny styl.

3. Dla edukacji, konsultingu i ofert osobistych wybieraj styl cieplejszy, ale nadal premium.

4. Dla technologii i narzędzi wybieraj styl nowoczesny, ale bez losowego "AI glow".

5. Strona ma wyglądać jak zaprojektowana pod tę ofertę, nie jak szablon z generatora.

Efekty:

1. Używaj efektów tylko tam, gdzie pomagają zrozumieć strukturę strony.

2. Dobre efekty: subtelny cień, cienka ramka, delikatny hover, miękkie wejście sekcji, lekki gradient w tle hero.

3. Unikaj: neonowych poświat bez powodu, przypadkowych blobów, przesadnego glassmorphism, chaosu kolorów, wszystkiego co krzyczy "AI template".

Typografia:

1. Dobierz maksymalnie dwie rodziny fontów.

2. Nagłówki mają mieć wyraźny charakter, ale być czytelne.

3. Tekst główny ma być spokojny i łatwy do czytania.

4. Ustal role typografii: hero, nagłówki sekcji, tekst, etykiety, przyciski.

5. Nie rób zbyt dużych nagłówków, jeśli tekst zaczyna wyglądać jak makieta zamiast strony.

Tło:

1. Tło ma wspierać treść, nie walczyć o uwagę.

2. Dobre tła: czyste jasne tło, subtelny gradient, lekka tekstura, delikatny wzór, spokojne ciemne tło tylko jeśli pasuje do marki.

3. Unikaj przypadkowych wielokolorowych gradientów i ozdobników bez związku z ofertą.

Ikony:

1. Jeśli używasz ikon, wybierz jeden styl ikon na całą stronę.

2. Ikony mają pomagać skanować treść, nie dekorować na siłę.

3. Najbezpieczniejsze style: cienkie liniowe, proste geometryczne, minimalistyczne techniczne albo eleganckie organiczne.

4. Nie mieszaj ikon 3D, emoji, ręcznych ilustracji i line icons na jednej stronie.

Układ:

1. Hero ma być najmocniejszą sekcją wizualną.

2. Sekcje mają mieć rytm: hero, problem, rozwiązanie, co dostajesz, cena, FAQ, CTA.

3. Karty mają mieć spójne odstępy, ramki, cienie i wysokości.

4. Mobile ma być projektowane od początku, nie jako przypadkowe zmniejszenie desktopu.

Animacje:

1. Animacje mają być subtelne.

2. Dobre animacje: lekkie fade in, hover na przycisku, delikatny lift karty, smooth scroll.

3. Unikaj animacji, które odciągają uwagę od czytania albo spowalniają stronę.

Po odpowiedziach pokaż mi brief:

BRIEF STYLU STRONY

Odbiorca:

Emocja po wejściu:

3 słowa marki:

Czego unikamy:

Kolory:

Typografia:

Układ:

Klimat referencyjny:

Tło:

Sekcje:

Karty:

Przyciski:

Ikony:

Animacje:

Mobile:

Efekt wow:

Decyzja designu:

ZASADY WYKONANIA

1. Strona ma wyglądać jak zaprojektowana dla tej konkretnej marki, nie jak generyczny wynik AI.

2. Hero ma mieć najmocniejszą hierarchię wizualną na stronie.

3. Ikony, jeśli ich używamy, mają mieć jeden spójny styl.

4. Kolory mają mieć role: tło, tekst, akcent, CTA, ramki, karty.

5. Typografia ma mieć role: nagłówek, tekst główny, małe etykiety, CTA.

6. Animacje mają wspierać czytanie, nie robić hałasu.

7. Mobile ma być projektowane od początku, nie jako przypadkowe zmniejszenie desktopu.

8. Nie używamy stockowych zdjęć ani losowych grafik, jeśli nie ma konkretnego sensu.

Zapytaj: "Czy ten brief stylu pasuje?" Jeśli powiem nie, popraw brief pytaniami pomocniczymi.

Jeśli powiem tak:
1. Zapisz brief jako projekty/[nazwa-projektu]/strona/styl-strony.md (pokaż treść, zapytaj o zgodę, zapisz po zgodzie).
2. Załóż folder projekty/[nazwa-projektu]/strona/projekt/ po mojej zgodzie.
3. Przygotuj gotowy do skopiowania prompt do modelu graficznego. Prompt ma zawierać: pełną treść mojej strony z strona.md (nagłówki i najważniejsze zdania każdej sekcji, bez wymyślania niczego), brief stylu w kilku zdaniach, kolejność sekcji (hero, problem, rozwiązanie, co klient dostaje, cena i warunki, FAQ, finalne CTA, stopka) oraz polecenie: „Zaprojektuj tę stronę jako jedną grafikę pokazującą całą stronę od góry do dołu, w wersji na komputer, jakby to był gotowy projekt do wdrożenia. Prawdziwe teksty z treści, bez lorem ipsum, bez nowych opinii, liczb i obietnic. Hero jako najmocniejsza sekcja z jedną ilustracją pasującą do oferty. Jeden spójny styl, bez efektów typu szablon AI.”
4. Pokaż prompt w osobnym bloku do skopiowania i powiedz mi: wygeneruj go trzy razy w ChatGPT (GPT Image 2.5, najwyższa jakość), każdy wynik zapisz jako projekt/strona-wariant-1.png, -2.png, -3.png, wybierz ten, który najlepiej pasuje do Twojej marki, i wróć do mnie z numerem.

CZĘŚĆ B, w ChatGPT w przeglądarce (bez API, zwykłe okno czatu z generowaniem obrazów): wygeneruj trzy warianty, każdy obraz zapisz na dysk, zapisz w folderze projekt/, wybierz jeden. Nie oceniaj po detalach, oceniaj po wrażeniu: czy klient wchodząc na tę stronę poczuje to, co wpisałeś w briefie. Zły wariant nie jest do poprawiania, jest do wyrzucenia.

CZĘŚĆ C, w aplikacji: Wybrałem wariant [numer]. Zapisz w styl-strony.md, że projekt bazowy to projekt/strona-wariant-[numer].png, i powiedz, co dalej. Poprawny wynik: asystent dopisuje decyzję do briefu i kieruje do Kroku 4.
~~~~
