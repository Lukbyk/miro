# Instalacja systemu marketingowego CMO

Źródło: wiadomość użytkownika w sesji „Realizujemy w8”, 2026-10-12 (W8 · P1). Brak tego promptu w `biblioteka_promptow/`.
Dostosowanie do pracy na komputerze: zasady w `miro.md`.

## Treść promptu

~~~~text
PROMPT 1: Przygotowanie Folderów

Pracujemy w folderze mojego projektu.

Chcę zainstalować system marketingowy w folderze projekty/cmo.

To jest obecna wersja systemu marketingowego, którą będzie można później rozbudowywać. Nie pomniejszaj go w nazewnictwie.

Nie kasuj niczego i nie nadpisuj istniejących plików bez zgody.

Najpierw sprawdź:

1. Czy istnieje CLAUDE.md albo AGENTS.md.

2. Czy istnieją foldery dane, materialy, role i projekty.

3. Czy widzisz dokładnie pięć plików źródłowych:

   1. pliki/social.md

   2. pliki/social-planowanie.md

   3. pliki/social-linkedin.md

   4. pliki/newsletter.md

   5. pliki/reklamy.md

4. Jakie dane projektu są już dostępne:

   1. dane/profil.md albo profil.md

   2. dane/persona.md albo persona.md

   3. dane/oferta.md albo oferta.md

   4. dane/strona.md albo strona.md

   5. dane/plan.md albo plan.md

   6. dane/diagnoza-sprzedazy.md

   7. dane/wybor-lejka.md

   8. dane/plan-sprzedazy.md

   9. dane/pipeline.md

   10. dane/metryki-sprzedazy.md

Moje pliki firmy, na przykład profil.md, persona.md, oferta.md, plan.md albo strona.md, mogą leżeć w dane/ albo w głównym folderze firmy. Czytaj je z miejsca, w którym rzeczywiście są. Nie kopiuj ich, nie przenoś i nie twórz drugiej wersji.

Jeżeli ten sam plik istnieje w głównym folderze i w dane/, pokaż oba warianty i zapytaj mnie, który jest aktualny.

Jeżeli brakuje któregoś z pięciu plików źródłowych, zatrzymaj się i powiedz dokładnie, którego brakuje.

Jeżeli brakuje folderu projekty, zaproponuj utworzenie projekty/cmo i zapytaj o zgodę.

Pokaż mi strukturę, którą chcesz utworzyć:

projekty/cmo/

  ROADMAP.md

  CHANGELOG.md

  fundament/

  fundament/sciezka-klienta.md

  fundament/strategia-marketingu.md

  fundament/plan-marketingowy.md

  research/

  content-machine/

  social/social.md

  social/roadmap.md

  social/changelog.md

  social/docs/

  social/plany-contentu/

  social/linkedin/

  social/docs/planowanie.md

  social/docs/linkedin.md

  newsletter/newsletter.md

  newsletter/roadmap.md

  newsletter/changelog.md

  newsletter/wyniki/

  ads/ads.md

  ads/roadmap.md

  ads/changelog.md

  ads/kreacje/

W Zadaniu 1 możesz utworzyć foldery projekty/cmo/fundament/, projekty/cmo/research/, projekty/cmo/content-machine/, projekty/cmo/social/docs/, projekty/cmo/social/plany-contentu/, projekty/cmo/social/linkedin/, projekty/cmo/newsletter/wyniki/ i projekty/cmo/ads/kreacje/, ale nie twórz pustych plików roboczych. Pliki fundamentu, researchu, contentu, LinkedIna, newslettera i reklam powstaną dopiero w kolejnych zadaniach.

Zasady tworzenia systemu:

1. projekty/cmo/social/social.md jest głównym plikiem systemu social.

2. projekty/cmo/newsletter/newsletter.md jest głównym plikiem systemu newsletter.

3. projekty/cmo/ads/ads.md jest głównym plikiem systemu ads.

4. projekty/cmo/fundament/ jest lokalnym kontekstem strategicznym CMO.

5. Pliki w docs/ są dokumentacją, procedurami i standardami jakości, nie osobnymi asystentami.

