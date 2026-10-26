# SCLABS-226 – Zmiana hasła na krótsze niż 5 znaków – TC negatywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-226
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy system odrzuca próbę ustawienia nowego hasła zawierającego mniej niż 5 znaków.

## Warunki wstępne
- Sklep internetowy jest dostępny.
- Użytkownik posiada zarejestrowane konto i jest zalogowany.
- Użytkownik znajduje się w zakładce „Information”.
- Użytkownik zna aktualne hasło.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Wprowadź aktualne hasło | Poprawne hasło w polu „Password” | Hasło zostaje poprawnie wpisane w polu. |
| 2 | Wprowadź nowe hasło | `Ab1!` — 4 znaki w polu „New password” | System nie akceptuje nowego hasła, ponieważ zawiera mniej niż 5 znaków. |
| 3 | Spróbuj zapisać zmiany | Kliknij „Save” | System nie zmienia hasła i informuje o niespełnieniu wymagań dotyczących nowego hasła. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
