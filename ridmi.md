# Projekt: Kalkulator C++

Prosty kalkulator wykonany w ramach projektu zaliczeniowego, realizujący podstawowe operacje matematyczne. Projekt został przygotowany zgodnie z wymaganiami, z wykorzystaniem systemu kontroli wersji Git oraz metodyki Feature Branch.

## Kroki realizacji (Workflow)

Projekt został podzielony na trzy główne etapy, z których każdy był realizowany na osobnej gałęzi (branch) i dokumentowany w Trello:

### 1. Dodawanie (Suma)
- **Opis:** Implementacja podstawowej funkcji sumowania dwóch liczb.
- **Git:** Stworzono gałąź `feature-addition`, zaimplementowano kod w `main.cpp`, a następnie wykonano merge do głównej gałęzi.
- **Trello:** Zadanie "Implementacja dodawania" przeniesione do kolumny "Done".

### 2. Odejmowanie (Różnica)
- **Opis:** Rozszerzenie kalkulatora o możliwość odejmowania.
- **Git:** Praca na gałęzi `feature-subtraction`. Dodano obsługę operatora `-`.
- **Status:** Połączono z gałęzią główną po pomyślnych testach lokalnych.

### 3. Mnożenie (Iloczyn)
- **Opis:** Dodanie funkcjonalności mnożenia liczb zmiennoprzecinkowych.
- **Git:** Stworzono gałąź `feature-multiplication`. Zaktualizowano interfejs użytkownika o nową opcję wyboru.
- **Dokumentacja:** Zaktualizowano plik README o instrukcję obsługi mnożenia.

## Funkcje programu
- Prosty interfejs tekstowy w konsoli.
- Obsługa operacji: `+`, `-`, `*`.
- Walidacja danych wejściowych.

## Technologie i Narzędzia
- **Język programowania:** C++
- **IDE:** Visual Studio / CLion
- **Kontrola wersji:** Git (GitHub)
- **Zarządzanie zadaniami:** Trello
- **Format dokumentacji:** Markdown