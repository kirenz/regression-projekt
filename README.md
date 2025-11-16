# Regression-Projekt

Dieses Repository richtet sich an Einsteigerinnen und Einsteiger, die mit scikit-learn Regressionen bauen möchten. 

Die Notebooks erklären jeden Schritt – von der Daten-Exploration bis zur Bewertung der Modelle – in einfach nachvollziehbaren Abschnitten.

## Inhalte

- `regression_intro.ipynb`: zeigt eine einfache lineare Regression mit nur einem Merkmal. Ideal, um die grundlegenden Konzepte zu verstehen.
- `regression_intro_split.ipynb`: baut darauf auf und demonstriert Train-Test-Split sowie Cross-Validation, um die Generalisierungsfähigkeit zu prüfen.

## Voraussetzungen

- Python ≥ 3.11
- [uv](https://docs.astral.sh/uv/) (wird für das Dependency-Management genutzt)

## Installation & Start

1. Abhängigkeiten installieren:
   ```bash
   uv sync
   ```
2. Jupyter Lab (oder Notebook) im virtuellen Umfeld starten:
   ```bash
   uv run jupyter lab
   ```
3. Die gewünschten Notebooks im Browser öffnen und Schritt für Schritt durchlaufen.

> Tipp: Falls nur ein Notebook gestartet werden soll, funktioniert auch `uv run jupyter notebook regression_intro.ipynb`.

## Daten
Die Datei `data/data-ads.csv` enthält zwei Spalten:
- `ads`: Werbebudget in beliebigen Einheiten.
- `sales`: zugehörige Verkaufszahlen.

Der Datensatz ist klein und bewusst simpel gehalten, damit sich die gesamte Modellierung in wenigen Minuten nachvollziehen lässt.

## Arbeiten mit den Notebooks
1. Jede Sektion beschreibt kurz das Ziel (z. B. Daten verstehen, Modell trainieren, Kennzahlen interpretieren).
2. Nach jedem Codeblock gibt es Tabellen oder Grafiken, die sofort interpretiert werden sollten.
3. Experimentiere mit veränderten Parametern (z. B. `test_size` oder `random_state`), um den Einfluss auf die Ergebnisse zu sehen.

Viel Erfolg beim Lernen und Ausprobieren!
