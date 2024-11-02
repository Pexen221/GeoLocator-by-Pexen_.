# GeoLocator By Pexen ![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![Version](https://img.shields.io/badge/version-1.0.0-blue)

GeoLocator By Pexen to narzędzie do lokalizacji geograficznej, które pozwala użytkownikom na precyzyjne identyfikowanie i analizowanie lokalizacji na podstawie różnych danych wejściowych. Aplikacja wykorzystuje zaawansowane algorytmy geolokalizacji, aby dostarczać dokładne informacje o położeniu w czasie rzeczywistym.

## Spis treści
- [Wymagania](#wymagania)
- [Instalacja](#instalacja)
- [Użycie](#użycie)
- [Przykłady](#przykłady)
- [Licencja](#licencja)

## Wymagania
Do poprawnego działania GeoLocator By Pexen potrzebne są:
- Python 3.8 lub nowszy
- Biblioteka `requests` do komunikacji z API
- `geopy` - do konwersji danych geograficznych

## Instalacja
1. Sklonuj repozytorium:
    ```bash
    git clone https://github.com/twoje_konto/GeoLocator-By-Pexen.git
    ```
2. Przejdź do katalogu projektu:
    ```bash
    cd GeoLocator-By-Pexen
    ```
3. Zainstaluj zależności:
    ```bash
    pip install -r requirements.txt
    ```

## Użycie
Aby uruchomić aplikację, użyj poniższego polecenia:

```bash
python geolocator.py --location "Warszawa, Polska"

