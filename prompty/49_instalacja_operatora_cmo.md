# Instalacja operatora @cmo

Źródło: wiadomość użytkownika w sesji „W9 realizacja”, 2026-10-12 (W9 · P1); treść z eksportu sesji, bez zmian. Kolejność według transkrypcji W9. Brak tego promptu w `biblioteka_promptow/`.
Dostosowanie do pracy na komputerze: zasady w `miro.md`.

## Treść promptu

~~~~text
PROMPT 1: Instalacja CMO

Pracujemy w folderze mojego projektu.

Chcę zainstalować operatora @cmo NAD istniejącym systemem marketingowym w projekty/cmo. @cmo nie jest kolejnym promptem do generowania treści. Jest warstwą, która wybiera właściwy system, pilnuje trybu pracy, jakości, zapisu wyników i rozwoju roadmapy.

Nie kasuj niczego i nie nadpisuj istniejących plików bez zgody.

KROK 1. DIAGNOZA (nic nie zapisuj)

Sprawdź strukturę istniejącego systemu marketingowego:

1. Czy istnieje CLAUDE.md albo AGENTS.md.

2. Czy istnieje folder projekty/cmo.

3. Czy istnieje fundament marketingowy:

   1. projekty/cmo/fundament/sciezka-klienta.md

   2. projekty/cmo/fundament/strategia-marketingu.md

   3. projekty/cmo/fundament/plan-marketingowy.md

4. Czy istnieją systemy kanałowe:

   1. projekty/cmo/social/social.md i asystent @social

   2. projekty/cmo/newsletter/newsletter.md i asystent @newsletter

   3. projekty/cmo/ads/ads.md i asystent @ads

   4. Systemy z AI Marketing Lab mogą leżeć w projekty/cmo/systems/. Traktuj je tak samo.

5. Czy istnieją inne elementy: projekty/cmo/research/, projekty/cmo/content-machine/, projekty/cmo/social/plany-contentu/.

6. Czy w instrukcji projektu są już wpisane wywołania @social, @newsletter i @ads.

7. Czy widzisz plik źródłowy pliki/cmo.md.

8. Czy @cmo już istnieje, na przykład projekty/cmo/cmo.md z AI Marketing Lab (w nagłówku linia „Wersja roli”).

Wypisz krótko, co znalazłeś, a czego nie znalazłeś. Braki opisuj jako miejsce na rozwój systemu, nie jako mój błąd. Jeżeli nie widzisz tej struktury, zatrzymaj się i powiedz, że najpierw trzeba zainstalować system marketingowy w projekty/cmo, albo wskaż, gdzie leży system marketingowy.

Jeżeli brakuje pliku źródłowego pliki/cmo.md, zatrzymaj się i powiedz to wprost.

WAŻNE, jeśli istnieją @social, @newsletter albo @ads:

@cmo staje się operatorem NAD nimi. Niczego nie duplikuje i nie tworzy konkurencyjnych promptów. Istniejące systemy zostają nietknięte. @cmo dostaje w swojej roli listę systemów, którymi steruje, i deleguje do nich pracę kanałową. Fundament marketingowy z projekty/cmo/fundament/ staje się danymi wejściowymi warstwy strategicznej @cmo. Nie przenoś tych plików.

WAŻNE, jeśli @cmo już istnieje (na przykład z AI Marketing Lab):

Nie instalujesz drugiego @cmo. Nie nadpisujesz istniejącej roli i nie wklejasz do niej całego pliki/cmo.md. Porównaj komendy z pliki/cmo.md z istniejącym @cmo i wypisz tylko te, których brakuje (na przykład „rozbuduj roadmapę”, „checklista [format]”, „wynik: [co się stało]”). W planie zmian zaproponuj dopisanie procedur tylko tych komend, skopiowanych z pliki/cmo.md: do projekty/cmo/ustalenia.md, jeśli ten plik istnieje (aktualizacje AI Marketing Lab go nie ruszają), a jeśli nie istnieje, w osobnej sekcji na końcu istniejącej roli. Pozostałe kroki wykonujesz tylko w zakresie, którego brakuje.

KROK 2. PLAN ZMIAN (pokaż i czekaj na moją zgodę)

Pokaż listę plików, które utworzysz albo zmienisz. Zasady twarde:

1. Niczego nie kasujesz i nie nadpisujesz mojej pracy.

2. Jeśli plik istnieje, proponujesz dopisanie, nie podmianę.

3. Wszystko zostaje lokalnie w tym projekcie. Zero wysyłania danych.

Plan domyślny:

1. projekty/cmo/cmo.md, rola i zasady @cmo, tylko gdy @cmo jeszcze nie istnieje. Skopiuj treść z pliki/cmo.md. Nie pisz roli od zera, jeśli plik źródłowy istnieje.

2. projekty/cmo/ROADMAP.md. Jeżeli istnieje, dopisz sekcję operatora @cmo, nie podmieniaj całego pliku. Jeżeli nie istnieje, utwórz go z sekcją tematów do zrobienia.

3. projekty/cmo/CHANGELOG.md. Jeżeli istnieje, dopisz wpis instalacji @cmo z datą. Jeżeli nie istnieje, utwórz go.

4. Dopisek do instrukcji projektu: wywołanie @cmo ładuje projekty/cmo/cmo.md.