6. roadmap.md zawiera rzeczy do rozbudowy.

7. changelog.md zawiera rzeczy zrobione.

8. Jeżeli plik docelowy istnieje, pokaż różnicę i zapytaj o zgodę.

9. W folderze social istnieje jeden nadrzędny asystent: @social, zapisany w projekty/cmo/social/social.md.

10. planowanie.md i linkedin.md są modułami dokumentacji używanymi przez @social, nie osobnymi asystentami, nie osobnymi wywołaniami i nie dodatkowymi promptami nadrzędnymi.

Na podstawie pięciu plików źródłowych utwórz główne pliki systemowe i dokumentację. Skopiuj treść źródeł do miejsc docelowych, nie usuwaj plików z folderu pliki/.

1. Skopiuj treść pliki/social.md do projekty/cmo/social/social.md jako nadrzędny prompt asystenta @social.

2. Skopiuj treść pliki/social-planowanie.md do projekty/cmo/social/docs/planowanie.md jako dokumentację modułu planowania dla @social.

3. Skopiuj treść pliki/social-linkedin.md do projekty/cmo/social/docs/linkedin.md jako dokumentację modułu LinkedIn dla @social.

4. Skopiuj treść pliki/newsletter.md do projekty/cmo/newsletter/newsletter.md jako główny prompt asystenta @newsletter.

5. Skopiuj treść pliki/reklamy.md do projekty/cmo/ads/ads.md jako główny prompt asystenta @ads.

Nie twórz generycznych plików głównych bez nazwy systemu.

Nie twórz projekty/cmo/social/social.md samodzielnie od zera, jeśli istnieje pliki/social.md. Użyj pliki/social.md jako źródła prawdy dla nadrzędnego prompta social.

Nie rozbijaj dokumentacji na osobne podfoldery systemu.

Nie twórz dodatkowych promptów konkurencyjnych dla @newsletter ani @ads w docs/. W tej instalacji newsletter/newsletter.md i ads/ads.md są głównymi promptami tych systemów.

Nie twórz osobnych asystentów typu @social-planowanie, @social-linkedin, @linkedin ani osobnych głównych promptów social.

Foldery projekty/cmo/social/plany-contentu/ i projekty/cmo/social/linkedin/ służą do historii wyników, nie do tworzenia osobnych asystentów.

Zasady dla głównych plików systemowych:

1. System może działać samodzielnie, bez głównego CMO.

2. System ma odpowiadać za cały swój folder.

3. System czyta swoją dokumentację, roadmapę, changelog i dane projektu.

4. System pilnuje jakości wyników, braków danych, ograniczeń i kolejnych kroków.

5. System aktualizuje albo proponuje aktualizacje swojej roadmapy.

6. System przygotowuje krótki raport stanu swojego obszaru.

7. System nie publikuje, nie wysyła, nie uruchamia reklam i nie wydaje budżetu bez zgody.

8. System nie wymaga uruchomienia social planowania, jeśli chcę pracować tylko z newsletterem albo tylko z reklamami.

9. System rozróżnia folder od asystenta: folder to projekty/cmo/social, a wywołanie to @social.

10. System traktuje projekty/cmo/fundament/sciezka-klienta.md, projekty/cmo/fundament/strategia-marketingu.md i projekty/cmo/fundament/plan-marketingowy.md jako wspólny fundament marketingowy, jeśli te pliki istnieją.

11. System nie nadpisuje fundamentu marketingowego automatycznie. Jeżeli podczas pracy odkryje nowy fakt, konflikt albo brak, proponuje konkretną aktualizację właściwego pliku fundamentu i pyta o zgodę.

12. System ma na końcu każdej większej pracy zostawić: wynik, decyzje, braki, następny krok, propozycję aktualizacji fundamentu marketingowego, propozycję wpisu do roadmapy i propozycję wpisu do changeloga.

13. System nie nadpisuje wyników contentowych. Każdy plan, wynik Content Machine, pakiet LinkedIn, newsletter i kreacja reklamowa mają trafić do folderu historii jako nowy plik z datą i krótkim slugiem oraz wpisem w INDEX.md.

