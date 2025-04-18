# C++ Git & GitLab Demo

Dieses Projekt zeigt, wie man Git und GitLab in einem einfachen C++-Projekt effektiv nutzt. Es enthält grundlegende Git-Operationen, eine Commit-Guide-Dokumentation und ist vollständig für die Verwendung mit GitLab CI/CD eingerichtet.

## Überblick

In diesem Projekt findest du:

- Eine einfache `main.cpp`, die "Hello, World!" ausgibt.
- Eine `.gitignore`-Datei, um unnötige Dateien vom Git-Tracking auszuschließen.
- Eine `commitguide.md`-Datei, die die besten Praktiken für Commit-Messages erklärt.
- GitLab CI/CD für eine einfache Pipeline-Konfiguration.

## 🚀 Erste Schritte

### 1. Repository klonen

Hier einmal voher noch ssh keygen erklären und vielleicht ein kleines how to schreiben.
Verlinke das how to.
Klonen des Repositories auf deinen lokalen Rechner:

```bash
git clone git@github.com:Brainfcker929/DemoRob.git
cd cpp-gitlab-demo
```

### 2. Abhängigkeiten installieren

Erklärung was man alles für C++ braucht. Welche tools kann man empfehlen? Ide, precommit hook etc.

### 3. Kompilieren und Ausführen

Um das Programm zu kompilieren und auszuführen, benutze einen C++-Compiler wie g++:
Ich mach das zum Beispiel mit vscode alles. 😋

```bash
g++ main.cpp -o hello_world
./hello_world
```

### 4. GitLab CI/CD Setup

Die `.gitlab-ci.yml`-Datei enthält eine einfache GitLab CI/CD-Konfiguration, um das Projekt bei jeder Änderung zu bauen und zu testen. Weitere Details zur CI/CD-Konfiguration findest du in der [GitLab-Dokumentation](https://docs.gitlab.com/ee/ci/).

## ⚙️ Git Features

Wenn man will how to für git features erklären.
Und wie man in branches arbeitet, Ihr habt euch ja für main und dev entschieden.

### Branching

Verwende Branches, um neue Features oder Fehlerbehebungen zu entwickeln, ohne die Hauptentwicklungslinie zu stören:

```bash
git checkout -b feature/neues-feature
```

### GitLab Merge Requests

Erstelle einen Merge Request (MR) auf GitLab, um Änderungen in den Hauptbranch (meist `main` oder `master`) zu integrieren. Dies ist eine gängige Methode zur Code-Überprüfung und Zusammenarbeit.

## 📜 Commit-Guide

In der Datei `docs/commitguide.md` findest du eine detaillierte Anleitung, wie du deine Commit-Nachrichten strukturierst, um die Projektgeschichte sauber und nachvollziehbar zu halten.

## 🔧 GitLab CI/CD-Pipeline

Die `.gitlab-ci.yml`-Datei definiert eine Pipeline, die jedes Mal ausgeführt wird, wenn du Änderungen in dein GitLab-Repository pusht. Sie enthält folgende Stufen:

1. **Build**: Kompiliert den C++-Code.
2. **Test**: Führt alle Unit-Tests durch (falls vorhanden).
3. **Deploy**: Stellt das Projekt in einer Testumgebung bereit (optional).

## ✨ Features

- **Einfache C++-Anwendung**: Kompiliert und führt ein einfaches "Hello, World!"-Programm aus.
- **GitLab CI/CD**: Eine vollständige Pipeline zur Automatisierung des Build- und Testprozesses.
- **Commit-Guide**: Detaillierte Richtlinien für das Schreiben effektiver und verständlicher Commit-Nachrichten.

## 📑 Weitere Ressourcen

- [GitLab Dokumentation](https://docs.gitlab.com/ee/)
- [Git Dokumentation](https://git-scm.com/doc)
- [C++ Dokumentation](https://en.cppreference.com/w/)

## 🛠️ Technologien

- **Git**: Versionskontrolle.
- **GitLab CI/CD**: Automatisierte Builds und Tests.
- **C++**: Programmiersprache.
