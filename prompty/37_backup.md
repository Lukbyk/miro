# Backup każdej zmiany

Źródło: `biblioteka_promptow/16_backup_i_przywracanie.md` (W4 · P8). Treść: wersja wklejona przez użytkownika 2026-10-12, zgodna z biblioteką.
Dostosowanie do pracy na komputerze: zasady w `miro.md`. W tej ścieżce krok działa w trybie sprawdzenia (sekcja 11 w `miro.md`).

## Treść promptu

~~~~text
@coo

Chcę, żeby każda zmiana w plikach mojej firmy była odwracalna. Zrób trzy rzeczy, każdą po mojej zgodzie.

1. Dopisz do mojej instrukcji projektu (`CLAUDE.md` albo AGENTS.md) zasadę kopii zapasowej, najwyżej sześć linii, po ludzku:

   Zanim zmienisz, nadpiszesz albo usuniesz jakikolwiek plik w tym folderze, zapisz jego kopię w backup. Kopia leży w tej samej podścieżce co oryginał, na przykład backup/dane/persona.md dla dane/persona.md. Nazwa kopii: nazwa_RRRR-MM-DD_GGMM_krotki-opis-zmiany.md, na przykład oferta_2026-09-16_1430_nowa-cena-pakietu-start.md. Najpierw kopia, potem zmiana, nigdy odwrotnie. Po zapisie pokazujesz ścieżkę kopii i ścieżkę zmienionego pliku. Kopii nie usuwasz i nie nadpisujesz.

   Zasada wchodzi jako pierwsza przed „pokazujesz mi zmianę i pytasz o zgodę”; jeśli w instrukcji jest już wzmianka o kopii, zastąp ją tą, nie dubluj.

2. Sprawdź, czy moi asystenci (`minicoo.md` i inne pliki ról, jeśli są) mają własne zasady o zapisie plików. Jeśli tak, dopisz w nich jedno zdanie odsyłające do zasady kopii w instrukcji projektu. Nie przepisuj asystentów.

3. Dopisz do instrukcji komendę przywróć [plik] [data]: pokazujesz mi listę kopii tego pliku z backup, ja wybieram, Ty pokazujesz różnicę między obecną wersją a wybraną kopią, pytasz o zgodę, przywracasz. Przed przywróceniem obecna wersja też idzie do backup.

Przed każdym zapisem pokaż mi pełną treść i zapytaj o zgodę. Po zapisie ścieżki plików i informacja, że mam zrestartować aplikację.
~~~~
