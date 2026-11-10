# Wprowadzenie do Systemów Mobilnych

Repozytorium zawiera rozwiązania laboratoriów z przedmiotu **Wprowadzenie do Systemów Mobilnych**.

## Zawartość repozytorium

- **lab_01/** – teoretyczne podstawy i algorytmy generowania zdarzeń (ruchu) oraz teoria kolejek.
- **lab_02/** – implementacja symulatora stacji bazowej z wykorzystaniem modelu kolejkowego M/M/S.
- **lab_03/** – koncepcja sieci komórkowej, propagacja fal radiowych oraz efekt Dopplera.

Laboratoria obejmują zagadnienia związane z generowaniem zmiennych losowych z rozkładu Poissona i normalnego (Gaussa), analizą systemów kolejkowych, symulacją obsługi zgłoszeń, oceną obciążenia systemu, architekturą sieci komórkowych, ponownym wykorzystaniem częstotliwości, propagacją fal radiowych oraz wpływem ruchu odbiornika na częstotliwość sygnału.

### Zakres Laboratorium 3

Laboratorium 3 zostało opracowane na podstawie dwóch instrukcji laboratoryjnych: **WdSM_lab05** oraz **WdSM_lab06**. Składa się z dwóch części obejmujących łącznie 22 zadania.

- **Część I – Koncepcja komórki:** architektura sieci komórkowej, kształt i rozmiar komórek, klastry, odległość ponownego wykorzystania częstotliwości, pojemność sieci, obciążenie, handoff, interferencje oraz sektorowanie komórek.
- **Część II – Propagacja fal i efekt Dopplera:** model wolnej przestrzeni, wzór Friisa, moc odbieranego sygnału, straty propagacyjne, wielodrogowość, szybkie i wolne zanikanie sygnału oraz przesunięcie częstotliwości Dopplera.

## Technologie

- Python
- Google Colab
- Anaconda Navigator
- JupyterLab
- NumPy
- Matplotlib
- Pandas
- Markdown

## Organizacja pracy

Każde laboratorium znajduje się w osobnym katalogu. Katalog zawiera kod źródłowy oraz plik `README.md` z opisem wykonanych zadań, zastosowanych rozwiązań i sposobem uruchomienia programu.

W przypadku laboratoriów o charakterze teoretyczno-obliczeniowym dokumentacja zawiera również zastosowane wzory, obliczenia i wnioski.

## Środowisko pracy

Początkowo do realizacji laboratoriów wykorzystywano Google Colab. Ze względu na wyczerpanie dostępnych bezpłatnych limitów konieczne było przejście na lokalne środowisko Anaconda z wykorzystaniem JupyterLab.

W zależności od charakteru zadania wykorzystywano również Markdown do dokumentowania rozwiązań i prezentowania wyników obliczeń.
