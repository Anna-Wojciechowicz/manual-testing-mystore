# SCLABS-231 – Weryfikacja wyglądu aktywnych pól formularza adresowego – TC pozytywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-231
- **Plan testów:** TP-03 – Zarządzanie adresami dostawy
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy pola formularza dodawania adresu zmieniają wygląd po ich kliknięciu.

## Warunki wstępne
- Użytkownik posiada konto w sklepie.
- Użytkownik jest zalogowany.
- Użytkownik znajduje się w sekcji „Your account”.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Przejdź do zakładki adresów użytkownika | Kliknij „Addresses” | Wyświetla się poprawnie strona z adresami użytkownika. |
| 2 | Otwórz formularz dodawania nowego adresu | Kliknij „Create new address” | Wyświetla się formularz dodawania adresu. |
| 3 | Sprawdź wygląd kolejnych pól formularza po ich aktywowaniu | Kliknij kolejno: Alias, First name, Last name, Company, VAT number, Address, Address Complement, City, Zip/Postal Code, Country, Phone | Każde kliknięte pole zmienia kolor na biały i otrzymuje niebieskie obramowanie. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