14. Jeżeli folder historii nie ma INDEX.md, system tworzy go przy pierwszym zapisie po mojej zgodzie.

15. @social jest jednym systemem nadrzędnym dla social. Planowanie, Content Machine i LinkedIn są modułami pracy @social, a nie osobnymi asystentami.

16. Każdy główny prompt systemowy rozróżnia trzy tryby pracy zgodne z docelowym AI Marketing Lab: Strategia, Kreacja, Operacje.

projekty/cmo/social/social.md ma prowadzić folder social i umieć użyć:

1. projekty/cmo/social/docs/planowanie.md, gdy @social pracuje w module planowania, Content Machine i planowania social po przygotowaniu fundamentu marketingowego.

2. projekty/cmo/social/docs/linkedin.md, gdy @social pracuje w module LinkedIn.

3. projekty/cmo/social/plany-contentu/INDEX.md, gdy potrzebuje ostatnich planów contentu.

4. projekty/cmo/social/linkedin/INDEX.md, gdy potrzebuje historii wyników LinkedIn.

projekty/cmo/newsletter/newsletter.md ma prowadzić folder newsletter, być głównym promptem @newsletter i korzystać z projekty/cmo/newsletter/wyniki/INDEX.md, jeśli istnieje.

projekty/cmo/ads/ads.md ma prowadzić folder ads, być głównym promptem @ads i korzystać z projekty/cmo/ads/kreacje/INDEX.md, jeśli istnieje.

Każdy główny plik systemowy ma mieć strukturę:

1. Nazwa systemu.

2. Rola systemu.

3. Folder, którym system zarządza.

4. Dokumentacja, którą system czyta.

5. Dane wejściowe.

6. Wyniki, które system tworzy.

7. Standard jakości.

8. Granice, czego system nie robi bez zgody.

9. Tryb samodzielny, jak mogę pracować bez głównego CMO.

10. Tryb raportowania stanu systemu.

11. Zasada pracy z roadmapą.

12. Zasada pracy z changelogiem.

13. Zasada pracy z fundamentem marketingowym.

14. Format odpowiedzi po każdej większej pracy.

15. Trzy tryby pracy: Strategia, Kreacja, Operacje.

Format odpowiedzi po większej pracy:

1. Wynik.

2. Decyzje do mnie.

3. Braki danych.

4. Ryzyka jakości.

5. Następny krok.

6. Proponowana aktualizacja fundamentu marketingowego, jeśli odkryto nowy fakt, konflikt albo brak.

7. Proponowany wpis do roadmapy.

8. Proponowany wpis do changeloga, jeśli coś zostało wykonane.

9. Krótki raport stanu systemu.

Utwórz pliki roadmap.md:

1. projekty/cmo/social/roadmap.md

2. projekty/cmo/newsletter/roadmap.md

3. projekty/cmo/ads/roadmap.md

Każdy plik roadmap.md ma mieć sekcje:

1. Co już potrafi.

2. Jakie dane czyta.

3. Jakie wyniki oddaje.

4. Czego nie wolno mu zgadywać.

5. Co rozbudować później.

6. Jak testować jakość.

7. Miejsce w przyszłym większym systemie marketingowym.

8. Jak główny plik systemowy ma raportować stan systemu.

Utwórz pliki changelog.md:

1. projekty/cmo/social/changelog.md

2. projekty/cmo/newsletter/changelog.md

3. projekty/cmo/ads/changelog.md

Każdy plik changelog.md ma mieć sekcję startową:

1. Data utworzenia.

2. Co zostało zainstalowane.

3. Jakie główne prompty i moduły dokumentacji powstały.

4. Co jeszcze nie zostało wykonane.

Utwórz też projekty/cmo/ROADMAP.md:

1. Gotowe trzy foldery systemowe, trzy główne prompty asystentów i dwa moduły dokumentacji social.

2. Dane wspólne.

3. Kolejność pracy.

4. Co zostaje do rozbudowy w głównym systemie CMO.

5. Granice, system niczego nie publikuje, nie wysyła i nie odpala reklam bez zgody.

