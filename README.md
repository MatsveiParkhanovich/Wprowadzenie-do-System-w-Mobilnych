# Wprowadzenie do Systemów Mobilnych

Repozytorium zawiera rozwiązania laboratoriów z przedmiotu **Wprowadzenie do Systemów Mobilnych**.

## Zawartość repozytorium

- **lab_01/** – teoretyczne podstawy i algorytmy generowania zdarzeń (ruchu) oraz teoria kolejek.
- **lab_02/** – implementacja symulatora stacji bazowej z wykorzystaniem modelu kolejkowego M/M/S.
- **lab_03/** – koncepcja sieci komórkowej, propagacja fal radiowych oraz efekt Dopplera.
- **lab_04/** – tworzenie aplikacji mobilnych w środowisku Android Studio z wykorzystaniem języka Kotlin i XML. Implementacja aplikacji Code Manager oraz generatora liczb pseudolosowych z zakresem określanym przez użytkownika.
- **lab_05/** – rozwój aplikacji mobilnych w Android Studio. Obsługa czujników urządzenia, odczyt danych z akcelerometru, światłomierza i żyroskopu, wyświetlanie listy dostępnych sensorów oraz implementacja gry Ball Game sterowanej ruchem telefonu.

Laboratoria obejmują zagadnienia związane z generowaniem zmiennych losowych z rozkładu Poissona i normalnego (Gaussa), analizą systemów kolejkowych, symulacją obsługi zgłoszeń, oceną obciążenia systemu, architekturą sieci komórkowych, propagacją fal radiowych, wpływem ruchu odbiornika na częstotliwość sygnału oraz tworzeniem aplikacji mobilnych i obsługą interfejsu użytkownika.

## Technologie

- Python
- Kotlin
- XML
- Android Studio
- Google Colab
- Anaconda Navigator
- JupyterLab
- NumPy
- Matplotlib
- Pandas
- Gradle
- Markdown
- Android Sensor Framework

## Organizacja pracy

Każde laboratorium znajduje się w osobnym katalogu. Katalog zawiera kod źródłowy oraz plik `README.md` z opisem wykonanych zadań, zastosowanych rozwiązań i sposobem uruchomienia programu.

W przypadku laboratoriów o charakterze teoretyczno-obliczeniowym dokumentacja zawiera również zastosowane wzory, obliczenia i wnioski.

W przypadku laboratoriów programistycznych dokumentacja obejmuje opis funkcjonalności aplikacji, wykorzystane technologie oraz instrukcję uruchomienia.

## Środowisko pracy

Początkowo do realizacji laboratoriów wykorzystywano Google Colab. Ze względu na wyczerpanie dostępnych bezpłatnych limitów konieczne było przejście na lokalne środowisko Anaconda z wykorzystaniem JupyterLab.

W zależności od charakteru zadania wykorzystywano również Markdown do dokumentowania rozwiązań i prezentowania wyników obliczeń.

Do realizacji laboratoriów związanych z tworzeniem aplikacji mobilnych wykorzystano Android Studio, język Kotlin oraz XML. Aplikacje były uruchamiane i testowane za pomocą emulatora Android Studio.

W laboratorium 5 wykorzystano również wbudowane czujniki urządzenia Android, w szczególności akcelerometr, czujnik światła oraz żyroskop. Do realizacji zadania Ball Game wykorzystano grafikę `ball.png` oraz odczyty danych z akcelerometru do sterowania położeniem obiektu na ekranie.
