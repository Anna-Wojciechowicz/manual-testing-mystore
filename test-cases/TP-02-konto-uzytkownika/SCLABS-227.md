# SCLABS-227 – Zmiana hasła bez poprawnego aktualnego hasła – TC negatywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-227
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy system nie pozwala zmienić hasła, gdy użytkownik nie poda poprawnego aktualnego hasła.

## Warunki wstępne
- Sklep internetowy jest dostępny.
- Użytkownik posiada zarejestrowane konto i jest zalogowany.
- Użytkownik znajduje się w zakładce „Information”.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Wprowadź nieprawidłowe aktualne hasło | Niepoprawne hasło w polu „Password” | Hasło zostaje wpisane w polu. |
| 2 | Wprowadź nowe hasło | Nowe hasło zawierające co najmniej 5 znaków, np. `Nowe123` | Nowe hasło zostaje wpisane w polu „New password”. |
| 3 | Spróbuj zapisać zmiany | Kliknij „Save” | System nie zmienia hasła i wyświetla odpowiedni komunikat o błędnym aktualnym haśle. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
