# SCLABS-217 – Wyświetlanie informacji o użytkowniku – TC pozytywny

## Informacje podstawowe
- **ID przypadku testowego:** SCLABS-217
- **Plan testów:** TP-02 – Konto użytkownika
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis
Sprawdzenie, czy w zakładce „Information” wyświetlają się aktualne dane użytkownika, prawidłowe ustawienia pól haseł i zgód oraz wymagane elementy nawigacyjne.

## Warunki wstępne
- Sklep internetowy jest dostępny.
- Użytkownik posiada zarejestrowane konto.
- Użytkownik jest zalogowany.
- Panel użytkownika jest otwarty.
- Dane użytkownika i jego ustawienia zgód są znane.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Otwórz zakładkę z informacjami o użytkowniku | Kliknij „Information” | Wyświetla się formularz informacji o użytkowniku. |
| 2 | Sprawdź pole „Social title” | Aktualny tytuł użytkownika | Pole wyświetla poprawny tytuł użytkownika. |
| 3 | Sprawdź pole „First name” | Aktualne imię użytkownika | Pole wyświetla poprawne imię użytkownika. |
| 4 | Sprawdź pole „Last name” | Aktualne nazwisko użytkownika | Pole wyświetla poprawne nazwisko użytkownika. |
| 5 | Sprawdź pole „Email” | Adres e-mail przypisany do konta | Pole wyświetla poprawny adres e-mail użytkownika. |
| 6 | Sprawdź pole „Password” | Nie wprowadzaj żadnej wartości | Pole jest puste i dostępna jest opcja „Show”. |
| 7 | Sprawdź pole „New password” | Nie wprowadzaj żadnej wartości | Pole jest puste, oznaczone jako opcjonalne i dostępna jest opcja „Show”. |
| 8 | Sprawdź pole „Birthdate” | Aktualna data urodzenia użytkownika | Pole wyświetla poprawną datę urodzenia w wymaganym formacie DD/MM/YYYY. |
| 9 | Sprawdź checkbox „Receive offers from our partners” | Aktualne ustawienie zgody | Checkbox odzwierciedla aktualne ustawienie zgody użytkownika. |
| 10 | Sprawdź checkbox „Customer data privacy” | Aktualne ustawienie zgody | Checkbox wyświetla zgodę na przetwarzanie danych osobowych. |
| 11 | Sprawdź checkbox „Newsletter” | Aktualne ustawienie zgody | Checkbox odzwierciedla aktualne ustawienie zgody użytkownika. |
| 12 | Sprawdź checkbox „I agree to the terms and conditions and the privacy policy” | Aktualne ustawienie zgody | Checkbox odzwierciedla aktualne ustawienie zgody użytkownika. |
| 13 | Sprawdź ścieżkę nawigacyjną | „Home/Nazwa zakładki” | Wyświetla się ścieżka w formacie „Home/Nazwa zakładki”. |

## Wynik wykonania
Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
