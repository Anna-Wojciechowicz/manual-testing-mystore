# SCLABS-198 – Walidacja zgody „Customer data privacy” – TC pozytywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-198
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy zaznaczenie zgody „Customer data privacy” umożliwia przejście procesu rejestracji, gdy pozostałe wymagania są spełnione.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest otwarty.
- Pozostałe wymagane pola formularza są wypełnione poprawnymi danymi.
- Jest zaznaczony checkbox „I agree to the terms and conditions and the privacy policy”.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Sprawdź widoczność checkboxa „Customer data privacy”. | Odszukaj checkbox w formularzu rejestracji. | Checkbox jest widoczny. |
| 2 | Zaznacz checkbox „Customer data privacy”. | Kliknij checkbox „Customer data privacy”. | Checkbox zostaje zaznaczony. |
| 3 | Spróbuj utworzyć konto po zaznaczeniu zgody. | Kliknij przycisk „Save”. | System pozwala zakończyć rejestrację, a konto zostaje utworzone. |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
