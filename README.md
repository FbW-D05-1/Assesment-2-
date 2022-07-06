# BDL Assessment

## Art der Frage

- Mehrere Antworten: Mehrere Antworten können richtig sein
- R/F: Richtig oder Falsch
- Multiple Choice: Nur eine Antwort ist richtig.

# Anfänger: Überprüfe auf Verständnis

### Beantworte die folgenden Fragen

1. (Mehrere Antworten) Git ist:

   - [x] Ein Versionsverwaltungsystem
   - [ ] Zentralisiert
   - [x] Verteilt
   - [ ] Dasselbe wie GitHub

1. (R/F) Git und GitHub sind dasselbe.

   - [ ] Richtig
   - [x] Falsch

1. (Multiple Choice) Was ist GitHub?

   - [x] Ein Anbieter von Git-Repositories
   - [ ] Eine Integrierte-Entwicklungs-Umgebung (engl. integrated development environment - IDE)
   - [ ] Das Unternehmen dem Git gehört
   - [ ] Alle Antworten treffen zu.

1. (Schreibe in den Platzhalter) Wie heißt der Entwicklungszweig ("branch") für Produktiv-Code (engl. "deployment-ready code")?    

Main oder Master

1. (R/F) Pull Requests sollten voll funktionsfähig und fehlerfrei sein, bevor sie Teamkollegen ansehen.

   - [x] Richtig
   - [ ] Falsch

1. (R/F) Git speichert die Versionsgeschichte und den jeweiligen Autor.

   - [x] Richtig
   - [ ] Falsch

1. (Multiple Choice) Was ist Markdown?

   - [ ] Eine Syntax um Text einfach fürs Web zu formatieren.
   - [ ] Eine Möglichkeit Projekte auf GitHub zu bewerten.
   - [x] Eine Programmiersprache für Web-Anwendungen.
   - [ ] Eine Möglichkeit Code in einer Cloud bereitzustellen.

1. (Multiple Choice) Was ist ein Commit?

   - [x] Ein Schnappschuss (engl. "snapshot") aller Dateien in einem Repository.
   - [ ] Ein Schnappschuss lediglich der Veränderungen bzgl. des Zustandes davor.
   - [ ] Eine Sammlung von Entwicklungszweigen (engl. "branches).
   - [ ] Eine andere Bezeichnung für ein Repository.

1. (Multiple Choice) Was ist ein Entwicklungszweig (engl. "branch")?

   - [x] Ein Verweis auf einen speziellen Commit.
   - [ ] Eine Verbindung zwischen einer lokalen und einer entfernten (engl. "remote") Entwicklungsgeschichte.
   - [ ] Der zentrale Ort an dem Repositories gespeichert werden.
   - [ ] Eine Dateiversion zu einem speziellen Zeitpunkt.

1. (Multiple Choice) Welches der folgenden Kommandos erzeugt einen neuen Entwicklungszweig (engl. "branch")?
   - [ ] `git checkout new-branch`
   - [x] `git checkout -b new-branch`
   - [ ] `git clone new-branch`
   - [ ] `git create-branch new-branch`

---

# Fortgeschrittene Anfänger: Überprüfe auf Verständnis

### Beantworte die folgenden Fragen

1. (R/F) Vor einem Commit ist "Staging" oder `git add` notwendig.

   - [x] Richtig
   - [ ] Falsch

1. (Multiple Choice) Welches der folgenden Kommandos ermöglicht es den Entwicklungszweig (engl. "branch") zu wechseln?

   - [x] `git checkout`
   - [ ] `git clone`
   - [ ] `git add`
   - [ ] `git commit`

1. (Mehrere Antworten) Was macht eine gute Commit-Nachricht aus?

   - [x] Kurz, weniger als 50 Zeichen.
   - [x] Sie beschreibt die Änderung, die bei diesem Commit eingeführt wurde.
   - [ ] Erzählt die Geschichte, wie sich das Projekt entwickelt hat.
   - [ ] Commit-Nachrichten sind optional.

1. (R/F) Das Kommando `git push` wird benutzt, um Änderungen vom entfernten ins lokale Repository zu holen.

   - [ ] Richtig
   - [x] Falsch

1. (Multiple Choice) Welches der folgenden Kommandos ermöglicht es Commits vom entfernten (engl. "remote") ins lokale Repository zu holen?

   - [x] `git pull`
   - [ ] `git push`
   - [ ] `git checkout`
   - [ ] `git add`

1. (R/F) "Merging" ermöglicht es Änderungen, die in einem Entwicklungszweig (engl. "branch") vorgenommen wurden, mit Änderungen auf einem anderen Entwicklungszweig zusammenzuführen.

   - [x] Richtig
   - [ ] Falsch

1. (Multiple Choice) Welche der folgenden Kommando-Sequenzen wird `hotfix`-Entwicklungszweig _in_ den `main`-Entwicklungszweig (engl. "branch") zusammenführen?

   - [x] `git checkout main` und `git merge hotfix`
   - [ ] `git checkout hotfix` und `git merge main`
   - [ ] `git merge main` und `git checkout hotfix`
   - [ ] `git merge hotfix` und `git checkout main`

1. (R/F) Git kann mit den meisten Text-Editoren genutzt werden.

   - [x] Richtig
   - [ ] Falsch

1. (R/F) "Clonen" eines Repositorys erzeugt eine lokale Kopie mit nur dem `main`-Entwicklungszweig (engl. "branch").

   - [ ] Richtig
   - [x] Falsch

1. (Multiple Choice) Was macht das Kommando `git branch` (ohne weitere Option)?
   - [x] Zeigt eine Liste lokaler Entwicklungszweige (engl. "branches")
   - [ ] Erzeugt einen Entwicklungszweig
   - [ ] Löscht einen Entwicklungszweig
   - [ ] Bennent einen Entwicklungszweig um
