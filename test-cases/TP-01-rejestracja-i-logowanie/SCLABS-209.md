# SCLABS-209 – Podgląd i ukrywanie hasła w formularzu rejestracji – TC pozytywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-209
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy kliknięcie przycisku „SHOW” umożliwia wyświetlenie hasła wpisanego w formularzu rejestracji, a kliknięcie przycisku „HIDE” pozwala ponownie je ukryć.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz rejestracji nowego użytkownika jest otwarty.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Sprawdź widoczność pola „Password” i przycisku „SHOW” | Odszukaj pole „Password” i przycisk „SHOW” w formularzu rejestracji | Pole „Password” i przycisk „SHOW” są widoczne |
| 2 | Wprowadź hasło | Wpisz w polu „Password” hasło `Test123` | Hasło zostaje wpisane i jest domyślnie ukryte |
| 3 | Sprawdź możliwość podglądu hasła | Kliknij przycisk „SHOW” | Hasło jest widoczne w postaci wpisanych znaków |
| 4 | Sprawdź możliwość ponownego ukrycia hasła | Kliknij przycisk „HIDE” | Hasło zostaje ponownie ukryte |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