6. Mapowanie na większy system marketingowy.

7. Główne pliki systemowe: social/social.md, newsletter/newsletter.md, ads/ads.md.

W projekty/cmo/ROADMAP.md nazwij to systemem marketingowym CMO w obecnej wersji, który będzie dalej rozbudowywany.

Utwórz też projekty/cmo/CHANGELOG.md z informacją, że utworzono trzy foldery systemowe, trzy główne prompty, dwa moduły dokumentacji social, roadmapy i changelogi.

Mapowanie na większy system marketingowy:

1. projekty/cmo/social zasila obszar treści, planowania social media i LinkedIna.

2. projekty/cmo/newsletter zasila obszar newslettera, maila i ogrzewania relacji.

3. projekty/cmo/ads zasila obszar reklam i testów komunikatu.

4. Wideo jest adaptacją Content Machine, nie osobnym podsystemem w tej instalacji.

Po utworzeniu struktury obowiązkowo przejdź do integracji asystentów marketingowych z instrukcją projektu.

Sprawdź:

1. Czy istnieje AGENTS.md.

2. Czy istnieje CLAUDE.md.

3. Czy istnieje inny główny plik instrukcji projektu.

Jeżeli istnieje AGENTS.md albo CLAUDE.md, przygotuj sekcję do dopisania do każdego istniejącego pliku instrukcji projektu.

Jeżeli nie istnieje żaden plik instrukcji projektu, zaproponuj utworzenie AGENTS.md z tą sekcją.

Nie kończ zadania bez jasnego statusu:

1. Czy sekcja z asystentami marketingowymi została dopisana do AGENTS.md.

2. Czy sekcja z asystentami marketingowymi została dopisana do CLAUDE.md.

3. Jeżeli nie została dopisana, dlaczego.

4. Co muszę zatwierdzić, żeby wywołania @social, @newsletter i @ads działały w moim systemie.

Nie edytuj instrukcji projektu bez osobnej zgody.

W propozycji dopisania do instrukcji projektu rozróżnij foldery od wywołań asystentów:

1. Foldery systemu nie mają znaku @: projekty/cmo/social, projekty/cmo/newsletter, projekty/cmo/ads.

2. Wywołania asystentów mają znak @: @social, @newsletter, @ads.

3. Każdy folder systemowy ma główny plik systemowy: projekty/cmo/social/social.md, projekty/cmo/newsletter/newsletter.md, projekty/cmo/ads/ads.md.

4. @social korzysta z projekty/cmo/social/social.md i ma dwa moduły pracy w tej instalacji: planowanie oraz LinkedIn.

5. @newsletter korzysta z projekty/cmo/newsletter/newsletter.md.

6. @ads korzysta z projekty/cmo/ads/ads.md.

7. W instrukcji projektu jest tabela „Moi asystenci”: asystent, za co odpowiada, kiedy go wołać, po jednej linii na asystenta. Dopisz do niej @social, @newsletter i @ads. Jeśli tabeli nie ma, utwórz ją z asystentami, których już mam, np. @coo i @cso.

8. Wszystkie inne sekcje mojej instrukcji zostają bez zmian. Zmiany wprowadź w każdej istniejącej instrukcji projektu zgodnie z moją zasadą synchronizacji.

Propozycja dopisania do CLAUDE.md albo AGENTS.md ma mieć treść w tym stylu:

START SEKCJI DO INSTRUKCJI PROJEKTU

Nagłówek: System marketingowy CMO

Mam zainstalowany system marketingowy w projekty/cmo.

Foldery:

1. projekty/cmo/social

2. projekty/cmo/newsletter

3. projekty/cmo/ads

Główne pliki systemowe:

1. projekty/cmo/social/social.md

2. projekty/cmo/newsletter/newsletter.md

3. projekty/cmo/ads/ads.md

Dokumentacja:

1. projekty/cmo/social/docs/planowanie.md

2. projekty/cmo/social/docs/linkedin.md

3. Newsletter ma główny prompt w projekty/cmo/newsletter/newsletter.md.

4. Ads ma główny prompt w projekty/cmo/ads/ads.md.

