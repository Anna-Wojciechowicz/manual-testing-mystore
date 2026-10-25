# SCLABS-186 – Walidacja pola "First name" – TC pozytywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-186
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy pole „First name” akceptuje wartość zawierającą wyłącznie litery.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest poprawnie otwarty.
- Pole „First name” jest widoczne i dostępne do edycji.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Otwórz przeglądarkę internetową. | — | Przeglądarka internetowa poprawnie się otwiera. |
| 2 | Przejdź na stronę internetową sklepu My Store. | Wpisz w wyszukiwarkę https://dev-mystore-testlab.coderslab.pl/ | Strona poprawnie się otwiera. |
| 3 | Przejdź do zakładki logowania. | Kliknij zakładkę „Sign in”. | Zakładka logowania poprawnie się otwiera. |
| 4 | W zakładce logowania przejdź do zakładki tworzenia konta nowego użytkownika. | Kliknij zakładkę „No account? Create one here”. | Formularz do tworzenia konta nowego użytkownika poprawnie się otwiera. |
| 5 | Sprawdź walidację pola „First name”. | Wpisz w polu „First name” wartość „Anna”. | System akceptuje wartość zawierającą wyłącznie litery. |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
