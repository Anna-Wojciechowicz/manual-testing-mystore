# SCLABS-228 – Dodanie nowego adresu z poprawnymi danymi – TC pozytywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-228
- **Plan testów:** TP-03 – Zarządzanie adresami dostawy
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie możliwości dodania nowego adresu dostawy przez zalogowanego użytkownika.

## Warunki wstępne
- Użytkownik posiada konto w sklepie.
- Użytkownik jest zalogowany.
- Użytkownik znajduje się w sekcji „Your account”.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Przejdź do zakładki „Addresses” w panelu użytkownika | — | Wyświetla się poprawnie strona z adresami użytkownika. |
| 2 | Kliknij „Create new address” | — | Wyświetla się poprawnie formularz dodawania nowego adresu. |
| 3 | Sprawdź automatyczne uzupełnienie pól „First name”, „Last name” i „Country” | — | Pola są automatycznie uzupełnione danymi użytkownika. |
| 4 | Uzupełnij pole „Address” | `ul. Testowa 10` | Pole przyjmuje wpisaną wartość. |
| 5 | Uzupełnij pole „Address” | `ul. Testowa 20` | Pole przyjmuje wpisaną wartość. |
| 6 | Uzupełnij pole „City” | `Wrocław` | Pole przyjmuje wpisaną wartość. |
| 7 | Uzupełnij pole „Zip/Postal Code” | `50-001` | Pole przyjmuje wpisaną wartość. |
| 8 | Uzupełnij pole „Phone” | `123456789` | Pole przyjmuje wpisaną wartość. |
| 9 | Pozostaw pola opcjonalne niewypełnione | „Company”, „VAT number”, „Address Complement” | Pola opcjonalne mogą pozostać puste. |
| 10 | Zapisz zmiany | Kliknij przycisk „Save” | Adres zostaje zapisany i wyświetla się na liście adresów użytkownika. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
