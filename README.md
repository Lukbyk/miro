# MIRO

Przewodnik po budowie i aktualizacji projektów. Ścieżka kursu AI Biznes Lab (W1–W10) jako 59 kroków, każdy krok to jeden prompt.

## Jak używać

Działa w każdym folderze, w Claude Code i w Codexie (wpis w globalnych instrukcjach).

- `@miro nowy [nazwa]`: nowy projekt, od kroku 1.
- `@miro [projekt]` albo `@miro` w folderze projektu: aktualizacja istniejącego projektu; inwentaryzacja, luki, następny krok.
- Potem: `dalej`, `gdzie jestem`, `pomiń`, `krok N`, `przywróć [plik] [data]`.

Postęp każdego projektu jest w jego folderze, w `miro_postep.md`.

## Co jest w środku

- `miro.md`: instrukcja przewodnika.
- `AGENTS.md` i `CLAUDE.md`: zasady pracy nad samym przewodnikiem.
- `prompty/`: 59 kroków ścieżki.
- `pliki/`: pliki źródłowe kursu instalowane przez prompty: CSO (krok 27), system marketingowy (krok 38), operator @cmo (krok 49), @ghost ze szablonem stylu (krok 53), @ceo, rozbudowa @coo i szablon zespołu (kroki 56–58).
- `checklisty/`: checklisty do tekstu strony (B2B, B2C, copywriting).
- `przewodniki/`: przewodniki warsztatów (W7).
- `szablony/`: pliki zakładane w nowym projekcie (`miro_postep.md`, `decyzje.md`, `AGENTS_projektu.md`, `CLAUDE_projektu.md`).
- `coo.md`: wzór roli COO, instalowany w kroku 12.
- `backup/`: kopie plików przed zmianą.

## Czego nie ma

Pominięte świadomie: rozbudowa profilu (praca domowa W1), import istniejącej oferty (W2, prompt 3B), sprawdzenie folderu i przebudowa instrukcji (W4, prompty 1–2).
Cztery kroki (3, 8, 15, 29) i krok 40 wymagają Deep Research w przeglądarce. Dwa kroki (21, 22) wymagają generowania obrazów w ChatGPT. Kroki 33–34 wymagają skilla /master.
