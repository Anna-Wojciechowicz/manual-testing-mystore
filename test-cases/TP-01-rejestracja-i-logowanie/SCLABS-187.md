# SCLABS-187 – Walidacja pola "First name" – TC negatywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-187
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy pole „First name” odrzuca wartość zawierającą znaki inne niż litery.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest poprawnie otwarty.
- Pole „First name” jest widoczne i dostępne do edycji.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Otwórz przeglądarkę internetową. | — | Przeglądarka poprawnie się otwiera. |
| 2 | Przejdź na stronę sklepu My Store. | Wpisz w wyszukiwarkę https://dev-mystore-testlab.coderslab.pl/ | Strona poprawnie się otwiera. |
| 3 | Przejdź do zakładki logowania. | Kliknij zakładkę „Sign in”. | Zakładka logowania poprawnie się otwiera. |
| 4 | W zakładce logowania przejdź do zakładki tworzenia konta nowego użytkownika. | Kliknij zakładkę „No account? Create one here”. | Formularz do tworzenia konta nowego użytkownika poprawnie się otwiera. |
| 5 | Sprawdź walidację pola „First name”. | W polu „First name” wpisz wartość „Anna123”. | System nie akceptuje wpisanej wartości zawierającej znaki inne niż litery. |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
