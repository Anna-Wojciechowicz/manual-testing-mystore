# SCLABS-203 – Walidacja pola "Birthdate" – TC pozytywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-203
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy pole „Birthdate” akceptuje datę zapisaną w wymaganym formacie.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest otwarty.
- Wszystkie obowiązkowe pola są wypełnione danymi w poprawnym formacie.
- Wszystkie obowiązkowe checkboxy są zaznaczone.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Sprawdź widoczność pola „Birthdate” | Odszukaj pole „Birthdate” w formularzu rejestracji | Pole „Birthdate” jest widoczne |
| 2 | Sprawdź możliwość wprowadzenia daty | Wpisz datę w formacie `11/11/1990` | Pole pozwala wprowadzić datę w wymaganym formacie |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
