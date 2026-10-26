# SCLABS-232 – Zapisanie nowego adresu z poprawnymi danymi – TC pozytywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-232
- **Plan testów:** TP-03 – Zarządzanie adresami dostawy
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy użytkownik może zapisać nowy adres po poprawnym uzupełnieniu formularza i kliknięciu przycisku „Save”.

## Warunki wstępne
- Użytkownik posiada konto w sklepie.
- Użytkownik jest zalogowany.
- Użytkownik znajduje się w sekcji „Your account”.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Przejdź do zakładki adresów użytkownika | Kliknij „Addresses” | Wyświetla się poprawnie strona z adresami użytkownika. |
| 2 | Otwórz formularz dodawania nowego adresu | Kliknij „Create new address” | Wyświetla się poprawnie formularz dodawania adresu. |
| 3 | Uzupełnij formularz poprawnymi danymi adresowymi | First name: Jan; Last name: Kowalski; Address: Testowa 10; City: Wrocław; Zip/Postal Code: 50-001; Country: Poland | Dane zostają poprawnie wprowadzone. |
| 4 | Zapisz nowy adres | Kliknij „Save” | Adres zostaje zapisany i jest widoczny na liście adresów użytkownika. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
