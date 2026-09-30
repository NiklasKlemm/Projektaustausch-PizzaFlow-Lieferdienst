# Projektaustausch: PizzaFlow Lieferdienst 🍕

Dieses Repository dokumentiert ein praktisches Software-Engineering-Lernprojekt im Rahmen des Unterrichts. 

Der Kern dieser Unterrichtseinheit bestand in einem strukturierten **Projektaustausch**: Ein Entwickler bzw. Team erstellte eine fundierte Konzeption (Aufgabenstellung, UML-Diagramme und Ablaufmodelle), die anschließend an eine andere Person übergeben wurde, um diese Vorgaben präzise in lauffähigen Code zu überführen.

---

## 🎯 Ziel & Lernerfolg

Die zentrale Herausforderung und der wesentliche Lernerfolg dieses Projekts lagen nicht nur im reinen Programmieren, sondern im **disziplinierten Umsetzen fremder Spezifikationen**:

- **Verständnis von Modellierung:** Interpretation komplexer UML-Diagramme (Klassendiagramm, Aktivitätsdiagramm, Zustandsdiagramm und Use-Case-Diagramm).
- **Spezifikationstreue:** Exakte Übertragung der vorgegebenen Klassen, Attribute, Methoden und Zustandswechsel in Python, ohne eigenmächtig von der Architektur abzuweichen.
- **Schnittstellen- und Anforderungsanalyse:** Kritisches Durcharbeiten einer Aufgabenstellung (`PizzaFlow`) und Abgleich zwischen Konzept und Code.
- **Praxisnahe Softwareentwicklung:** Simulation eines realen Entwicklungsszenarios, in dem Architekten/Kunden Anforderungen formulieren und Entwickler diese maßstabsgetreu realisieren.

---

## 📂 Repository-Struktur

Das Repository gliedert sich in die zwei Phasen des Austauschs: die erhaltenen Vorgaben und die daraus resultierende Umsetzung.

```text
Projektaustausch-Lieferdienst/
├── Erhaltenen Dokumente/          # Zur Verfügung gestellte Spezifikationen & Modelle
│   ├── Aufgabenstellung_PizzaFlow.pdf
│   ├── Klassendiagramme.png
│   ├── PizzaSystem-Aktivitäten.jpg
│   ├── PizzaSystem-Use Case.jpg
│   └── PizzaSystem-Zustands.jpg
│
└── Umgesetzter code/              # Implementierung basierend auf den Vorgaben
    ├── klassen.py                 # Klassenstruktur gemäß Klassendiagramm
    └── main.py                    # Programmablauf / Logiksteuerung
```

---

## 🛠️ Verwendete Technologien & Konzepte

- **Programmiersprache:** Python 3
- **Konzepte:** 
  - Objektorientierte Programmierung (OOP)
  - Zustandsverwaltung (State Pattern / Lifecycle der Bestellung)
  - Geschäftsprozessmodellierung & UML-Compliance

---

## 🚀 Ausführung

Um das Programm lokal auszuführen, navigiere in das Verzeichnis mit dem Quellcode:

```bash
cd "Umgesetzter code"
python main.py
```