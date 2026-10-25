# SCLABS-184 – Działanie zakładki do rejestracji nowego użytkownika

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-184
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy kliknięcie zakładki „No account? Create one here” w formularzu logowania otwiera formularz rejestracji nowego użytkownika.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Użytkownik nie posiada konta założonego na adres e-mail, którego użyje do rejestracji.
- Strona sklepu MyStore jest dostępna.
- Zakładka „Sign in” jest widoczna i działa poprawnie.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Otwórz przeglądarkę internetową. | — | Przeglądarka poprawnie się otwiera. |
| 2 | Przejdź na stronę główną sklepu internetowego MyStore. | https://dev-mystore-testlab.coderslab.pl/index.php | Strona internetowa poprawnie się otwiera. |
| 3 | Otwórz formularz logowania. | Kliknij „Sign in”. | Formularz logowania poprawnie się otwiera. |
| 4 | W formularzu logowania kliknij zakładkę do rejestracji nowych użytkowników. | Kliknij „No account? Create one here”. | Formularz rejestracji nowego użytkownika poprawnie się otwiera. |

## Rezultat testu

Do uzupełnienia po wykonaniu testu.
