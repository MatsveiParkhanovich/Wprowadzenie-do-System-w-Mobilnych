# Lab 04 – Code Manager (część 1)

## Co zostało zrealizowane

W pierwszej części laboratorium stworzyłem aplikację mobilną Code Manager w środowisku Android Studio, wykorzystując język Kotlin oraz XML.

Aplikacja pozwala użytkownikowi wpisać swoje imię, zwiększać licznik napisanych linii kodu za pomocą przycisku +1 oraz wyzerować go przyciskiem Clean. Dodatkowo interfejs wyświetla aktualną liczbę linii kodu, komunikat motywacyjny i pasek postępu.

Do obsługi licznika utworzyłem klasę `CodeManager`, która przechowuje imię użytkownika i wartość licznika oraz udostępnia metody zwiększania i zerowania jego wartości.

Zrealizowana część obejmuje podstawową funkcjonalność aplikacji. Pozostałe zadania z instrukcji laboratoryjnej nie zostały jeszcze wykonane.

## Uruchomienie

1. Otwórz projekt `lab_04` w Android Studio.
2. Poczekaj na zakończenie synchronizacji Gradle.
3. Uruchom emulator Android lub podłącz urządzenie mobilne.
4. Wybierz urządzenie na górnym pasku Android Studio.
5. Kliknij przycisk **Run** (zielony trójkąt).
6. Po uruchomieniu aplikacji wpisz imię i przetestuj przyciski +1 oraz Clean.

## Trudności / refleksja

Podczas pracy zapoznałem się z tworzeniem interfejsu aplikacji za pomocą XML oraz połączeniem jego elementów z kodem Kotlin. Przećwiczyłem również tworzenie własnej klasy i obsługę zdarzeń przycisków.

Jedną z ważniejszych rzeczy było poprawne powiązanie elementów interfejsu z logiką aplikacji oraz sprawdzenie, czy licznik i pasek postępu aktualizują się zgodnie z oczekiwaniami.

**Status:** zrealizowano pierwszą część laboratorium. Dalsza część zostanie wykonana osobno.
