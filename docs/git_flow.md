# Git-Workflow und Branching-Strategie
## Unser Git-Flow (Feature Branch Workflow)

Wir verwenden einen schlanken Ansatz, bei dem Features direkt in die Hauptlinie integriert werden.

**Der Ablauf:**

1.  **Feature-Branches:**
    Die Arbeit erfolgt in Feature-Branches, die direkt vom `main`-Branch abgezweigt werden. In diesen Branches werden spezifische Features entwickelt oder Bugs behoben.

2.  **Pull Requests & Integration:**
    Nach Abschluss der Entwicklung wird ein Pull Request erstellt, um die Änderungen in den `main`-Branch zu integrieren.
    * *Hinweis:* Wir verzichten auf einen intermediären `develop`-Branch; der `main`-Branch ist stets die Quelle der Wahrheit.

3.  **Qualitätssicherung:**
    Vor der Integration in den `main`-Branch finden Reviews statt:
    * Nutzung von Pull Requests, um Änderungen zu reviewen und sicher zu integrieren.
    * Durchführung von Code-Reviews zur Sicherstellung der Qualität und zur Erkennung von Verbesserungsmöglichkeiten.

## Kompetenzen und Standards

Um einen stabilen Code zu gewährleisten, fokussieren wir uns auf folgende Punkte:

* **Branch-Management:** Korrekte Erstellung und Verwaltung von Branches für die Entwicklung neuer Features.
* **Review-Kultur:** Konsequente Nutzung von Pull Requests für Reviews.
* **Coding-Standards:** Sicherstellen, dass alle Integrationen strikt gemäss den definierten Coding-Standards des Projekts erfolgen.
* 