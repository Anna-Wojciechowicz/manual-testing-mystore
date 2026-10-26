# SCLABS-233 – Próba zapisania nowego adresu bez uzupełnienia pól obowiązkowych – TC negatywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-233
- **Plan testów:** TP-03 – Zarządzanie adresami dostawy
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy system uniemożliwia zapisanie nowego adresu, gdy wymagane pola formularza pozostają niewypełnione.

## Warunki wstępne
- Użytkownik posiada konto w sklepie.
- Użytkownik jest zalogowany.
- Użytkownik znajduje się w sekcji „Your account”.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Przejdź do zakładki adresów użytkownika | Kliknij „Addresses” | Wyświetla się poprawnie strona z adresami użytkownika. |
| 2 | Otwórz formularz dodawania nowego adresu | Kliknij „Create new address” | Wyświetla się poprawnie formularz dodawania adresu. |
| 3 | Usuń wartości z pól obowiązkowych, pozostawiając je puste | First name, Last name, Address, City, Zip/Postal Code, Country (jeżeli formularz pozwala usunąć wybór) | Pola pozostają niewypełnione. |
| 4 | Spróbuj zapisać adres | Kliknij „Save” | System nie zapisuje adresu i informuje użytkownika o konieczności uzupełnienia wymaganych pól. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