Wywołania:

1. @social, używa projekty/cmo/social/social.md, a potem dobiera moduł planowania albo moduł LinkedIn.

2. @newsletter, używa projekty/cmo/newsletter/newsletter.md.

3. @ads, używa projekty/cmo/ads/ads.md.

Zasady:

1. @ oznacza asystenta, nie nazwę folderu.

2. Każdy folder systemowy ma własny plik nazwany jak system, który prowadzi ten folder jak marketing manager danego obszaru.

3. Każdy system może działać samodzielnie, zanim pojawi się główny CMO.

4. Każdy system pracuje w trzech trybach: Strategia, Kreacja, Operacje.

5. System czyta dane z dane/, a jeśli ich tam nie ma, sprawdza też starsze pliki w głównym folderze: profil.md, persona.md, oferta.md, plan.md, strona.md.

6. System niczego nie publikuje, nie wysyła i nie uruchamia reklam bez mojej zgody.

7. Dane wejściowe firmy czyta z dane/, ale wyniki pracy systemu marketingowego zapisuje w projekty/cmo/.

8. Fundament marketingowy zapisuje do projekty/cmo/fundament/.

9. Research zapisuje do projekty/cmo/research/.

10. Wyniki social zapisuje do projekty/cmo/social/.

11. Wyniki newslettera zapisuje do projekty/cmo/newsletter/.

12. Wyniki reklam zapisuje do projekty/cmo/ads/.

13. Po większej pracy system aktualizuje albo proponuje aktualizację swojej roadmapy.

14. Po wykonanej pracy system dopisuje albo proponuje wpis do changeloga.

15. projekty/cmo/fundament/sciezka-klienta.md, projekty/cmo/fundament/strategia-marketingu.md i projekty/cmo/fundament/plan-marketingowy.md są wspólnym fundamentem marketingowym dla social, newslettera i reklam.

16. Jeżeli @social, @newsletter albo @ads odkryje nowy fakt, konflikt albo brak w fundamencie, nie nadpisuje plików samowolnie. Proponuje konkretną zmianę do właściwego pliku i pyta o zgodę.

17. System marketingowy jest obecną wersją większego systemu, w którym podsystemy mogą być później koordynowane przez głównego CMO.

KONIEC SEKCJI DO INSTRUKCJI PROJEKTU

Zanim zapiszesz:

1. Pokaż listę plików do utworzenia.

2. Pokaż listę plików instrukcji projektu, które chcesz edytować albo utworzyć.

3. Pokaż listę plików, których nie ruszysz.

4. Pokaż dokładnie, gdzie dopiszesz sekcję asystentów marketingowych.

5. Zapytaj: Czy zapisać strukturę systemu i dopisać sekcję asystentów marketingowych do instrukcji projektu?

Zapisz dopiero po mojej zgodzie.

Jeżeli zgodzę się na zapis:

1. Zrób backup każdego pliku instrukcji projektu, który będziesz edytować.

2. Utwórz strukturę systemu.

3. Dopisz sekcję asystentów marketingowych do AGENTS.md, CLAUDE.md albo innego wskazanego pliku instrukcji projektu.

4. Jeżeli zgodzę się tylko na strukturę, ale nie na zmianę instrukcji projektu, zapisz strukturę i jasno oznacz, że wywołania @social, @newsletter i @ads nie zostały jeszcze podpięte w instrukcji projektu.

Po zapisie pokaż tylko:

1. Utworzoną strukturę.

2. Ścieżki głównych plików systemowych.

3. Ścieżki plików w docs/.

4. Ścieżki plików roadmap.md.

5. Ścieżki plików changelog.md.

6. Czy dopisano system marketingowy do CLAUDE.md albo AGENTS.md.

7. Braki danych, które zauważyłeś.

8. Stan instalacji i braki danych.

9. Informację, że muszę zamknąć i ponownie otworzyć aplikację w tym samym folderze firmy, żeby @social, @newsletter i @ads zaczęły działać.

10. Wiadomość testową, którą mam wkleić po ponownym otwarciu: @social pokaż menu
~~~~
