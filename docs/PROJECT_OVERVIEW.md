# Projektübersicht: QuantzAI

QuantzAI ist ein privat entwickeltes Forschungs- und Softwareprojekt von Yones Alizai, Informatiker & Softwareentwickler. Das Projekt beschäftigt sich mit der datenbasierten Analyse von Forex- und Rohstoffmärkten und verbindet historische Marktdaten, Datenverarbeitung, Feature Engineering, Machine Learning, Backtesting, Risikomanagement, Paper-Trading, eine grafische Desktop-Oberfläche, Audit-Logging und automatisierte Tests.

Diese Dokumentation beschreibt den öffentlichen Rahmen des Projekts. Sie enthält keine interne Strategielogik, keine Modelle, keine Parameter, keine Zugangsdaten und keine vollständige technische Implementierung.

## Motivation

Finanzmärkte erzeugen große Mengen zeitabhängiger Daten. QuantzAI untersucht, wie solche Daten strukturiert aufbereitet, analysiert und in Machine-Learning-Workflows bewertet werden können. Im Mittelpunkt steht nicht ein Gewinnversprechen, sondern die technische Umsetzung eines nachvollziehbaren Forschungs- und Entwicklungsprozesses.

## Allgemeine Problemstellung

Die datenbasierte Marktanalyse erfordert mehrere zusammenhängende Komponenten. Historische Daten müssen konsistent verarbeitet, Merkmale müssen reproduzierbar erzeugt, Modelle müssen nachvollziehbar validiert und Ergebnisse müssen unter realistischen Annahmen bewertet werden.

Besonders wichtig ist dabei die Trennung zwischen Forschung, Auswertung und simulierter Ausführung. QuantzAI verbindet diese Bereiche in einem privaten Softwareprojekt, ohne die interne Implementierung öffentlich offenzulegen.

## Zeitbasierte Validierung

Bei Marktdaten ist die zeitliche Reihenfolge zentral. Eine zufällige Vermischung von Trainings- und Bewertungsdaten kann zu unrealistischen Ergebnissen führen, weil spätere Informationen unbeabsichtigt in frühere Auswertungen einfließen können.

QuantzAI berücksichtigt deshalb zeitbasierte Validierung als allgemeinen methodischen Grundsatz. Ziel ist eine Bewertung, die die zeitliche Struktur der Daten respektiert und Modellverhalten nachvollziehbarer macht.

## Bewertung unter Handelskosten

Eine technische Bewertung von Signalen oder Modellentscheidungen ist ohne Kostenannahmen nur begrenzt aussagekräftig. Handelskosten können Ergebnisse deutlich beeinflussen und müssen deshalb in einer realistischeren Bewertung berücksichtigt werden.

Die öffentliche Darstellung nennt keine konkreten Spread-, Slippage- oder Provisionswerte. Sie beschreibt lediglich, dass Kostenaspekte in der Bewertung eine Rolle spielen.

## Risikomanagement und Paper-Trading

Risikomanagement dient dazu, Modellentscheidungen und Ausführungsszenarien kontrollierter zu betrachten. Paper-Trading ermöglicht simulierte Abläufe ohne produktiven Kapitaleinsatz und kann helfen, technische Prozesse, Logging und Monitoring nachvollziehbar zu prüfen.

QuantzAI wird nicht als fertiges profitables Handelssystem dargestellt. Der Fokus liegt auf Forschung, Softwareentwicklung und kontrollierter Simulation.

## Desktop-Oberfläche

Die grafische Desktop-Oberfläche macht zentrale Arbeitsbereiche des Projekts bedienbar und sichtbar. Dazu gehören Monitoring, Auswertung, Paper-Trading-bezogene Ansichten und Audit-Logging. Die Oberfläche unterstützt damit die praktische Arbeit am Projekt, ohne interne Logik oder vertrauliche Daten öffentlich preiszugeben.

## Verwendete Technologien

| Bereich | Technologien |
| --- | --- |
| Programmiersprache | Python 3.11 |
| Machine Learning | LightGBM, scikit-learn |
| Datenverarbeitung | pandas, PyArrow |
| Desktop-Oberfläche | PySide6 |
| Trading-Anbindung | MetaTrader 5 |
| Speicherung | SQLite |
| Logging und Tests | Loguru, pytest |

## Hinweis

QuantzAI ist ein privates Forschungs- und Entwicklungsprojekt. Die öffentliche Darstellung ist keine Finanzberatung und enthält kein Gewinnversprechen.
