# SCLABS-222 – Edycja danych z nieprawidłowym hasłem – TC negatywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-222
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy system odrzuca próbę zapisania zmienionych danych, gdy użytkownik poda nieprawidłowe aktualne hasło.

## Warunki wstępne
- Sklep internetowy jest dostępny.
- Użytkownik posiada zarejestrowane konto i jest zalogowany.
- Użytkownik znajduje się w zakładce „Information”.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Edytuj wybrane dane użytkownika | Wprowadź nowe imię w polu „First name” | Nowa wartość zostaje wprowadzona do pola. |
| 2 | Podaj nieprawidłowe hasło | Hasło inne niż aktualne hasło do konta | Hasło zostaje wpisane w polu „Password”. |
| 3 | Zapisz zmiany | Kliknij „Save” | System odrzuca zmianę, nie zapisuje nowych danych i wyświetla odpowiedni komunikat. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
