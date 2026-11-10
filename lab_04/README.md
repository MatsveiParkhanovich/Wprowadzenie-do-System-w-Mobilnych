# lab_04 –  Android Studio cz.1

## Co zostało zrealizowane

W ramach laboratorium zrealizowałem dwie części pracy, tworząc aplikacje mobilne w środowisku Android Studio, wykorzystując język Kotlin oraz XML.

### Część 1 – Code Manager

W pierwszej części stworzyłem aplikację mobilną Code Manager, która umożliwia użytkownikowi wpisanie swojego imienia, zwiększanie licznika napisanych linii kodu za pomocą przycisku +1 oraz wyzerowanie go przyciskiem Clean.

Interfejs wyświetla aktualną liczbę linii kodu, komunikat motywacyjny oraz pasek postępu.

Do obsługi licznika utworzyłem klasę `CodeManager`, która przechowuje imię użytkownika i wartość licznika oraz udostępnia metody zwiększania i zerowania jego wartości.

### Część 2 – Pierwsza aplikacja mobilna

W drugiej części stworzyłem aplikację umożliwiającą generowanie liczb pseudolosowych w zakresie określonym przez użytkownika.

Interfejs zawiera pole edycyjne (`EditText`), w którym można wprowadzić maksymalną wartość losowania, oraz przycisk `Generate`, który uruchamia losowanie i wyświetla jego wynik.

Do obsługi interfejsu wykorzystałem metodę `findViewById()`, obsługę zdarzeń `setOnClickListener()` oraz `addTextChangedListener()` do monitorowania zmian w polu edycyjnym.

Generator liczb został zaimplementowany z wykorzystaniem biblioteki `kotlin.random.Random`. Dodano również sprawdzanie poprawności wprowadzonych danych.

Obie części obejmują funkcjonalności zrealizowane zgodnie z odpowiednimi instrukcjami laboratoryjnymi.

## Uruchomienie

Pobierz projekt z GitHub za pomocą opcji **Code → Download ZIP**, rozpakuj archiwum, a następnie otwórz odpowiedni projekt w Android Studio.

Po synchronizacji Gradle uruchom aplikację na emulatorze Android lub urządzeniu mobilnym, klikając **Run**.

W przypadku aplikacji Code Manager można wpisać imię, zwiększać licznik przyciskiem +1 i zerować go za pomocą Clean.

W przypadku drugiej aplikacji należy wpisać maksymalną wartość w polu tekstowym i kliknąć przycisk Generate, aby otrzymać losową liczbę z wybranego zakresu.

## Trudności / refleksja

Podczas pracy zapoznałem się z tworzeniem interfejsów aplikacji mobilnych za pomocą XML oraz łączeniem ich elementów z logiką aplikacji napisaną w Kotlinie.

Przećwiczyłem tworzenie własnych klas, obsługę zdarzeń przycisków, pobieranie danych z pól edycyjnych, aktualizowanie elementów interfejsu oraz generowanie liczb pseudolosowych.

Ważnym elementem było prawidłowe powiązanie elementów interfejsu z logiką aplikacji oraz sprawdzenie poprawności działania poszczególnych funkcjonalności.

Obie aplikacje zostały uruchomione i przetestowane w emulatorze Android Studio.

**Status:** zrealizowano obie części laboratorium. Obie aplikacje posiadają zaimplementowane i przetestowane podstawowe funkcjonalności.
