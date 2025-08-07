# claude.cursor-rules

Ein Repository für optimierte Entwicklungsregeln zur Verwendung mit Claude und Cursor.

## 📋 Übersicht

Dieses Repository enthält spezifische Regeln und Richtlinien für die Zusammenarbeit zwischen Entwicklern und KI-Assistenten, um eine saubere, minimalistische und effiziente Projektstruktur zu gewährleisten.

## 🎯 Kernprinzipien

### Minimalismus
- **Eine Datei pro Thema**: Jedes Thema oder Modul erhält genau eine Datei oder einen Ordner
- **Keine Redundanz**: Vorhandene Dateien werden editiert, nicht dupliziert
- **Geringe Entropie**: Die Anzahl der Dateien wird minimalistisch gehalten

### Strukturelle Integrität
- **Projektstruktur einhalten**: Vorhandene Strukturen werden unter allen Umständen respektiert
- **Fundamentale Komponenten**: Datenbanklogik, Konfiguration und Startdatei (main/app) sind essentiell
- **Keine unangekündigten Änderungen**: Gravierende Code-Änderungen nur nach Rückfrage

### Datenverwaltung
- **Echte Daten verwenden**: Keine Musterdaten oder Platzhalter
- **Credentials nutzen**: Vorhandene Anmeldedaten und Konfigurationen verwenden
- **Keine redundanten Datenbanken**: Bestehende Datenbanken nutzen

### Änderungsmanagement
- **Versionierung**: Alle Änderungen werden im CHANGELOG.md dokumentiert
- **Propagierung**: Änderungen werden durch alle betroffenen Komponenten propagiert
- **Abhängigkeiten**: Implizite Abhängigkeitskaskaden werden beachtet und angepasst
- **Kompatibilität**: Alle Änderungen müssen rückwärtskompatibel sein oder klar kommuniziert werden

## 📝 Wichtige Hinweise

- **Keine Windows-Skripte** (.bat, .ps1) werden erstellt, außer explizit gefordert
- **Keine TODOs** in Code oder Dokumentation
- **Vorhandene Dateien** werden nicht ungefragt gelöscht
- **Saubere Struktur** hat höchste Priorität
