# lab_02 – Symulator stacji bazowej

## Co zostało zrealizowane

W ramach laboratorium przygotowałem symulator stacji bazowej, który przedstawia sposób obsługi zgłoszeń w systemie z ograniczoną liczbą kanałów.

Do generowania momentów przybycia zgłoszeń wykorzystałem rozkład Poissona, natomiast czas trwania połączeń jest generowany na podstawie rozkładu Gaussa.

Program pozwala zmieniać parametry symulacji, obserwować wykorzystanie kanałów oraz analizować długość kolejki i czas oczekiwania. Wyniki są przedstawiane na wykresach i zapisywane w pliku CSV.

## Uruchomienie

Do uruchomienia projektu potrzebne są:

- Python 3
- Anaconda Distribution
- JupyterLab
- Biblioteki: NumPy, Pandas, Matplotlib oraz IPython

Sposób uruchomienia:

1. Uruchomić JupyterLab.
2. Otworzyć plik `zad_02.ipynb`.
3. Uruchomić komórki notebooka kolejno, od początku do końca.
4. Po zakończeniu symulacji wyniki zostaną zapisane w pliku `wyniki_symulacji.csv`.

## Trudności / refleksja

Podczas realizacji projektu największym wyzwaniem było prawidłowe odwzorowanie procesu obsługi zgłoszeń oraz uwzględnienie ograniczonej liczby dostępnych kanałów.

W trakcie pracy musiałem również zmienić środowisko programistyczne. Początkowo korzystałem z Google Colab, jednak po wykorzystaniu dostępnych bezpłatnych jednostek obliczeniowych zdecydowałem się przenieść projekt do lokalnego środowiska Anaconda i JupyterLab. Wymagało to skonfigurowania środowiska oraz ponownego uruchomienia i sprawdzenia kodu.

Praca nad symulatorem pozwoliła mi lepiej zrozumieć zastosowanie rozkładów prawdopodobieństwa w modelowaniu systemów oraz analizę wyników za pomocą wykresów.
