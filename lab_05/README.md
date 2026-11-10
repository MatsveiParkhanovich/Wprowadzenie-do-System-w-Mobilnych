
# Lab 05 – Obsługa czujników urządzenia Android

## Co zostało zrealizowane

W ramach laboratorium przygotowano aplikację Android prezentującą działanie czujników urządzenia.

Aplikacja zawiera następujące funkcje:

- **Accelerometer** – odczyt danych z akcelerometru w osiach X, Y i Z. Wartości zmieniają się w zależności od położenia urządzenia.
- **Lightmeter** – pomiar natężenia światła i wyświetlanie aktualnej wartości w luksach (Lux).
- **Sensors List** – wyświetlanie listy czujników dostępnych w urządzeniu wraz z informacjami o ich typie, producencie, poborze mocy, rozdzielczości i maksymalnym zakresie.
- **Additional Sensor** – odczyt danych z żyroskopu (Gyroscope), prezentujący prędkość kątową w osiach X, Y i Z.
- **Ball Game** – gra wykorzystująca akcelerometr, w której położenie piłki zmienia się w zależności od nachylenia urządzenia. Do wyświetlenia piłki wykorzystano plik graficzny `ball.png`.

Każda funkcja została umieszczona w osobnej aktywności. Przechodzenie między poszczególnymi ekranami odbywa się za pomocą menu głównego aplikacji.

## Uruchomienie

1. Otwórz projekt `lab_05` w programie Android Studio.
2. Poczekaj na zakończenie synchronizacji Gradle.
3. Uruchom emulator Android lub podłącz urządzenie z systemem Android.
4. Kliknij przycisk **Run**.
5. Wybierz odpowiednią funkcję z menu głównego aplikacji.

Do poprawnego działania poszczególnych funkcji wymagane jest wsparcie odpowiednich czujników przez urządzenie lub emulator.

## Trudności / refleksja

Podczas realizacji laboratorium pojawiły się trudności związane z obsługą czujników oraz aktualizacją danych na ekranie.

W przypadku gry Ball Game konieczne było poprawienie kierunku ruchu piłki, dostosowanie jej pozycji do wskazań akcelerometru oraz ograniczenie ruchu do granic ekranu.

Realizacja laboratorium pozwoliła zapoznać się z obsługą czujników Android, wykorzystaniem `SensorManager`, obsługą zdarzeń oraz tworzeniem własnego widoku graficznego.

