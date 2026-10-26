# SCLABS-223 – Edycja danych bez podania aktualnego hasła – TC negatywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-223
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy system blokuje zapis zmienionych danych i wyświetla komunikat o konieczności wypełnienia pola „Password”, gdy użytkownik nie poda aktualnego hasła.

## Warunki wstępne
- Sklep internetowy jest dostępny.
- Użytkownik posiada zarejestrowane konto i jest zalogowany.
- Użytkownik znajduje się w zakładce „Information”.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Edytuj wybrane dane użytkownika | Wprowadź nowe imię w polu „First name” | Nowa wartość zostaje wprowadzona do pola. |
| 2 | Spróbuj zapisać zmiany bez podania hasła | Pozostaw pole „Password” puste i kliknij „Save” | System nie zapisuje zmian i wyświetla komunikat o konieczności wypełnienia pola „Password”. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
