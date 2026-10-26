# SCLABS-234 – Weryfikacja ścieżki nawigacyjnej w formularzu adresowym – TC pozytywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-234
- **Plan testów:** TP-03 – Zarządzanie adresami dostawy
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy w zakładce dodawania adresu wyświetla się ścieżka nawigacyjna w formacie określonym w specyfikacji.

## Warunki wstępne
- Użytkownik posiada konto w sklepie.
- Użytkownik jest zalogowany.
- Użytkownik znajduje się w sekcji „Your account”.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Przejdź do zakładki adresów użytkownika | Kliknij „Addresses” | Wyświetla się poprawnie strona adresów użytkownika. |
| 2 | Sprawdź ścieżkę nawigacyjną wyświetlaną na stronie | Breadcrumb | Ścieżka nawigacyjna poprawnie wyświetla się w formacie „Home/Your account/Addresses”. |
| 3 | Otwórz formularz dodawania nowego adresu | Kliknij „Create new address” | Wyświetla się poprawnie formularz dodawania adresu. |
| 4 | Sprawdź ścieżkę nawigacyjną formularza | Breadcrumb | Ścieżka nawigacyjna poprawnie wyświetla się w formacie „Home/Your account/Add new address” lub z nazwą zakładki zgodną z rzeczywistym interfejsem. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
