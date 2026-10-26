# SCLABS-230 – Weryfikacja pól obowiązkowych i opcjonalnych formularza adresowego – TC pozytywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-230
- **Plan testów:** TP-03 – Zarządzanie adresami dostawy
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy formularz dodawania adresu prawidłowo rozróżnia pola obowiązkowe i opcjonalne oraz umożliwia zapisanie adresu bez uzupełniania pól opcjonalnych.

## Warunki wstępne
- Użytkownik posiada konto w sklepie.
- Użytkownik jest zalogowany.
- Użytkownik znajduje się w sekcji „Your account”.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Przejdź do zakładki „Addresses” | — | Wyświetla się strona z adresami użytkownika. |
| 2 | Kliknij „Create new address” | — | Wyświetla się formularz dodawania nowego adresu. |
| 3 | Sprawdź pola formularza i oznaczenia pól opcjonalnych | Alias, Company, VAT number, Address Complement, Phone | Pola opcjonalne są oznaczone jako „Optional”. |
| 4 | Uzupełnij wszystkie wymagane pola poprawnymi danymi | First name: Jan; Last name: Kowalski; Address: ul. Testowa 10; City: Wrocław; Zip/Postal Code: 50-001; Country: Poland | Wszystkie wymagane pola zawierają poprawne dane. |
| 5 | Pozostaw pola opcjonalne niewypełnione | Alias, Company, VAT number, Address Complement, Phone | Pola opcjonalne pozostają puste. |
| 6 | Zapisz zmiany | Kliknij przycisk „Save” | Adres zostaje zapisany pomyślnie mimo pozostawienia pól opcjonalnych pustych. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
