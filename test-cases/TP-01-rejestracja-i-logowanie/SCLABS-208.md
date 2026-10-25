# SCLABS-208 – Przejście z rejestracji do logowania – TC pozytywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-208
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy niezarejestrowany użytkownik może przejść z formularza rejestracji do formularza logowania za pomocą linku „Log in instead!”.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest otwarty.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Sprawdź widoczność linku do logowania | Odszukaj link „Log in instead!” w formularzu rejestracji | Link „Log in instead!” jest widoczny |
| 2 | Przejdź do formularza logowania | Kliknij link „Log in instead!” | Formularz logowania użytkownika otwiera się poprawnie |
| 3 | Sprawdź elementy formularza logowania | Sprawdź, czy formularz zawiera pola „Email” i „Password” oraz przycisk „SIGN IN” | Pola „Email” i „Password” oraz przycisk „SIGN IN” są widoczne |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
