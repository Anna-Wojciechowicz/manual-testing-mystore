# SCLABS-197 – Działanie checkboxa „Customer data privacy” – TC negatywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-197
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy system nie pozwala zakończyć rejestracji bez zaznaczenia obowiązkowej zgody „Customer data privacy”.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest otwarty.
- Pozostałe wymagane pola formularza są wypełnione poprawnymi danymi.
- Checkbox „I agree to the terms and conditions and the privacy policy” jest zaznaczony.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Sprawdź widoczność checkboxa „Customer data privacy”. | Odszukaj checkbox w formularzu rejestracji. | Checkbox „Customer data privacy” jest widoczny w formularzu. |
| 2 | Sprawdź, czy checkbox nie jest zaznaczony. | Pozostaw checkbox niezaznaczony. | Checkbox pozostaje niezaznaczony. |
| 3 | Spróbuj utworzyć konto bez zaznaczenia zgody. | Kliknij przycisk „Save”. | System nie pozwala zakończyć rejestracji bez wymaganej zgody. |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
