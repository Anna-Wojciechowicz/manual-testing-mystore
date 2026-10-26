# SCLABS-375 – Próba zmiany hasła na takie samo jak dotychczasowe – TC negatywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-375
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy system pozwala ustawić nowe hasło identyczne z aktualnym.

## Warunki wstępne
- Użytkownik jest zalogowany i zna swoje aktualne hasło.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Przejdź do zmiany hasła | Otwórz zakładkę z nazwą użytkownika | Wyświetla się poprawnie formularz „Your personal information”. |
| 2 | Wprowadź aktualne hasło oraz takie samo hasło w polu nowego hasła i jego potwierdzeniu | Uzupełnij pole „Password” aktualnym hasłem `Hasło123` | Aktualne hasło zostaje poprawnie uzupełnione. |
| 3 | Wprowadź nowe hasło w polu „New password” | Wpisz takie samo hasło jak obecne: `Hasło123` | System odrzuca zmianę. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
