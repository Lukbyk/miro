# Upgrade asystenta do COO

Źródło: `biblioteka_promptow/17_upgrade_coo.md` (W5 · P1). Treść skopiowana bez zmian.
Dostosowanie do pracy na komputerze: zasady w `miro.md`.

## Treść promptu

~~~~text
@coo
Chcę zrobić upgrade mojego asystenta operacyjnego do pełnej wersji COO.
Mam plik `coo.md` w tym folderze. To nowa, pełna wersja mojego asystenta operacyjnego, ma zastąpić obecny miniCOO.
Zanim cokolwiek zmienisz, zrób to w tej kolejności:
1\. Przeczytaj CAŁY mój obecny plik instrukcji: `CLAUDE.md` albo `AGENTS.md`. To moja dotychczasowa instrukcja, budowana przeze mnie etapami. Powiedz mi w kilku punktach, co już w niej jest (np. moje pliki kontekstowe, moje wcześniejsze zasady, miniCOO).
2\. Przeczytaj plik `coo.md`.
3\. Porównaj obecną instrukcję z `coo.md` i powiedz mi: co jest nowe (charakter, menu, sposób pracy COO), a co z mojej obecnej instrukcji zostaje bez zmian.
4\. Przeczytaj mój plik `decyzje.md` (założyłem go na poprzednim warsztacie) i powiedz mi, jaki ma schemat pól.
5\. Jeśli `coo.md` opisuje inny schemat decyzji niż mój, zapytaj mnie: zachowujemy mój obecny schemat, czy migrujemy do schematu z `coo.md`? Nie zgaduj, zapytaj.
6\. Jeśli z jakiegoś powodu nie mam `decyzje.md`, zaproponuj prostą strukturę (data, decyzja, dlaczego, co to zmienia, kto/co robi następny krok) i pokaż mi ją do akceptacji, zanim utworzysz plik.
Zasada zapisu instrukcji:
1\. Znajdź w mojej obecnej instrukcji sekcję albo sekcje, które opisują działanie miniCOO (jego charakter, jego zasady, jego wywołanie). Te sekcje mają zostać CAŁKOWICIE ZASTĄPIONE treścią z `coo.md`. Po zapisie ma działać tylko jedna wersja COO, nie obie naraz, stary miniCOO ma zniknąć z instrukcji.
2\. Wszystkie INNE sekcje mojej obecnej instrukcji, niezwiązane z miniCOO (na przykład moje pliki kontekstowe, inne moje zasady), mają zostać bez zmian.
3\. Jeśli nie jesteś pewien, który fragment instrukcji to stary miniCOO, pokaż mi go i zapytaj, czy go usunąć, zanim zapiszesz.
Zanim zapiszesz jakąkolwiek zmianę:
1\. Zrób kopię zapasową obecnego pliku instrukcji i obecnego `decyzje.md` do folderu `backup`, według zasady kopii z mojej instrukcji.
2\. Pokaż mi dokładnie, co dopisujesz albo zmieniasz w instrukcji projektu.
3\. Zapytaj: "Czy zapisać zmianę?"
4\. Zapisz dopiero po mojej zgodzie.
Po zapisie:
1\. Pokaż ścieżkę backupu.
2\. Pokaż ścieżkę zmienionego pliku instrukcji i `decyzje.md`.
3\. Powiedz mi, że muszę zrestartować aplikację, żeby zmiana zaczęła działać.
Po restarcie wpiszę `@coo`, żeby sprawdzić, czy widzisz nowe menu.
~~~~
