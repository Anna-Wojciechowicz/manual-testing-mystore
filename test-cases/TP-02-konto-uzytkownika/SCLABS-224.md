# SCLABS-224 – Edycja pozostałych danych podczas zmiany hasła – TC pozytywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-224
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy podczas edycji hasła użytkownik może również edytować pozostałe dane swojego konta.

## Warunki wstępne
- Sklep internetowy jest dostępny.
- Użytkownik posiada zarejestrowane konto i jest zalogowany.
- Użytkownik znajduje się w zakładce „Information”.
- Użytkownik zna aktualne hasło.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Wprowadź nowe hasło | Wpisz nowe hasło w polu „New password” | Nowe hasło zostaje poprawnie wprowadzone do pola. |
| 2 | Edytuj pozostałe dane | Wprowadź nowe imię w polu „First name” | Nowa wartość zostaje poprawnie wprowadzona do pola. |
| 3 | Wprowadź nowe nazwisko | Wprowadź nowe nazwisko w polu „Last name” | Nowa wartość zostaje poprawnie wprowadzona do pola. |
| 4 | Wprowadź nowy adres e-mail | Wprowadź nowego e-maila w polu „Email” | Nowa wartość zostaje poprawnie wprowadzona do pola. |
| 5 | Podaj aktualne hasło | Wpisz aktualne hasło w polu „Password” | Aktualne hasło zostaje poprawnie wpisane w polu. |
| 6 | Zapisz zmiany | Kliknij „Save” | System zapisuje nowe hasło i zmienione dane użytkownika oraz wyświetla komunikat potwierdzający zapis zmian. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
