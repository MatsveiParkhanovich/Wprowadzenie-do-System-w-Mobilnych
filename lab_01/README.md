# Laboratorium 1 – Generowanie rozkładów Poissona i normalnego

## Cel

Celem laboratorium jest implementacja generatorów liczb pseudolosowych o rozkładzie Poissona oraz rozkładzie normalnym (Gaussa), a także przedstawienie otrzymanych wyników za pomocą histogramów.

## Co zostało zrealizowane

- Zaimplementowano generator rozkładu Poissona z parametrem lambda.
- Zaimplementowano generator rozkładu normalnego z wykorzystaniem metody Boxa-Mullera.
- Wygenerowano histogramy obu rozkładów.
- Dodano możliwość ustawienia liczby generowanych wartości.
- Dodano parametry rozkładów: lambda, mu oraz sigma.
- Sprawdzono generowanie z ustalonym ziarnem (`seed`) i bez ustalonego ziarna.
- Wyświetlono średnie z próby oraz odchylenie standardowe dla wygenerowanych danych.

## Technologie

- Python
- Google Colab
- Matplotlib

## Uruchomienie

1. Otwórz plik `lab_01.ipynb` w Google Colab.
2. Ustaw parametry programu w pierwszej części kodu.
3. Ustaw `SEED` na liczbę całkowitą, aby uzyskać powtarzalne wyniki, lub na `None`, aby generować bez ustalonego ziarna.
4. Uruchom komórkę z programem.
5. Sprawdź wyświetlone statystyki oraz histogramy.

## Parametry programu

- `LAMBDA` – parametr rozkładu Poissona.
- `MU` – średnia rozkładu normalnego.
- `SIGMA` – odchylenie standardowe rozkładu normalnego.
- `N` – liczba generowanych wartości.
- `SEED` – ziarno generatora lub `None`.

## Weryfikacja

Poprawność działania sprawdzono na podstawie histogramów oraz porównania statystyk z wartościami teoretycznymi dla wybranych parametrów.

## Trudności / refleksja

Podczas laboratorium zapoznałem się ze środowiskiem Google Colab i nauczyłem się uruchamiać w nim kod w języku Python. Poznałem również podstawy generowania liczb pseudolosowych oraz wizualizacji wyników za pomocą histogramów.
