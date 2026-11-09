# lab_01 – Teoretyczne podstawy i algorytmy generowania zdarzeń (ruchu) oraz teoria kolejek.

## Co zostało zrealizowane

W ramach laboratorium przygotowałem programy w języku Python, które pozwalają generować liczby losowe oraz analizować różne systemy obsługi i kolejkowe.

W pierwszej części laboratorium zaimplementowałem dwa generatory liczb losowych. Pierwszy wykorzystuje rozkład Poissona, a drugi rozkład normalny (Gaussa). Program umożliwia ustawienie liczby generowanych wartości oraz parametrów obu rozkładów. Wyniki przedstawiane są w postaci histogramów. Dodatkowo program oblicza średnią i odchylenie standardowe wygenerowanych wartości.

W drugiej części laboratorium przeprowadziłem analizę różnych systemów kolejkowych:

**Zadanie 1 – Sieć komórkowa**

Przeanalizowałem działanie sieci komórkowej, obliczając intensywność ruchu oraz minimalną liczbę kanałów potrzebnych do utrzymania równowagi systemu.

**Zadanie 2 – System pięciu serwerów**

Przeanalizowałem system składający się z pięciu serwerów. Obliczyłem prawdopodobieństwa związane z kolejką i oczekiwaniem, średnią liczbę oczekujących klientów oraz średni czas oczekiwania na obsługę.

**Zadanie 3 – Przychodnia stomatologiczna**

Przeanalizowałem kolejkę pacjentów w przychodni stomatologicznej. Porównałem działanie systemu z trzema i dwoma gabinetami, sprawdzając prawdopodobieństwo obsługi bez oczekiwania oraz średni czas oczekiwania.

**Zadanie 4 – Obsługa studentów w barze**

Przeanalizowałem dane dotyczące studentów korzystających z dwóch stanowisk obsługi w barze. Na podstawie pomiarów oszacowałem intensywność przybywania studentów, intensywność obsługi oraz obciążenie systemu.

## Uruchomienie

Programy zostały przygotowane w języku Python i wykonane w środowisku Google Colab. Aby uruchomić obliczenia, należy otworzyć odpowiednie pliki z kodem w Google Colab i wykonać komórki programu.

W przypadku generatorów liczb losowych parametry generowania można zmienić na początku programu. Wyniki analizy systemów kolejkowych są obliczane automatycznie na podstawie wprowadzonych danych.

## Trudności / refleksja

Podczas laboratorium nauczyłem się generować liczby losowe z wykorzystaniem rozkładu Poissona i normalnego oraz przedstawiać wyniki na histogramach. Poznałem również podstawowe zasady analizy systemów kolejkowych i nauczyłem się obliczać ich najważniejsze parametry.

Lepiej zrozumiałem, jak intensywność napływu klientów, szybkość obsługi oraz liczba stanowisk wpływają na obciążenie systemu, stabilność kolejki i czas oczekiwania. Zdobyłem również praktyczne doświadczenie w wykorzystaniu języka Python do wykonywania obliczeń i analizy danych.
