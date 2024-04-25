# Insolvenzvorhersagemodell

Dieses Projekt erstellt ein Insolvenzvorhersagemodell für Bankkunden. Das Modell basiert auf maschinellem Lernen und verwendet verschiedene Klassifikationsalgorithmen, um vorherzusagen, ob ein Kunde in naher Zukunft insolvent wird oder nicht.

## Datensatz

Der Datensatz, den wir verwenden, enthält verschiedene Merkmale von Bankkunden sowie Informationen darüber, ob sie insolvent wurden oder nicht. Die Merkmale umfassen Dinge wie Kreditwürdigkeit, Einkommen, Kreditkartenverhalten und mehr.

## Modelle

Wir haben mehrere Modelle trainiert, um die Vorhersagegenauigkeit zu maximieren:

- **Logistische Regression**: Ein linearer Klassifikationsalgorithmus, der die Wahrscheinlichkeit berechnet, dass ein Kunde insolvent wird.
- **Entscheidungsbaum**: Ein Baumstruktur-Algorithmus, der Entscheidungen anhand der Merkmale der Kunden trifft.
- **Random Forest**: Ein Ensemble-Algorithmus, der aus vielen Entscheidungsbäumen besteht und deren Ergebnisse kombiniert.

## Ergebnisse

Die Ergebnisse der Modelle sind wie folgt:

- **Logistische Regression**: Genauigkeit von 96.55%
- **Entscheidungsbaum**: Genauigkeit von 96.48%
- **Random Forest**: Genauigkeit von 97.73%


Eine detaillierte Analyse der Ergebnisse, einschließlich Klassifizierungsberichten und Confusion Matrices, finden Sie im Abschnitt "Ergebnisse" unserer [Jupyter Notebook](link_zu_notebook.ipynb).

## Verwendung

Sie können das Modell verwenden, um Vorhersagen für neue Kunden zu treffen, indem Sie einfach ihre relevanten Merkmale eingeben und das Modell die Wahrscheinlichkeit ihres Insolvenzrisikos berechnen lassen.

## Abhängigkeiten

Um das Modell zu verwenden, benötigen Sie Python und die folgenden Bibliotheken:

- pandas
- scikit-learn
- matplotlib
- seaborn

Sie können alle Abhängigkeiten mit `pip install -r requirements.txt` installieren.
