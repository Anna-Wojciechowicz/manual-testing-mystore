# SCLABS-202 – Walidacja zgody "I agree to the terms and conditions and the privacy policy" – TC negatywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-202
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy system blokuje rejestrację, gdy użytkownik nie zaznaczy obowiązkowej zgody.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest otwarty.
- Pola „First name”, „Last name”, „Email” i „Password” są wypełnione poprawnymi danymi.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Sprawdź widoczność checkboxa zgody | Odszukaj checkbox „I agree to the terms and conditions and the privacy policy” w formularzu rejestracji | Checkbox jest widoczny |
| 2 | Pozostaw checkbox niezaznaczony | Nie zaznaczaj checkboxa | Checkbox pozostaje niezaznaczony |
| 3 | Spróbuj utworzyć konto bez zgody | Kliknij przycisk „Save” | System nie pozwala zakończyć rejestracji bez wymaganej zgody |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
