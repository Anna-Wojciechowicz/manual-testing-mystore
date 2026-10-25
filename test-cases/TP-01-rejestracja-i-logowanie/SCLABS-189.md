# SCLABS-189 – Walidacja pola "Last name" – TC negatywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-189
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy pole „Last name” odrzuca wartość zawierającą znaki inne niż litery.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest otwarty.
- Pole „First name” jest widoczne i dostępne do edycji.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Otwórz przeglądarkę internetową. | — | Przeglądarka poprawnie się otwiera. |
| 2 | Przejdź na stronę internetową sklepu My Store. | W wyszukiwarce wpisz https://dev-mystore-testlab.coderslab.pl/index.php | Strona poprawnie się otwiera. |
| 3 | Przejdź do zakładki logowania. | Kliknij zakładkę „Sign in”. | Zakładka logowania poprawnie się otwiera. |
| 4 | W zakładce logowania przejdź do zakładki tworzenia konta nowego użytkownika. | Kliknij zakładkę „No account? Create one here”. | Formularz do tworzenia konta nowego użytkownika poprawnie się otwiera. |
| 5 | Sprawdź walidację pola „Last name”. | W polu „Last name” wpisz wartość „Kowalska123”. | System nie akceptuje wpisanej wartości zawierającej znaki inne niż litery. |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
