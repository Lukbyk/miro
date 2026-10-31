# Badanie cenowe

Źródło: `biblioteka_promptow/07_badanie_cenowe.md` (W3 · P1). Treść skopiowana bez zmian.
Dostosowanie do pracy na komputerze: zasady w `miro.md`.

## Treść promptu

~~~~text
@Głębokie badanie  coo ## CEL Wykonaj Deep Research cenowy dla mojej oferty. Nie tworzysz zapytania do Deep Research. Jesteś już uruchomiony w trybie Deep Research i masz samodzielnie przeprowadzić badanie. Masz: 1\\. Przeczytać pliki z projektu. 2\\. Zrozumieć, co sprzedaję i komu. 3\\. Zbadać rynek, konkurencję i benchmarki. 4\\. Pokazać konkretne ceny, źródła i poziom pewności. 5\\. Dać rekomendację cenową do dalszej analizy oferty i planu. Jeśli nie masz aktywnego Deep Research albo dostępu do internetu, zatrzymaj się i napisz: \`Nie mam aktywnego Deep Research albo dostępu do internetu. Uruchom tę instrukcję w trybie Deep Research.\` \\--- \\## WYMAGANE PLIKI W PROJEKCIE Przeczytaj: 1\\. \`profil.md\`, kompetencje, doświadczenie, pozycja, zasoby. 2\\. \`persona.md\`, klient docelowy, budżet, bóle, gotowość do płacenia. 3\\. \`oferta.md\`, produkt albo usługa, format, stack, obecna cena, gwarancja. Jeśli któregoś pliku brakuje, zatrzymaj się i powiedz, którego pliku potrzebujesz. Nie zastępuj brakujących danych zgadywaniem. \\--- \\## KROK 1: KONTEKST Z PLIKÓW Na podstawie plików pokaż krótkie podsumowanie: \\\`\\\`\\\`markdown \\## KONTEKST OFERTY Produkt albo usługa: [...] Format: [...] Rynek: [...] Klient docelowy: [...] Problem klienta: [...] Obecna cena z [oferta.md]\([http://oferta.md](http://oferta.md) "[http://oferta.md](http://oferta.md)"): [...]
Poziom przedsiębiorcy: [...]
Atuty podnoszące cenę: [...]
Czynniki obniżające cenę: [...]
\\\`\\\`\\\`
Nie używaj danych, których nie ma w plikach. Jeśli czegoś brakuje, wpisz \`brak danych\`.
\\---
\\## KROK 2: PLAN BADANIA
Zanim zaczniesz szukać, ustal:
1\\. Jakie typy konkurentów są porównywalne.
2\\. Jakie frazy wyszukasz.
3\\. Jak odróżnisz ofertę podobną od nieporównywalnej.
4\\. Jakie ceny będą użyteczne, a jakie odrzucasz.
Pokaż to krótko:
\\\`\\\`\\\`markdown
\\## PLAN BADANIA
Porównuję z:
1\\. [...]
2\\. [...]
3\\. [...]
Szukam fraz:
1\\. [...]
2\\. [...]
3\\. [...]
Odrzucam:
1\\. [...]
2\\. [...]
\\\`\\\`\\\`
\\---
\\## KROK 3: BADANIE RYNKU KLIENTA
Ustal z persony i oferty rynek, język klienta oraz walutę. Jeśli brakuje rynku, zadaj jedno pytanie przed badaniem. Wyszukaj realne oferty na tym rynku, nie zakładaj Polski. Jeśli firma działa na kilku rynkach, porównuj je osobno z właściwymi walutami; jeśli nie wiadomo, od którego zacząć, zapytaj o rynek priorytetowy.
Minimum, jeśli rynek na to pozwala:
1\\. Do 5 porównywalnych ofert. Jeśli znalazłeś mniej, nazwij brak; nie uzupełniaj listy fikcyjnymi ofertami.
2\\. Cena albo informacja, że cena nie jest publiczna.
3\\. Link do źródła.
4\\. Co zawiera oferta.
5\\. Dlaczego jest porównywalna albo częściowo porównywalna.
Format:
\\\`\\\`\\\`markdown
\\## KONKURENCJA NA RYNKU KLIENTA
\\| Oferta | Cena | Co zawiera | Źródło | Porównywalność |
\\|---|---:|---|---|---|
\\| [...] | [...] [waluta] | [...] | [link] | wysoka / średnia / niska |
\\\`\\\`\\\`
Zasady:
1\\. Cena bez źródła nie jest faktem.
2\\. Jeśli cena jest ukryta, wpisz \`cena niepubliczna\`.
3\\. Jeśli cena jest szacunkiem, oznacz ją jako \`szacunek\` i wyjaśnij dlaczego.
4\\. Nie wymyślaj konkurentów, opinii, wyników ani kwot.
\\---
\\## KROK 4: BENCHMARKI MIĘDZYNARODOWE
Zbadaj benchmarki zagraniczne tylko wtedy, gdy pomagają w decyzji cenowej.
Wybierz tylko dodatkowy rynek przydatny do decyzji. Oferty muszą być podobne formatem albo problemem klienta. Dodatkowe kraje nie są obowiązkowe.
Format:
\\\`\\\`\\\`markdown
\\## BENCHMARKI MIĘDZYNARODOWE
\\| Rynek | Oferta | Cena lokalna | Przeliczenie / odniesienie do rynku klienta | Źródło | Wniosek |
\\|---|---|---:|---:|---|---|
\\| [wybrany rynek] | [...] | [...] | [...] | [link] | [...] |
\\\`\\\`\\\`
Nie rób prostego przeliczenia waluty jako rekomendacji ceny.
Traktuj benchmark zagraniczny jako sygnał pozycjonowania, nie gotową cenę dla rynku klienta.
\\---
\\## KROK 5: ANALIZA PROFILU I PERSONY
Po badaniu oceń dopasowanie ceny do mnie i do klienta.
Format:
\\\`\\\`\\\`markdown
\\## PROFIL CENOWY
Poziom przedsiębiorcy: [...]
Argumenty za wyższą ceną:
1\\. [...]
2\\. [...]
3\\. [...]
Argumenty za ostrożną ceną:
1\\. [...]
2\\. [...]
3\\. [...]
\\## GOTOWOŚĆ PERSONY DO PŁACENIA
Kto płaci: [...]
Szacowany budżet: [...]
Pilność problemu: [...]
Obiekcje cenowe: [...]
Wniosek: [...]
\\\`\\\`\\\`
\\---
\\## KROK 6: PRZEDZIAŁY CENOWE
Na podstawie źródeł i plików zaproponuj trzy przedziały:
\\\`\\\`\\\`markdown
\\## PRZEDZIAŁY CENOWE
Cena wejściowa: [...] [waluta]
Kiedy ma sens: [...]
Cena optymalna: [...] [waluta]
Kiedy ma sens: [...]
Cena premium: [...] [waluta]
Kiedy ma sens: [...]
\\\`\\\`\\\`
Każdy przedział musi wynikać z:
1\\. Cen konkurencji.
2\\. Profilu przedsiębiorcy.
3\\. Gotowości persony do płacenia.
4\\. Zakresu wartości w \`oferta.md\`.
\\---
\\## KROK 7: BONUSY I STACK WARTOŚCI
Zbadaj, co konkurencja dodaje do podobnych ofert.
Format:
\\\`\\\`\\\`markdown
\\## BONUSY I STACK WARTOŚCI
\\| Element | Wartość dla klienta | Koszt dla mnie | Źródło albo inspiracja | Rekomendacja |
\\|---|---|---|---|---|
\\| [...] | wysoka / średnia / niska | wysoki / średni / niski | [link albo z [oferta.md]\([http://oferta.md](http://oferta.md) "[http://oferta.md](http://oferta.md)")] | dodać / nie dodawać |
\\\`\\\`\\\`
Nie dopisuj bonusów tylko po to, żeby sztucznie podbić wartość.
Rekomenduj tylko te, które wzmacniają obietnicę oferty.
\\---
\\## KROK 8: RAPORT KOŃCOWY
Na końcu przygotuj raport do dalszej pracy nad ofertą i planem.
Format:
\\\`\\\`\\\`markdown
\\# RAPORT DEEP RESEARCH WYCENY
\\## 1. Najkrótszy wniosek
[1 do 3 zdań]
\\## 2. Rekomendowana cena
Cena rekomendowana: [...] [waluta]
Przedział bezpieczny: [...] [waluta]
Przedział premium: [...] [waluta]
\\## 3. Dlaczego ta cena
1\\. [...]
2\\. [...]
3\\. [...]
\\## 4. Ryzyka
1\\. [...]
2\\. [...]
3\\. [...]
\\## 5. Źródła cen
1\\. [nazwa] , [cena] , [link]
2\\. [nazwa] , [cena] , [link]
3\\. [nazwa] , [cena] , [link]
\\## 6. Co zrobić dalej
Zachowaj cały ten raport. Będzie potrzebny do analizy ceny, aktualizacji oferty i aktualizacji planu.
\\\`\\\`\\\`
\\---
\\## AUTOMATYCZNE URUCHOMIENIE
Zaczynam od KROKU 1: czytam \`profil.md\`, \`persona.md\` i \`oferta.md\`, a potem przeprowadzam badanie cenowe w internecie.
~~~~
