# SCLABS-221 – Edycja danych użytkownika – TC pozytywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-221
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy zalogowany użytkownik może edytować wybrane dane i zapisać zmiany po podaniu aktualnego hasła.

## Warunki wstępne
- Sklep internetowy jest dostępny.
- Użytkownik posiada zarejestrowane konto i jest zalogowany.
- Użytkownik znajduje się w zakładce „Information”.
- Użytkownik zna aktualne hasło.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Edytuj wybrane dane użytkownika | Wprowadź nowe imię w polu „First name” | Nowa wartość zostaje wprowadzona do pola. |
| 2 | Podaj aktualne hasło | Poprawne hasło do konta | Hasło zostaje wpisane w polu „Password”. |
| 3 | Zapisz zmiany | Kliknij „Save” | System zapisuje zmiany i wyświetla komunikat potwierdzający ich zapis. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
