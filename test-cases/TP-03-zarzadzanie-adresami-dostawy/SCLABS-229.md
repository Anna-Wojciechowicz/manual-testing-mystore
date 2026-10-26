# SCLABS-229 – Weryfikacja automatycznego uzupełniania danych użytkownika – TC pozytywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-229
- **Plan testów:** TP-03 – Zarządzanie adresami dostawy
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy podczas dodawania nowego adresu pola „First name”, „Last name” i „Country” są automatycznie uzupełniane danymi użytkownika, zgodnie z punktem 11 specyfikacji.

## Warunki wstępne
- Użytkownik posiada konto w sklepie.
- Użytkownik jest zalogowany.
- Użytkownik znajduje się w sekcji „Your account”.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Przejdź do zakładki „Addresses” | — | Wyświetla się poprawnie strona z adresami użytkownika. |
| 2 | Kliknij „Create new address” | — | Wyświetla się poprawnie formularz dodawania nowego adresu. |
| 3 | Sprawdź pole „First name” | — | Pole jest automatycznie uzupełnione prawidłowym imieniem użytkownika. |
| 4 | Sprawdź pole „Last name” | — | Pole jest automatycznie uzupełnione prawidłowym nazwiskiem użytkownika. |
| 5 | Sprawdź pole „Country” | — | Pole jest automatycznie uzupełnione poprawnym krajem użytkownika. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
