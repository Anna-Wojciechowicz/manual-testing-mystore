# SCLABS-220 – Komunikat po nieudanej edycji danych – TC negatywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-220
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy system nie wyświetla komunikatu o pomyślnym zapisaniu zmian, gdy edycja danych nie powiedzie się z powodu braku aktualnego hasła.

## Warunki wstępne
- Sklep internetowy jest dostępny.
- Użytkownik posiada zarejestrowane konto.
- Użytkownik jest zalogowany.
- Użytkownik znajduje się w zakładce „Information”.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Zmień wybrane dane użytkownika | Wprowadź nową wartość w polu „First name” | Nowa wartość zostaje wprowadzona do pola. |
| 2 | Spróbuj zapisać zmiany | Wprowadź nieprawidłowe hasło w polu „Password” i kliknij „Save” | System nie zapisuje zmian i wyświetla komunikat informujący o niepowodzeniu edycji. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
