# SCLABS-210 – Podgląd i ukrywanie hasła w formularzu logowania – TC pozytywny

## Informacje podstawowe

- **ID przypadku testowego:** SCLABS-210
- **Plan testów:** TP-01 – Rejestracja i logowanie
- **Typ:** Test Case
- **Priorytet:** Medium
- **Status:** Otwarty

## Opis

Sprawdzenie, czy kliknięcie przycisku „SHOW” umożliwia wyświetlenie hasła wpisanego w formularzu logowania, a kliknięcie przycisku „HIDE” pozwala ponownie je ukryć.

## Warunki wstępne

- Użytkownik nie jest zalogowany w sklepie.
- Strona sklepu My Store jest dostępna.
- Formularz logowania jest otwarty.

## Kroki testowe

| Krok | Akcja | Dane wejściowe | Oczekiwany rezultat |
|---|---|---|---|
| 1 | Sprawdź widoczność pola „Password” i przycisku „SHOW” | Odszukaj pole „Password” i przycisk „SHOW” w formularzu logowania | Pole „Password” i przycisk „SHOW” są widoczne |
| 2 | Wprowadź hasło | Wpisz w polu „Password” hasło `Test123` | Hasło zostaje wpisane i jest domyślnie ukryte |
| 3 | Sprawdź możliwość podglądu hasła | Kliknij przycisk „SHOW” | Hasło jest widoczne w postaci wpisanych znaków |
| 4 | Sprawdź możliwość ponownego ukrycia hasła | Kliknij ponownie przycisk „SHOW”, jeśli nadal pełni funkcję przełącznika | Hasło zostaje ponownie ukryte |

## Wynik wykonania

Test nie został jeszcze wykonany. Wszystkie kroki mają status „To do” w Jira.
