# SCLABS-190 – Walidacja pola "Email" – TC pozytywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-190
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy pole „Email” akceptuje poprawny adres e-mail, na który nie zostało jeszcze założone konto.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest otwarty.
- Pole „Email” jest widoczne i dostępne do edycji.
- Użyty adres e-mail nie jest przypisany do istniejącego konta.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Otwórz przeglądarkę internetową. | — | Przeglądarka poprawnie się otwiera. |
| 2 | Przejdź na stronę internetową sklepu My Store. | W wyszukiwarce wpisz https://dev-mystore-testlab.coderslab.pl/index.php | Strona poprawnie się otwiera. |
| 3 | Przejdź do zakładki logowania. | Kliknij zakładkę „Sign in”. | Zakładka poprawnie się otwiera. |
| 4 | W zakładce logowania przejdź do zakładki tworzenia konta nowego użytkownika. | Kliknij zakładkę „No account? Create one here”. | Formularz do tworzenia konta nowego użytkownika poprawnie się otwiera. |
| 5 | Sprawdź walidację pola „Email”. | Wpisz w polu „Email” adres „anna.test.2026@example.com”. | System informuje, że adres e-mail jest już używany, i nie pozwala utworzyć kolejnego konta na ten adres. |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
