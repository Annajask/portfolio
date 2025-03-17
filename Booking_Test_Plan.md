# Plan Testów dla Platformy Booking.com
### Identyfikator raportu
TP_Booking_gen_V1

### 1. Cel testów:

Zapewnienie poprawności działania funkcji platformy Booking.com.
Weryfikacja, czy platforma działa zgodnie z wymaganiami użytkowników oraz specyfikacją.
### 2. Zakres testów:
**2.1. Testy Funkcjonalne:**

2.1.1. Rejestracja i logowanie:
- Rejestracja nowego użytkownika (formularz, walidacja danych).
- Logowanie (poprawne dane, błędne dane, odzyskiwanie hasła).
- Opcja logowania przez media społecznościowe (Google, Facebook).

2.1.2. Wyszukiwanie dostępnych ofert:
- Wyszukiwanie ofert według różnych kryteriów (data, miejsce, liczba osób).
- Działanie filtrów (cena, rodzaj obiektu, ocena).
- Sortowanie wyników (najtańsze, najdroższe, najlepsze oceny).

2.1.3. Rezerwacja noclegu:
- Proces rezerwacji pokoju (wybór pokoju, wprowadzenie danych, wybór metody płatności).
- Anulowanie rezerwacji.
- Działanie promocji i kuponów.

2.1.4. Płatności:
- Testowanie różnych metod płatności (karta kredytowa, PayPal, płatność przy zameldowaniu).
- Proces zwrotu pieniędzy.
- Poprawność generowania faktur i paragonów.

2.1.5. Zarządzanie kontem użytkownika:
- Edytowanie profilu użytkownika (adres, dane kontaktowe).
- Historia rezerwacji (sprawdzanie wcześniejszych rezerwacji).
- Zmiana preferencji (np. język, waluta).
- Lista ulubionych

**2.2. Testy niefunkcjonalne:**

2.2.1. Wydajność:
- Szybkość ładowania strony na różnych urządzeniach (desktop, mobile).
- Testowanie platformy pod kątem dużego ruchu użytkowników.
- Stabilność aplikacji przy dużej liczbie jednoczesnych rezerwacji.

2.2.2. Użyteczność:
- Nawigacja i intuicyjność interfejsu użytkownika.
- Testowanie dostępności na różnych urządzeniach (responsive design).
- Łatwość obsługi procesu rezerwacji

2.2.3. Bezpieczeństwo:
- Testowanie szyfrowania danych użytkowników.
- Testowanie ochrony danych osobowych.

### 3. Rodzaje testów:
- Testy manualne: Testowanie poszczególnych funkcji aplikacji przez testerów na różnych platformach (przeglądarki, urządzenia mobilne).
- Testy automatyczne: Automatyzacja procesów logowania, rezerwacji i płatności.
- Testy potwierdzające: Testowanie poprawności naprawiania zgłaszanych błędów.
- Testy regresji: Testowanie systemu po każdej aktualizacji oraz po naprawie błędów aby upewnić się, że nowe zmiany nie wpłynęły na istniejącą funkcjonalność.
- Testy integracyjne: Testowanie interakcji pomiędzy różnymi systemami (np. systemy płatności).

### 4. Środowisko testowe:
- Przeglądarki: Chrome, Firefox, Safari, Edge.
- Urządzenia: Desktop (Windows, macOS), mobile (Android, iOS).
- Bazy danych: Testowanie integracji z bazą danych systemu rezerwacji.

### 5. Zasoby:
- Zespół testerów: Testerzy manualni, testerzy automatyczni, specjalista od bezpieczeństwa.
- Narzędzia: Jira (zarządzanie zgłoszeniami), Selenium (automatyzacja), JMeter (testy wydajnościowe).

### 6. Plan czasowy:
- Przygotowanie testów: 1 tydzień
- Testy funkcjonalne: 2 tygodnie
- Testy niefunkcjonalne: 1 tydzień
- Testy potwierdzające, regresji i integracji: 2 tygodnie
- Raportowanie i analiza wyników: 1 tydzień

### 7. Kryteria zakończenia testów:
- Wszystkie przypadki testowe wykonane.
- Wszelkie krytyczne błędy muszą zostać naprawione i ponownie przetestowane.
- Wszystkie przypadki testowe zakończone wynikiem negatywnym z zaplanowanym akcjami i terminem wykonania.
- Przygotowany raport z testów.

### 8. Ryzyka:
- Ograniczona dostępność testera automatyzującego.
