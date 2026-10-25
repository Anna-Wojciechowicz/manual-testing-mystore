# SCLABS-201 – Walidacja zgody "I agree to the terms and conditions and the privacy policy" – TC pozytywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-201
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy zaznaczenie obowiązkowej zgody pozwala zakończyć rejestrację, gdy pozostałe wymagania są spełnione.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest otwarty.
- Pola „First name”, „Last name”, „Email” i „Password” są wypełnione poprawnymi danymi.
- Zgoda „Customer data privacy” jest zaznaczona.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Sprawdź widoczność checkboxa zgody | Odszukaj checkbox w formularzu rejestracji | Checkbox jest widoczny |
| 2 | Zaznacz checkbox zgody | Kliknij checkbox „I agree to the terms and conditions and the privacy policy” | Checkbox zostaje zaznaczony |
| 3 | Spróbuj utworzyć konto | Kliknij przycisk „Save” | System pozwala zakończyć rejestrację i tworzy konto użytkownika |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
