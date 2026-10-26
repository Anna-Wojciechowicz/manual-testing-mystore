# SCLABS-225 – Zmiana hasła – TC pozytywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-225
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy zalogowany użytkownik może zmienić hasło, podając poprawne aktualne hasło oraz nowe hasło zawierające co najmniej 5 znaków.

## Warunki wstępne
- Sklep internetowy jest dostępny.
- Użytkownik posiada zarejestrowane konto i jest zalogowany.
- Użytkownik znajduje się w zakładce „Information”.
- Użytkownik zna aktualne hasło.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Wprowadź aktualne hasło | Poprawne hasło w polu „Password” | Hasło zostaje poprawnie wpisane w polu. |
| 2 | Wprowadź nowe hasło | Nowe hasło zawierające co najmniej 5 znaków, np. `Nowe123` | Nowe hasło zostaje poprawnie wpisane w polu „New password”. |
| 3 | Zapisz zmiany | Kliknij „Save” | System zapisuje nowe hasło i wyświetla komunikat potwierdzający zmianę. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
