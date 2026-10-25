# SCLABS-204 – Walidacja pola "Birthdate" – TC negatywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-204
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy pole „Birthdate” odrzuca datę zapisaną w nieprawidłowym formacie.

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
| 2 | Sprawdź walidację formatu daty | Wpisz datę w nieprawidłowym formacie, np. `AA/BB/CCCC` | System odrzuca datę w nieprawidłowym formacie |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
