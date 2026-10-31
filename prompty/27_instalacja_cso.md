# Instalacja CSO

Źródło: `biblioteka_promptow/29_w7_instalacja_cso.md` (W7 · P1). Treść: wersja wklejona przez użytkownika 2026-10-12, zgodna z biblioteką.
Dostosowanie do pracy na komputerze: zasady w `miro.md`.

## Treść promptu

~~~~text
Cel: uczestnik ma w projekcie działającego CSO, wpisanego do własnej instrukcji projektu, z podpiętymi plikami sprzedażowymi i bez utraty tego, co już wcześniej zbudował.

Ważne zanim zaczniesz: Twoja instrukcja projektu, CLAUDE.md i AGENTS.md, jest już Twoja. Może mieć własne zasady, pliki kontekstowe, role i wcześniejsze decyzje. Ten metaprompt nie wgrywa jednej gotowej instrukcji dla wszystkich. Agent ma przeczytać obecną instrukcję w całości i dopisać do niej CSO, a nie nadpisać ani wyczyścić Twojej pracy.

Wklej do Claude Code albo Codex:

Pracujemy w folderze mojego projektu.

Chcę zainstalować Asystenta Sprzedaży CSO i materiały sprzedażowe w moim projekcie.

Zrób to spokojnie, bez kasowania czegokolwiek i bez nadpisywania mojej obecnej instrukcji projektu.

Najpierw sprawdź:

1. Jakie instrukcje projektu istnieją: CLAUDE.md, AGENTS.md, i czy jedna jest kopią drugiej.

2. Gdzie leży coo.md i gdzie leżą moje pliki firmy: profil.md, persona.md, oferta.md, strona.md, publikacja.md.

3. Czy istnieją foldery dane i materialy.

4. Czy widzisz pliki źródłowe:

   1. pliki/cso.md

   2. pliki/checklista_lejki.md

   3. pliki/checklista_sprzedazy.md

Jeżeli nie ma CLAUDE.md ani AGENTS.md, zaproponuj utworzenie jednego pliku instrukcji projektu i zapytaj mnie o zgodę.

Jeżeli brakuje folderów dane albo materialy, zaproponuj ich utworzenie i zapytaj mnie o zgodę.

Jeżeli nie widzisz któregoś pliku źródłowego, zatrzymaj się i powiedz dokładnie, którego brakuje.

Potem przeczytaj:

1. Wszystkie istniejące instrukcje projektu, CLAUDE.md i AGENTS.md, w całości.

2. pliki/cso.md.

Powiedz mi krótko:

1. Co już jest w mojej instrukcji projektu.

2. Gdzie najlepiej dopisać CSO.

3. Co dokładnie dopiszesz.

4. Czego nie ruszysz.

Zasada zapisu instrukcji:

1. CSO ma być dostępny jako @cso.

2. Instrukcja projektu ma mówić, że @cso oznacza Asystenta Sprzedaży.

3. Instrukcja projektu ma wskazywać, że rola CSO żyje w cso.md, obok coo.md. Jeśli nie mam coo.md, w głównym folderze firmy.

4. Instrukcja projektu ma wskazywać materiały sprzedażowe:

   1. materialy/checklista_lejki.md

   2. materialy/checklista_sprzedazy.md

5. Instrukcja projektu ma mówić, że CSO pomaga w sprzedaży, lejku, obiekcjach, follow upach, pipeline i decyzjach sprzedażowych.

6. Instrukcja projektu ma mówić, że CSO nie zgaduje cen, wyników, terminów, promocji ani social proofu. Jeśli nie ma danych, używa trybu NIE MAM DANYCH.

7. W instrukcji projektu ma być tabela „Moi asystenci”: asystent, za co odpowiada, kiedy go wołać, po jednej linii na asystenta. Jeśli tabela istnieje, dopisz do niej CSO. Jeśli jej nie ma, utwórz ją z asystentami, których już mam, np. @coo, i dopisz CSO. Opisy współpracy między asystentami żyją tylko w tej tabeli, nie w plikach ról.

8. Rola CSO opisuje moje pliki firmy jako dane/profil.md, dane/persona.md, dane/oferta.md, dane/strona.md i dane/publikacja.md. Jeśli u mnie leżą gdzie indziej, np. w głównym folderze firmy, dopisz przy @cso jedną zasadę: CSO czyta te pliki z moich rzeczywistych ścieżek. Nie kopiuj ich do dane i nie twórz drugiej wersji.

9. Wszystkie inne sekcje mojej instrukcji, niezwiązane z CSO ani tabelą „Moi asystenci”, mają zostać bez zmian.

10. Zmiany wprowadź w każdej istniejącej instrukcji projektu zgodnie z moją zasadą synchronizacji. Nie wybieraj jednego pliku kosztem drugiego.

11. Jeśli w instrukcji istnieje już stary CSO albo inny asystent sprzedaży, pokaż mi ten fragment i zapytaj, czy go zastąpić.

12. Jeśli mam już własny plik z kontaktami albo klientami, np. kontakty.md, pokaż mi go i zapytaj, czy CSO ma go używać zamiast dane/pipeline.md. Nie twórz drugiej listy tych samych osób.

Następnie przygotuj instalację plików:

1. Skopiuj albo pomóż mi skopiować:

   1. pliki/cso.md do cso.md obok coo.md

   2. pliki/checklista_lejki.md do materialy/checklista_lejki.md

   3. pliki/checklista_sprzedazy.md do materialy/checklista_sprzedazy.md

2. Jeżeli któryś plik docelowy już istnieje, nie nadpisuj go automatycznie. Pokaż różnicę i zapytaj mnie o zgodę.

Zanim zapiszesz jakąkolwiek zmianę:

1. Pokaż dokładnie, co zmienisz w instrukcjach projektu.

2. Zapytaj: "Czy zapisać zmianę?"

3. Po mojej zgodzie zrób kopie wszystkich zmienianych i nadpisywanych plików do backup, zgodnie z moją zasadą kopii.

4. Dopiero potem zapisz.

Po instalacji pokaż tylko:

1. Ścieżki kopii w backup.

2. Ścieżki zmienionych instrukcji projektu.

3. Listę skopiowanych plików.

4. Czego brakuje, jeśli czegoś brakuje.

5. Informację, że muszę zamknąć i ponownie otworzyć aplikację w tym samym folderze firmy, żeby @cso zaczął działać.

6. Wiadomość testową, którą mam wkleić po ponownym otwarciu:

@cso pokaż menu

Po ponownym otwarciu @cso powinien pokazać menu sześciu opcji i działać na moich danych projektowych.
~~~~
