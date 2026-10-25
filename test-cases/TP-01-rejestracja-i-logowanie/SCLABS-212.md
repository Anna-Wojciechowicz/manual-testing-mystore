# SCLABS-212 – Logowanie do serwisu przy użyciu niepoprawnych danych – TC negatywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-212
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy system odrzuca próbę logowania przy użyciu niepoprawnego hasła.

## Warunki wstępne

- Strona sklepu My Store jest dostępna.
- Użytkownik posiada konto w sklepie My Store.
- Użytkownik nie jest zalogowany.
- Formularz logowania jest otwarty.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Wprowadź adres e-mail | Podaj adres e-mail przypisany do istniejącego konta | Adres e-mail zostaje wpisany |
| 2 | Wprowadź niepoprawne hasło | Podaj błędne hasło do konta | Hasło zostaje wpisane |
| 3 | Spróbuj zalogować się do serwisu | Kliknij przycisk „SIGN IN” | System odrzuca próbę logowania, wyświetla informację o błędnych danych i nie loguje użytkownika |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
