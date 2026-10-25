# SCLABS-213 – Przypomnienie hasła – TC pozytywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-213
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy zarejestrowany użytkownik może zainicjować procedurę resetowania hasła poprzez podanie adresu e-mail przypisanego do istniejącego konta.

## Warunki wstępne

- Sklep internetowy jest dostępny.
- Użytkownik posiada zarejestrowane konto.
- Użytkownik nie jest zalogowany.
- Formularz logowania jest otwarty.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Przejdź do formularza resetowania hasła | Kliknij „Forgot your password?” | Wyświetla się formularz „Reset your password” z polem „Email address” i przyciskiem „SEND RESET LINK” |
| 2 | Wprowadź adres e-mail | Adres e-mail przypisany do istniejącego konta | Adres e-mail zostaje wpisany w polu |
| 3 | Wyślij prośbę o resetowanie hasła | Kliknij „SEND RESET LINK” | System przyjmuje zgłoszenie i wyświetla odpowiedni komunikat dotyczący resetowania hasła |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
