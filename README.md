# SMM_termovision
Repozytorium dotyczące projektu z SMM  - Analiza obrazu i termowizja we wspomaganiu monitorowania pacjentów po chemioterapii

# Monitorowanie pacjentów po chemioterapii (RGB + termowizja)

Projekt systemu wspomagającego bezkontaktowe monitorowanie pacjentów onkologicznych po chemioterapii. Łączy analizę obrazu z kamery wizyjnej oraz pomiary termowizyjne w celu oceny temperatury, aktywności ruchowej i parametrów z aparatury medycznej. Repozytorium zawiera kod demonstratora, narzędzia do oceny symulacyjnej oraz dokumentację.

## Struktura folderów

* `configs/` – pliki konfiguracyjne (progi alarmowe, parametry kalibracji).
* `data/` – struktura katalogów na nagrania RGB, termowizyjne, dane referencyjne oraz scenariusze symulacyjne *(surowe nagrania nie są przechowywane w repozytorium)*.
* `docs/` – dokumentacja projektu, opis PDF, schematy i raporty.
* `notebooks/` – notatniki do analizy danych, kalibracji i generowania wykresów.
* `src/` – główny kod źródłowy aplikacji (przetwarzanie obrazu, termowizja, analiza zdarzeń, ewaluacja).
* `demo/` – kod demonstratora wybranych funkcji systemu.
* `tests/` – testy jednostkowe i integracyjne.

## Pobieranie projektu

1. Sklonuj repozytorium w terminalu:
   ```bash
   git clone [https://github.com/TWOJA_NAZWA/NAZWA_REPO.git](https://github.com/TWOJA_NAZWA/NAZWA_REPO.git)
   cd NAZWA_REPO
