# 📍 Übung: CSS Positionierung

Dieses Projekt enthält Übungsaufgaben zu den verschiedenen Positionierungsarten in CSS. Ziel ist es, den Unterschied zwischen dem normalen Dokumentenfluss und der manuellen Platzierung von Elementen zu verstehen.

## 🛠️ Voraussetzungen

- Grundkenntnisse in HTML & CSS
- Ein Editor (empfohlen: VS Code)
- Ein Browser zum Testen der Ergebnisse

---

## 📝 Aufgabenstellung: Abschnitt 1 - Positionierung

### 1. Die Basis: `static` & `relative`

**Konzept:** Verstehe den Unterschied zwischen dem Standardzustand und dem Verschieben von Elementen ohne Lücken im Layout.

- **Aufgabe:** Erstelle drei farbige Boxen (`div` mit Klassen) untereinander.
- **Ziel:** Verschiebe die **zweite Box** mit `position: relative;` um `30px` nach unten und `30px` nach rechts.
- **Beobachtung:** Achte darauf, dass der ursprüngliche Platz der Box als "Platzhalter" erhalten bleibt.

### 2. Der Anker: `absolute` in `relative`

**Konzept:** Ein absolut positioniertes Element orientiert sich am nächsten positionierten Elternelement.

- **Aufgabe:** Erstelle einen großen Container (`.parent`) und darin ein kleineres Quadrat (`.child`).
- **Ziel:** Positioniere das kleine Quadrat genau in der **unten rechten Ecke** des großen Containers.
- **Hinweis:** Damit das Kind nicht am Browserrand landet, muss das Elternteil eine Positionierung (z.B. `relative`) haben.

### 3. Der Klassiker: `fixed` Navigation

**Konzept:** Fixierte Elemente bleiben unabhängig vom Scrollen immer an der gleichen Stelle im Viewport.

- **Aufgabe:** Erstelle eine schmale Leiste (`header`) am oberen Rand. Füge darunter sehr viel Text (`lorem1000`) ein, um Scrollen zu ermöglichen.
- **Ziel:** Sorge dafür, dass der Header beim Scrollen \*\*immer oben kleben bleibt
