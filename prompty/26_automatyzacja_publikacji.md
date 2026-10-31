# Automatyzacja publikacji (opcjonalnie)

Źródło: `biblioteka_promptow/37_w6_automatyzacja_publikacji.md` (W6 · P8). Treść: wersja wklejona przez użytkownika 2026-10-12, zgodna z biblioteką.
Dostosowanie do pracy na komputerze: zasady w `miro.md`.

## Treść promptu

~~~~text
@coo

Chcę opublikować kolejną wersję mojej strony, tym razem możliwie automatycznie, przez API, CLI albo inną metodę mojego hostingu.

Jestem osobą nietechniczną. Najpierw wytłumacz mi jednym prostym akapitem:

1. Czym jest API.
2. Czym jest CLI.
3. Czym jest API key albo token.
4. Dlaczego API key albo token jest jak hasło i nie wolno go wklejać publicznie.
5. Dlaczego niczego nie uruchamiasz bez mojego wyraźnego OK.

Najpierw sprawdź lokalnie:

1. Czy istnieje projekty/[nazwa-projektu]/strona/index.html.
2. Czy istnieją polityka-prywatnosci.html i cookies.html, jeśli robiliśmy Zadanie 7.
3. Czy strona otwiera się lokalnie.
4. Jeśli coś nie istnieje, zatrzymaj się i powiedz mi, czego brakuje.
5. Przebuduj po mojej zgodzie strona.zip według zadania 6: index.html, użyte assets/ i zatwierdzone podstrony z zadania 7. Bez projekt/, plików .md, sekretów i backupów. Sprawdź paczkę po rozpakowaniu, nie używaj starego ZIP-a. Metoda wysyłająca folder ma wysyłać ten sam komplet.
6. Z publikacja.md odczytaj istniejący projekt i URL. Aktualizuj ten adres, nie twórz nowego bez mojej zgody.

Potem zapytaj mnie:

1. Na jakim hostingu opublikowałem stronę w Zadaniu 6?
2. Czy to był Tiiny Host, Netlify, Vercel, GitHub Pages, własny hosting z panelem plików, WordPress, Webflow, Wix, Squarespace czy coś innego?
3. Czy chcę automatyzować publikację na tym samym hostingu, czy tylko zrozumieć, jak wygląda taki proces?
4. Czy mam API key, token, CLI albo instrukcję deployu z mojego hostingu?

Zasady:

1. Jeśli hosting to Tiiny Host, możesz użyć API Tiiny Host.
2. Jeśli hosting to Netlify albo Vercel, sprawdź, czy można użyć CLI tej platformy.
3. Jeśli hosting to GitHub Pages, wyjaśnij, że publikacja zwykle idzie przez GitHub i commit/push, a nie przez prosty upload API.
4. Jeśli hosting to WordPress, Webflow, Wix albo Squarespace, nie zakładaj, że zwykły upload HTML zadziała. Wyjaśnij ograniczenia i zapytaj o panel albo eksport/import.
5. Jeśli hosting to własny panel plików, wyjaśnij, że automatyzacja może wymagać FTP/SFTP albo panelowego API.
6. Jeśli nie znasz hostingu albo nie masz pewności, poproś o nazwę platformy, link do dokumentacji albo screenshot panelu. Nie zgaduj.
7. Jeśli platforma nie ma prostej automatyzacji dla początkujących, powiedz to wprost i zostaw ręczną publikację z Zadania 6 jako właściwą ścieżkę warsztatową.
8. API key, token, hasło FTP i inne sekrety nie mogą trafić do plików projektu ani na grupę. Jeśli trzeba ich użyć, zaproponuj zmienną środowiskową tylko na czas sesji.

Przygotuj plan automatycznej publikacji dla mojego hostingu:

1. Nazwa hostingu.
2. Najprostsza dostępna metoda automatyzacji: API, CLI, Git, FTP/SFTP albo brak sensownej automatyzacji.
3. Co będzie wysyłane.
4. Jakie dane dostępowe są potrzebne.
5. Jak bezpiecznie podać sekret bez zapisywania go w projekcie.
6. Komenda albo kroki, jeśli platforma to obsługuje.

Jeśli hosting to Tiiny Host:

1. Sprawdź aktualną oficjalną dokumentację: dostępność API w moim planie, uwierzytelnienie, upload ZIP-a i aktualizację istniejącej strony.
2. Bez dokumentacji nie wymyślaj endpointu ani komendy; wróć do ręcznej publikacji z zadania 6.
3. Dopasuj komendę do mojego systemu, Mac albo Windows.

Dla każdego hostingu:

1. Nie uruchamiaj komendy bez mojego OK.
2. Pokaż mi pliki, hosting i projekt, koszt oraz sposób wycofania. Brak ustalenia tych danych zatrzymuje wykonanie.
3. Zapytaj: "Czy uruchomić automatyczną publikację?"

Po mojej zgodzie:

1. Uruchom upload.
2. Pokaż publiczny URL.
3. Sprawdź publiczny URL, jeśli możesz.
4. Zapisz albo zaktualizuj publikacja.md.
5. Wpisz datę, nazwę hostingu, metodę publikacji, publiczny URL i nazwę projektu.
6. Zaktualizuj README.md, dopisując automatyczną metodę publikacji:
1. nazwa hostingu,
2. metoda: API, CLI, Git, FTP/SFTP albo inna,
3. bezpieczny sposób podania sekretu,
4. komenda albo kroki,
5. czego COO ma nie robić bez zgody użytkownika.
7. Pokaż zmianę w README.md i zapytaj o zgodę przed zapisem.

Na koniec pokaż:

PUBLICZNY URL: [...]
HOSTING: [...]
METODA PUBLIKACJI: [...]
PLIK STATUSU: projekty/[nazwa-projektu]/strona/publikacja.md
CO SPRAWDZIĆ RĘCZNIE: strona na telefonie, linki w stopce, baner cookies, przycisk CTA.
~~~~
