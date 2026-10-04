# Funktionen

## Git-Funktionen

- Vollständige Git-Operationen: `clone`, `pull`, `push`, `fetch`, `commit`, `status` sowie Branch-Erstellung
- Branch-Verwaltung: Erstellen, Auflisten und Wechseln zwischen Branches (keine GUI für Merge/Rebase)
- Signierte Commits ausschließlich mit OpenSSH-Schlüsseln (derzeit keine Unterstützung für GPG/PGP)

## Dateiverwaltung und Bearbeitung

- Integrierter Datei-Explorer: Dateien und Ordner erstellen, umbenennen und löschen
- In-App-Bearbeitung von Klartextdateien mit Syntaxhervorhebung (Code, Konfigurationsdateien, Markdown usw.)
- `.gitignore` bearbeiten und eigene Commit-Nachrichten verwenden

## Authentifizierung

Unterstützte Authentifizierungsmethoden:

- GitHub
- GitLab
- Gitea
- Codeberg
- SSH-Schlüssel
- HTTP(S) mit Personal Access Tokens
- Selbst gehostete Instanzen über Token oder SSH

## Synchronisierung

- Hintergrundsynchronisierung mit anpassbaren Auslösern
- Android: Synchronisierung beim Öffnen/Schließen der App empfohlen
- iOS: App-Synchronisierung oder erweiterte geplante Synchronisierung empfohlen
- Synchronisierung pro Repository, mehrere Repositories werden unterstützt

## Weitere Funktionen

- Erkennung von Merge-Konflikten und Oberfläche zu deren Auflösung
- Backup und Wiederherstellung per verschlüsseltem Export (passwortgeschützt, eigenes Format)

## Bekannte Einschränkungen und fehlende Funktionen

- Kein Dateidiff-Viewer außerhalb von Merge-Konflikten (zum Anzeigen von Diffs sind externe Tools erforderlich)
- Eingeschränkte Unterstützung für Submodule (siehe FAQ)
- Keine Unterstützung für Branching/Merging über einfaches Wechseln und Erstellen hinaus
- Keine Unterstützung für Git-Hooks
