# Regression-Projekt

Dieses Repository richtet sich an Einsteigerinnen und Einsteiger, die mit scikit-learn Regressionen bauen möchten. 

Die Notebooks erklären jeden Schritt – von der Daten-Exploration bis zur Bewertung der Modelle – in einfach nachvollziehbaren Abschnitten.

## Inhalte

- `regression_intro.ipynb`: zeigt eine einfache lineare Regression mit nur einem Merkmal. Ideal, um die grundlegenden Konzepte zu verstehen.
- `regression_intro_split.ipynb`: baut darauf auf und demonstriert Train-Test-Split sowie Cross-Validation, um die Generalisierungsfähigkeit zu prüfen.

## Voraussetzungen

- Python ≥ 3.11
- [uv](https://docs.astral.sh/uv/) (wird für das Dependency-Management genutzt)
- VS Code Extension: Python, Jupyter

## Installation & Start

1. Repository klonen:

```bash
git clone https://github.com/kirenz/regression-projekt
```

2. In das Verzeichnis wechseln:

```bash
cd regression-projekt
```

3. Abhängigkeiten installieren:

```bash
uv sync
```

4. Die gewünschten Notebooks in VS Code öffnen und Schritt für Schritt durchlaufen.


## Daten

Die Dateien `data/data-ads.csv` und `data/data-ads-2.csv` enthalten zwei Spalten:

- `ads`: Werbebudget in beliebigen Einheiten.
- `sales`: zugehörige Verkaufszahlen.

Der Datensatz `data/data-ads.csv` ist klein und bewusst simpel gehalten, damit sich die gesamte Modellierung in wenigen Minuten nachvollziehen lässt.

`data/data-ads-2.csv` enthält 100 Beobachtungen mit einem realistischeren Werbebudget-Sales-Verhältnis und eignet sich somit für umfangreichere Experimente.

## Arbeiten mit den Notebooks

1. Jede Sektion beschreibt kurz das Ziel (z. B. Daten verstehen, Modell trainieren, Kennzahlen interpretieren).
2. Nach jedem Codeblock gibt es Tabellen oder Grafiken, die  interpretiert werden sollten.
3. Experimentiere mit veränderten Parametern (z. B. `test_size` oder `random_state`), um den Einfluss auf die Ergebnisse zu sehen.

