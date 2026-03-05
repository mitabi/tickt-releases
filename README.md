# Tickt — Prosty Tracker Czasu Pracy

Aplikacja desktopowa do śledzenia czasu pracy, zarządzania projektami i rozliczania godzin z klientami.

## 🎯 Dla kogo?

- **Freelancerzy** — rozliczaj pracę per projekt/klient
- **Agencje** — śledzenie czasu zespołu na różnych projektach  
- **Konsultanci** — fakturuj faktycznie przepracowane godziny
- **Każdy** — kto potrzebuje przejrzystości w zarządzaniu czasem pracy

## ✨ Główne cechy

### Śledzenie czasu
- Uruchamiaj timer z przyciskiem „Play" — pracuj i automatycznie zbieraj godziny
- Zatrzymaj timer kiedy skończysz — zapisz wpis z opisem i projektami
- Edytuj wpisy ręcznie (zmień czas/projekt/klienta)
- Szablony do szybkiego dodawania powtarzających się zadań

### Inteligentne zarządzanie
- **Detekcja bezczynności** — aplikacja wykrywa gdy nie pracujesz (30+ minut braku aktywności) i pyta czy odjąć ten czas
- Tagi do kategoryzowania wpisów (np. #design #frontend #testing)
- Opisy dla każdego wpisu (co dokładnie robiłeś?)
- Status: rozliczony/nierozliczony — prześledzaj co było zafakturowane

### Raporty i rozliczenia
- **Raporty okresu** — ten tydzień, ten miesiąc, poprzedni miesiąc
- Filtruj po kliencie, projekcie, dacie, opisie, statusie
- Dostosowuj kolumny raportu (pokaż/ukryj co potrzebujesz)
- **Eksport** — CSV (do Excela) lub PDF (do wydruku/wysłania)
- Sekcja „Do zafakturowania" — przegląd zaległych zafakturować wpisów

### Stawki godzinowe
- Przypisz stawkę każdemu projektowi (np. 50 PLN/h, 100 EUR/h)
- Każda zmiana stawki działa domyślnie **od dnia zmiany** (przyszłe wpisy)
- Opcja **przeliczenia historii** — jeśli zmieniła się stawka, możesz przeliczyć starsze wpisy
- Multi-waluta — każdy projekt może być rozliczany w innej walucie

### Cele i produktywność
- Ustaw dzienny cel (np. 8 godzin)
- Ustaw tygodniowy cel (np. 40 godzin)
- Widok produktywności — fokus vs. bezczynność (dzień/tydzień)
- Wskaźnik postępu do celu w głównym widoku

### Bezpieczeństwo danych
- **Wszystko lokalnie** — dane nigdy nie opuszczają Twojego komputera
- **Backup i przywracanie** — utwórz backup wszystkich danych w pliku ZIP
- **Auto-backup** — opcjonalnie twórz kopie automatycznie co N godzin
- Retencja backupów — przechowuj ostatnie N kopii (domyślnie 10)

### Wygoda
- **Ciemny i jasny motyw** — wybierz co podoba Ci się w oczy
- **Zapamiętywanie ustawień** — okno zawsze na wierzchu, ostatnie ustawienia raportu
- **Auto-aktualizacja** — aplikacja sama się aktualizuje gdy dostępna jest nowa wersja
- **Malutki footprint** — aplikacja nie spowalnia komputera

## 🚀 Start — pierwsze kroki

### Instalacja
1. Pobierz najnowszą wersję z [GitHub Releases](https://github.com/mitabi/tickt-releases/releases)
2. Uruchom instalator (`.exe`)
3. Czekaj na instalację — zajmie ~30 sekund
4. Aplikacja uruchomi się sama

### Pierwszy wpis — 5 minut
1. Kliknij **„Dodaj klienta"** (sekcja Klienci)
   - Wpisz nazwę (np. „Acme Corp")
   - Wybierz walutę (PLN, EUR, USD)

2. Kliknij **„Dodaj projekt"** (sekcja Projekty)
   - Wybierz klienta
   - Wpisz nazwę projektu (np. „Website redesign")
   - Ustaw stawkę godzinową (np. 100 PLN)

3. Uruchom timer
   - Wybierz projekt z menu
   - Kliknij **Play** ▶️
   - Pracuj...
   - Kliknij **Stop** ⏹️
   - Dodaj opis (opcjonalnie)
   - Kliknij **Zapisz wpis**

4. Sprawdź raport
   - Ustaw okres (np. „ten tydzień")
   - Obejrzyj podsumowanie godzin i wartość

## 📋 Popularne zadania

### Mam mnóstwo starych wpisów do zaladowania
Edytuj wpisy ręcznie:
1. Kliknij **„Edytuj"** przy wpisie
2. Zmień czas/datę/projekt
3. Zapisz

Lub skontaktuj się — jeśli masz CSV, mogę pomóc importować dane.

### Właśnie zmieniłem stawkę projektu — co z wczorajszymi wpisami?
Domyślnie nowa stawka dotyczy **przyszłych wpisów**. 

Jeśli chcesz przeliczenie wczorajszych:
1. Przejdź do ustawień
2. Znajdź **„Tryb przeliczenia stawek"**
3. Wybierz **„Przelicz całą historię"**
4. Zmień stawkę — wszystkie wpisy zostaną przeznowelizowane

Zapisz zmianę — gotowe!

### Zatraconym godziny bezczynności (idle)
Aplikacja automatycznie wykonuje to:
1. Gdy wróciłeś do pracy (30+ minut braku aktywności)
2. Aplikacja pyta: „Chcesz odjąć [3h 45m] bezczynności?"
3. Kliknij **Tak** lub **Nie**

Możesz też ręcznie edytować wpis i usunąć idle segmenty.

### Chcę wyeksportować raport do klienta
1. Ustaw okres i filtry w raporcie
2. Kliknij **„Eksportuj"**
3. Wybierz format:
   - **PDF** — gotowe do wysłania/wydruku
   - **CSV** — do Excela/przetwarzania
4. Zapisz plik — gotowe!

### Backup danych — procedura
1. Przejdź do ustawień → **Backup**
2. Kliknij **„Utwórz backup"**
3. Wybierz gdzie zapisać plik `.zip`
4. Plik zawiera wszystkie dane i ustawienia

**Ważne:** Rób backup przynajmniej raz w tygodniu!

Przywracanie:
1. Ustawienia → **Backup**
2. **„Przywróć backup"**
3. Wybierz plik `.zip`
4. Aplikacja się restartuje z przywróconymi danymi

## ❓ FAQ

**P: Czy moje dane będą wysyłane na serwer?**  
O: Nie. Wszystkie dane są przechowywane **tylko na Twoim komputerze**. Aplikacja nie łączy się z żadnym serwerem — chyba że sprawdzam aktualizacje.

**P: Czy mogę korzystać z tej samej bazy na wielu komputerach?**  
O: Nie — każdy komputer ma własną bazę. Aby synchronizować, eksportuj backup z jednego i przywróć na innym.

**P: Co się stanie jeśli zabraknie moim danych?**  
O: Pamiętaj o backupach! Bez backupu — dane znikają. Rób backup regularnie.

**P: Jak wyłączyć detekcję bezczynności?**  
O: Ustawienia → **Detekcja bezczynności** → ustaw na 0 minut (wyłączone).

**P: Czy mogę edytować wpisów sprzed jakiegoś czasu?**  
O: Tak! Kliknij „Edytuj" przy dowolnym wpisie i zmień co potrzebujesz.

**P: Czemu timer wybiera projekt z ostatnio zrobionego wpisu?**  
O: Żeby Ci zaoszczędzić kliki! Jeśli pracujesz na tym samym projekcie — start jest szybszy.

## 🛠️ Troubleshooting

### Aplikacja się nie otwiera
- Sprawdź czy Windows Defender nie blokuje (dodaj do wyjątków)
- Spróbuj odinstalować i zainstalować ponownie

### Nie mogę przywrócić backupu
- Upewnij się że plik jest w formacie `.zip` z tej aplikacji
- Zamknij aplikację, spróbuj ponownie
- Jeśli błąd powtarza się — backup może być uszkodzony

### Timer się nie zatrzymuje
- Zamknij aplikację całkowicie (Alt+F4)
- Jeśli timer dalej biega — restartuj komputer

### Gdzie są moje dane?  
- Dane przechowywane są w: `C:\Users\[Twoje_Imię]\AppData\Local\dev.tickt.app`
- Nie usuwaj tego folderu — inaczej stracisz dane!

## 📞 Wsparcie i błędy

Jeśli coś nie działa:
1. Sprawdź czy masz najnowszą wersję (w aplikacji → sprawdź aktualizacje)
2. Spróbuj ponownie zalogować się (zamknij i otwórz aplikację)
3. Zrób backup swoich danych (na wszelki wypadek)
4. Jeśli problem powtarza się — zgłoś na [GitHub Issues](https://github.com/mitabi/tickt/issues)

## 📚 Więcej informacji

- **Kod źródłowy:** [github.com/mitabi/tickt](https://github.com/mitabi/tickt)
- **Wydania:** [github.com/mitabi/tickt-releases](https://github.com/mitabi/tickt-releases)
- **Changelog:** [patrz CHANGELOG.md](https://github.com/mitabi/tickt/blob/main/CHANGELOG.md)

---

**Wersja aktywna:** Sprawdzisz w aplikacji → Informacje → Wersja

**Ostatnia aktualizacja:** 5 marca 2026

**Licencja:** Sprawdzisz w aplikacji
