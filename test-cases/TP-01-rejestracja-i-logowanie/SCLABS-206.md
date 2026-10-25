# SCLABS-206 – Działanie checkboxa „Newsletter” – TC pozytywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-206
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy użytkownik może zaznaczyć i odznaczyć zgodę na otrzymywanie newslettera w formularzu rejestracji.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest otwarty.
- Wszystkie wymagane pola formularza są wypełnione poprawnymi danymi.
- Checkboxy „Customer data privacy” i „I agree to the terms and conditions and the privacy policy” są zaznaczone.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Sprawdź widoczność checkboxa „Newsletter” | Odszukaj checkbox „Newsletter” w formularzu rejestracji | Checkbox „Newsletter” jest widoczny |
| 2 | Sprawdź możliwość zaznaczenia zgody na newsletter | Zaznacz checkbox „Newsletter” | Checkbox zostaje zaznaczony |
| 3 | Sprawdź możliwość odznaczenia zgody na newsletter | Kliknij ponownie zaznaczony checkbox „Newsletter” | Checkbox zostaje odznaczony |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