Nie twórz w tym zadaniu 18 folderów systemów. Nie twórz pustych folderów na zapas. Mapa 18 systemów żyje jako wewnętrzna wiedza @cmo w projekty/cmo/cmo.md, nie jako osobne foldery ani osobny plik.

KROK 3. INSTALACJA (po mojej zgodzie)

1. Skopiuj treść pliki/cmo.md do projekty/cmo/cmo.md jako nadrzędny prompt operatora @cmo. Nie usuwaj pliku źródłowego z pliki/.

2. Jeżeli projekty/cmo/ROADMAP.md istnieje, dopisz do niego sekcję o operatorze @cmo i listę systemów, którymi steruje. Jeżeli nie istnieje, utwórz go.

3. Jeżeli projekty/cmo/CHANGELOG.md istnieje, dopisz wpis z dzisiejszą datą: zainstalowano operatora @cmo nad istniejącym systemem marketingowym. Jeżeli nie istnieje, utwórz go z tym wpisem.

Ustal dzisiejszą datę z systemu, jeśli możesz. Jeżeli nie możesz, zapytaj mnie o zgodę na datę ręczną.

KROK 4. MAPOWANIE ISTNIEJĄCEJ PRACY DO SYSTEMÓW

Zmapuj istniejącą pracę marketingową do systemów. O systemach mów zawsze nazwą, numer folderu jest tylko techniczny:

1. Social i posty do systemu Social media.

2. Newsletter i maile do systemu Mail.

3. Reklamy do systemu Reklamy społecznościowe i wideo.

4. Content machine, biblioteka źródeł i plan treści do systemu Treści.

5. Fundament marketingu zostaje danymi wejściowymi operatora @cmo. Podlinkuj go w projekty/cmo/cmo.md w sekcji Rola.

Mapowanie to notatka o tym, gdzie leży istniejący materiał. Nie przenoś plików bez mojej osobnej zgody. Nie twórz nowych folderów systemów w tym kroku.

KROK 5. INTEGRACJA Z INSTRUKCJĄ PROJEKTU

Sprawdź, czy istnieje AGENTS.md, CLAUDE.md albo inny główny plik instrukcji projektu.

Jeżeli istnieje, przygotuj sekcję do dopisania do każdego istniejącego pliku instrukcji projektu. Jeżeli nie istnieje żaden, zaproponuj utworzenie AGENTS.md z tą sekcją.

Nie edytuj instrukcji projektu bez osobnej zgody. Zrób backup każdego pliku instrukcji, który będziesz edytować.

Sekcja do dopisania ma mieć treść w tym stylu:

START SEKCJI DO INSTRUKCJI PROJEKTU

Nagłówek: Operator systemu marketingowego @cmo

Mam zainstalowanego operatora @cmo w projekty/cmo/cmo.md.

Zasady:

1. @cmo jest operatorem NAD systemami kanałowymi @social, @newsletter, @ads.

2. @cmo niczego nie duplikuje. Deleguje pracę kanałową do istniejących systemów.

3. @cmo pracuje w trzech trybach: Strategia, Kreacja, Operacje. Na początku odpowiedzi nazywa tryb.

4. Fundament marketingowy z projekty/cmo/fundament/ jest danymi wejściowymi @cmo.

5. @cmo zapisuje wyniki do plików w folderach systemów, prowadzi projekty/cmo/ROADMAP.md i projekty/cmo/CHANGELOG.md.

6. @cmo niczego nie publikuje, nie wysyła i nie uruchamia reklam bez mojej zgody.

7. Wywołanie @cmo ładuje projekty/cmo/cmo.md.

Dopisz też @cmo do tabeli „Moi asystenci” w instrukcji projektu (asystent, za co odpowiada, kiedy go wołać). Jeśli tabeli nie ma, utwórz ją z asystentami, których już mam. Pozostałe sekcje instrukcji zostają bez zmian, a zmiany wprowadź w każdej istniejącej instrukcji projektu zgodnie z moją zasadą synchronizacji.

KONIEC SEKCJI DO INSTRUKCJI PROJEKTU

KROK 6. RAPORT INSTALACJI

Zanim zapiszesz, pokaż:

1. Listę plików do utworzenia albo zmiany.

2. Listę plików instrukcji projektu, które chcesz edytować albo utworzyć, i gdzie dokładnie dopiszesz sekcję.

3. Listę plików, których nie ruszysz.

4. Pytanie: Czy zapisać operatora @cmo i dopisać sekcję do instrukcji projektu?

Zapisz dopiero po mojej zgodzie.

Po zapisie pokaż tylko:

1. Listę utworzonych i zmienionych plików.

2. Które systemy mają realny materiał, a które są tylko mapą.

3. Kanały, które firma prowadzi POZA projektem, na przykład Instagram prowadzony ręcznie albo wysyłki z zewnętrznego narzędzia. Zanotuj je w projekty/cmo/ROADMAP.md, żeby nie zginęły przy budowie systemów.

4. Czy dopisano wywołanie @cmo do CLAUDE.md albo AGENTS.md, a jeśli nie, dlaczego.

5. Braki danych, które zauważyłeś.

6. Jeden proponowany następny mały krok.

7. Informację, że muszę zamknąć i ponownie otworzyć aplikację w tym samym folderze firmy, żeby @cmo zaczął działać.
~~~~
