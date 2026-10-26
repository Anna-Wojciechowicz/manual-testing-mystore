# SCLABS-219 – Wyświetlanie komunikatu po poprawnej edycji danych – TC pozytywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-219
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy po poprawnej edycji informacji o użytkowniku i zapisaniu zmian system wyświetla komunikat potwierdzający zmianę.

## Warunki wstępne
- Sklep internetowy jest dostępny.
- Użytkownik posiada zarejestrowane konto.
- Użytkownik jest zalogowany.
- Użytkownik znajduje się w zakładce „Information”.
- Użytkownik zna aktualne hasło.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Zmień wybrane dane użytkownika | Wprowadź nową wartość w wybranym polu, np. „First name” | Nowa wartość zostaje wprowadzona do pola. |
| 2 | Potwierdź zmianę danych | Wprowadź aktualne hasło w polu „Password” i kliknij „Save” | Zmiany zostają zapisane, a system wyświetla komunikat potwierdzający poprawną edycję danych. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
