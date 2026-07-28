
# Git Cheatsheet

# Repository klonen

```bash
git clone https://github.com/<USERNAME>/<REPOSITORY>.git
```

Beispiel:

```bash
git clone https://github.com/David08150815/nomad-guide.git
```

**Erklärung:**

- Erstellt eine lokale Kopie eines GitHub-Repositories.
- Die Verbindung zum Remote `origin` wird automatisch eingerichtet.
- Dies ist normalerweise der erste Schritt, wenn man an einem bestehenden Projekt arbeitet.

---

# Aktuellen Status prüfen

```bash
git status
```

Zeigt:

- den aktuellen Branch
- geänderte Dateien
- neue Dateien
- Dateien in der Staging Area
- ob Commits oder Pushes ausstehen

# Dateien zur Staging Area hinzufügen

```bash
git add .
```

## Was macht der Befehl?

Fügt alle neuen und geänderten Dateien zur **Staging Area** hinzu.

Die Staging Area ist eine Art "Wartebereich" für den nächsten Commit.

## Wann verwende ich ihn?

Nachdem du Dateien erstellt oder geändert hast und diese im nächsten Commit speichern möchtest.

## Merksatz

**"Ich packe meine Änderungen in den Rucksack für den nächsten Schnappschuss."**
# Commit erstellen

```bash
git commit -m "Add description"
```

## Was macht der Befehl?

Erstellt einen **Commit**.

Ein Commit ist ein Schnappschuss des Projekts zu einem bestimmten Zeitpunkt.

Nur Dateien, die zuvor mit `git add` zur Staging Area hinzugefügt wurden, werden gespeichert.

## Wann verwende ich ihn?

Wenn eine sinnvolle Arbeitseinheit abgeschlossen ist.

Zum Beispiel:

- Neue Funktion
- Fehler behoben
- Dokumentation ergänzt
- Projektstruktur erstellt

Beispiel:

```bash
git commit -m "Add initial project documentation"
```

## Merksatz

**"Ich mache ein Foto meines aktuellen Arbeitsstands."**
## Commit-Messages Scheme
- docs: improve vision statement
- docs: update roadmap
- docs: add architecture overview

- feat: add expense model
- feat: implement trip creation

- fix: correct date parsing

- refactor: simplify trip service

- test: add expense unit tests

- chore: update .gitignore