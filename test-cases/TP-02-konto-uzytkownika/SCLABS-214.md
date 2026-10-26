# SCLABS-214 – Przypomnienie hasła – TC negatywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-214
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy system prawidłowo obsługuje próbę resetowania hasła dla adresu e-mail nieprzypisanego do istniejącego konta.

## Warunki wstępne
- Sklep internetowy jest dostępny.
- Użytkownik nie jest zalogowany.
- Formularz „Reset your password” jest otwarty.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Wprowadź adres e-mail | Adres e-mail nieprzypisany do żadnego konta | Adres e-mail zostaje wpisany w polu. |
| 2 | Wyślij prośbę o resetowanie hasła | Kliknij „SEND RESET LINK” | System nie wysyła linku resetującego dla nieistniejącego konta i wyświetla informację o błędnym adresie e-mail. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
