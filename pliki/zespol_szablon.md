# ZESPÓŁ (dane/zespol.md)

## INSTRUKCJA (przeczytaj, potem usuń tę sekcję)

Ten plik trzyma stan zespołu ludzkiego firmy. Prowadzi go `@ceo`.
Wypełniasz go wywiadem: `@ceo` przechodzi z Tobą przez każdą osobę i pyta o jej rolę,
zadania, dane, asystenta. Aktualizujesz przy KAŻDEJ zmianie w zespole: nowa osoba,
zmiana zakresu, nowy asystent, zgłoszenie od pracownika.

Po co ten plik istnieje: żeby role AI wiedziały, kto jest w firmie, kto co robi, kto ma
asystenta i jaki kontekst każda osoba widzi. To tu `@coo` sprawdza obszar LUDZIE w audycie
autonomii. Bez tego pliku firma nie wie o sobie samej.

Zasada danych: wspólny kontekst widzą wszyscy, dane prywatne roli widzi tylko ta rola,
finanse i wrażliwe rzeczy widzi tylko właściciel. Rozpisujesz to per osoba niżej.

---

## TABELA ZBIORCZA ZESPOŁU

| Osoba | Rola | Główne zadania | Ma asystenta | Onboarding | Przegląd |
|-------|------|----------------|--------------|------------|----------|
| [imię] | [rola] | [1 do 2 zadań] | TAK / NIE | [nowy / w toku / gotowy] | [data] |
| [imię] | [rola] | [...] | TAK / NIE | [...] | [data] |

Legenda onboardingu:
- **nowy** to osoba jest, ale nie ma jeszcze asystenta ani wspólnego kontekstu.
- **w toku** to asystent w budowie albo kontekst częściowy.
- **gotowy** to ma asystenta i widzi wspólne dane.

---

## KARTA OSOBY: Anna (PRZYKŁAD, podmień na swój zespół)

> To jest przykład dla małej firmy usługowej. Podmień na realną osobę ze swojego zespołu.

**Rola i zadania powtarzalne:**
Asystentka biura. Obsługuje maile przychodzące, umawia spotkania, wystawia proste dokumenty,
prowadzi kalendarz właściciela, odpowiada klientom na pytania o dostępność i ceny.

**Gdzie traci najwięcej czasu:**
Powtarzalne odpowiedzi na te same pytania klientów (godziny, ceny, dostępność) oraz ręczne
przepisywanie danych z maili do kalendarza i do arkusza klientów.

**Jakich danych używa:**
Cennik, grafik dostępności, standardowe odpowiedzi na częste pytania, lista klientów.

**Asystent:**
- Nazwa roli: `@biuro`
- Plik: `role/biuro.md`
- Data przekazania: [data albo BRAK, jeśli jeszcze nie ma]

**Dane wspólne, które widzi:**
Cennik, oferta, standardowe odpowiedzi, grafik dostępności, persona klienta.

**Dane prywatne roli:**
Skrzynka biura, wersje robocze odpowiedzi, notatki z rozmów z klientami.

**Czego NIE widzi:**
Finanse firmy, marże, dane wynagrodzeń, decyzje strategiczne właściciela.

**Lekcje i zgłoszenia od tej osoby:**
| Data | Wpis |
|------|------|
| [data] | [np. "Klienci często pytają o parking, dodać do standardowych odpowiedzi"] |

**Następny krok onboardingu:**
Zebrać 20 najczęstszych pytań klientów i wgrać jako standardowe odpowiedzi do `@biuro`.

---

## KARTA OSOBY: [imię]

**Rola i zadania powtarzalne:**
[co robi, jakie zadania wracają co tydzień]

**Gdzie traci najwięcej czasu:**
[konkretne wąskie gardło czasowe]

**Jakich danych używa:**
[pliki, arkusze, dokumenty]

**Asystent:**
- Nazwa roli: [np. @rola albo BRAK]
- Plik: [ścieżka albo BRAK]
- Data przekazania: [data albo BRAK]

**Dane wspólne, które widzi:**
[lista]

**Dane prywatne roli:**
[lista]

**Czego NIE widzi:**
[lista, np. finanse]

**Lekcje i zgłoszenia od tej osoby:**
| Data | Wpis |
|------|------|
| [data] | [wpis] |

**Następny krok onboardingu:**
[jedna konkretna akcja]

---

## RYTM AKTUALIZACJI KONTEKSTU

Raz w tygodniu właściciel siada z `@ceo` i robi krótki przegląd zespołu:

1. **Zgłoszenia.** Przejrzyj lekcje i zgłoszenia od każdej osoby z ostatniego tygodnia.
   To, co się powtarza, wchodzi do wspólnych danych albo do asystenta tej osoby.
2. **Wspólne dane.** Zaktualizuj pliki, które zmieniły się w tym tygodniu
   (cennik, oferta, standardowe odpowiedzi, grafik).
3. **Informacja do zespołu.** Powiedz zespołowi, co się zmieniło. Ludzie i ich asystenci
   pracują na tym samym, aktualnym kontekście, nie na starym.
4. **Onboarding.** Sprawdź kolumnę Onboarding w tabeli zbiorczej. Rusz każdą osobę
   o jeden krok dalej: nowy do w toku, w toku do gotowy.

Zasada: kontekst, którego nikt nie aktualizuje, po miesiącu jest martwy.
Ten rytm trzyma go przy życiu.
