# SCLABS-192 – Walidacja pola "Email" – brak znaku @ – TC negatywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-192
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy system odrzuca adres e-mail, który nie zawiera znaku @.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest otwarty.
- Pole „Email” jest widoczne i dostępne do edycji.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Otwórz przeglądarkę internetową. | — | Przeglądarka poprawnie się otwiera. |
| 2 | Przejdź na stronę sklepu My Store. | W wyszukiwarce wpisz https://dev-mystore-testlab.coderslab.pl/index.php | Strona poprawnie się otwiera. |
| 3 | Przejdź do zakładki logowania. | Kliknij zakładkę „Sign in”. | Zakładka logowania poprawnie się otwiera. |
| 4 | W zakładce logowania przejdź do zakładki tworzenia konta nowego użytkownika. | Kliknij zakładkę „No account? Create one here”. | Formularz do tworzenia konta nowego użytkownika poprawnie się otwiera. |
| 5 | Sprawdź walidację pola „Email”. | Wpisz w polu „Email” adres „annatest2026example.com”, bez znaku @. | System odrzuca nieprawidłowy adres e-mail i nie pozwala na zakończenie rejestracji. |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
