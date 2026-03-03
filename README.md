# C# Portfolio – HR Overview

**Professionelle Desktop-Anwendungen mit C# und .NET**

Dieses Repository bietet eine übersichtliche Präsentation meiner wichtigsten Desktop-Projekte, entwickelt mit modernen .NET-Technologien.
Alle Anwendungen sind produktiv einsetzbar, eigenständig gepflegt und im Microsoft Store veröffentlicht.

> 📊 **Microsoft Store Statistiken**: Im Repository befinden sich Archive mit detaillierten Statistiken vom 12.01.2026 aus dem Microsoft Store für alle 5 Projekte.

## 🔓 Open Source

Alle Projekte sind Open Source, mit Ausnahme von **Vetale Browser**, der als proprietäres Hauptprodukt entwickelt wird.

---

## Vetale Browser

**Moderner Desktop-Webbrowser mit integrierter KI und Fokus auf Datenschutz**

Vetale Browser ist ein leistungsfähiger Desktop-Webbrowser mit KI-Unterstützung, moderner Benutzeroberfläche und klarer Trennung zwischen lokaler Verarbeitung und externen Diensten.

### Highlights für Recruiter:
- Integration moderner KI-Technologien (lokal + API-basiert)
- Komplexes UI- und State-Management (Tabs, Sessions, Speicheroptimierung)
- Fokus auf Datenschutz und Offline-Funktionalität
- Produktiv im Microsoft Store veröffentlicht

### Technologien:
`C#` · `.NET 10` · `Avalonia UI` · `Chromium WebView` · `LiteDB`

🔗 **Microsoft Store**:  https://apps.microsoft.com/detail/9P2XG1K9CVMH 
🔗 **GitHub Repository**: https://github.com/Developer3421/Vetale-Browser-Official

---

## Insait Text Editor

**Intelligenter Texteditor mit lokalem KI-Assistenten (Offline-First)**

Ein moderner Texteditor mit lokal ausgeführtem KI-Assistenten.
Die Anwendung ist vollständig offline nutzbar und legt besonderen Wert auf Privatsphäre und Performance.

### Highlights für Recruiter:
- Eigenständige Desktop-App mit komplexer interner Architektur
- Lokale KI-Inferenz ohne Cloud-Abhängigkeit
- Saubere MVVM-Struktur und modulare Services
- Mehrsprachige Benutzeroberfläche

### Technologien:
`C#` · `.NET 10` · `Avalonia UI` · `LLamaSharp` · `LiteDB` · `SkiaSharp`

🔗 **Microsoft Store**: https://apps.microsoft.com/detail/9PMDTL9PRP7J
🔗 **GitHub Repository**: https://github.com/Developer3421/Insait-Text-Editor

---

## VRelaxTimer

**Leichtgewichtige Desktop-Anwendung für Fokus und Entspannung**

VRelaxTimer kombiniert einen klassischen Entspannungstimer mit einem lokalen KI-Textassistenten.
Die Anwendung ist bewusst minimalistisch gehalten und vollständig offline nutzbar.

### Highlights für Recruiter:
- Fokus auf einfache UX und klare Funktionalität
- Lokale KI-Nutzung ohne externe Services
- Saubere asynchrone Verarbeitung
- Single-File Deployment

### Technologien:
`C#` · `.NET 9` · `WPF` · `LLamaSharp`

🔗 **Microsoft Store**: https://apps.microsoft.com/detail/9PBNDBFZ1JKK
🔗 **GitHub Repository**: https://github.com/Developer3421/VRelaxTimer

---

## German B1 – Step Further

**Desktop-Anwendung zum Deutschlernen (B1-Niveau)**

Eine strukturierte Lernanwendung für Deutsch als Fremdsprache mit integriertem KI-Assistenten zur individuellen Unterstützung.

### Highlights für Recruiter:
- Didaktisch strukturierter Content
- Fortschritts- und Sitzungsverwaltung
- Kombination aus klassischer Lernlogik und KI-Unterstützung
- Store-taugliche Produktarchitektur

### Technologien:
`C#` · `.NET 10` · `Avalonia UI` · `LiteDB` · `LLamaSharp`

### Technische Details:
- **Framework**: .NET 10.0, Avalonia UI 11.3.9
- **UI-Komponenten**: Tab-basierte Navigation, Dual-Panel-Ansicht, benutzerdefinierte Titelleiste
- **Datenbank**: LiteDB 6.0 für Sitzungsverwaltung und Fortschrittsspeicherung
- **KI-Integration**: LLamaSharp 0.25.0 mit Gemma-3-270m-Modell für intelligente Lernunterstützung
- **Architektur**: MVVM-Pattern mit ResourceDictionary-basiertem Inhaltssystem
- **Inhalt**: 4 Teile mit je 18 Themen (Wortschatz, Konversation, Grammatik, Übungen)

### Hauptfunktionen:
- Interaktive Grammatikübungen und Zeitformen
- Tabbed Interface für paralleles Lernen
- Session-Management mit Lesezeichenfunktion
- Eingebetteter WebView für erweiterte Inhalte
- KI-Assistent für personalisierte Hilfe

🔗 **Microsoft Store**: https://apps.microsoft.com/detail/9P6F8KJJWTJ5
🔗 **GitHub Repository**: https://github.com/Developer3421/german-b1-step-further

---

## Vetale Browser Super Lite

**Minimalistischer Chromium-basierter Desktop-Browser**

Eine bewusst reduzierte Browser-Variante mit Fokus auf Stabilität, Sicherheit und geringer Ressourcennutzung.

### Highlights für Recruiter:
- Klassische Desktop-Architektur mit WPF
- Direkte Arbeit mit Embedded Chromium (CEF)
- Eigene Fehler- und Sicherheitslogik
- Klarer Fokus auf Wartbarkeit

### Technologien:
`C#` · `WPF` · `.NET Framework 4.8` · `CefSharp`

🔗 **Microsoft Store**:  https://apps.microsoft.com/detail/9NZPNGDCQX2P
🔗 **GitHub Repository**: https://github.com/Developer3421/Vetale-Browser-SuperLite

---

## Insait Edit – C#-IDE

**Moderne, plattformübergreifende Entwicklungsumgebung für C# und .NET**

Insait Edit ist eine leistungsstarke IDE für C#- und .NET-Entwicklung, aufgebaut auf Avalonia UI und der Roslyn-Compiler-Plattform. Sie bietet IntelliSense, Echtzeit-Diagnose, Refactoring, MSBuild-Integration, ein eingebettetes Terminal, NuGet-Verwaltung und Git-/GitHub-Integration – alles in einem modernen Fluent-Design in Orange-Violett.

### Highlights für Recruiter:
- Vollständige Roslyn-Integration: IntelliSense, Code-Fixes, symbolweites Umbenennen
- MSBuild-Integration zum Erstellen, Ausführen und Veröffentlichen von .NET-Projekten
- Eingebetteter ConPTY-Terminal-Emulator mit ANSI-Rendering
- Git- und GitHub-Integration (Commit, Push, Pull, Diff, Klonen)
- NuGet-Paketverwaltung und MSIX-Manager direkt in der IDE
- ESP32-/nanoFramework-Unterstützung mit visuellem LED-Panel-Designer
- AXAML-Live-Vorschau für Avalonia-UI-Dateien
- Mehrsprachige Oberfläche (Englisch, Ukrainisch, Deutsch, Russisch, Türkisch)
- Gemini-KI-Assistent für Code-Unterstützung und Übersetzung

### Technologien:
`C#` · `.NET 10` · `Avalonia UI 11.3` · `Microsoft Roslyn 5.0` · `MSBuild 18.3` · `LibGit2` · `NuGet.Protocol` · `Octokit` · `LiteDB` · `nanoFramework`

🔗 **GitHub Repository**: https://github.com/Developer3421/Insait-Edit-C-Sharp

---

## VCalc – Wissenschaftlicher Taschenrechner

**Moderner Desktop-Taschenrechner mit wissenschaftlichen Funktionen und vollständiger Tastaturunterstützung**

VCalc ist ein eleganter wissenschaftlicher Taschenrechner für Windows mit warmem Farbdesign, abgerundeten Ecken und flüssigen Verläufen. Er bietet Grundrechenarten sowie wissenschaftliche Funktionen wie Sinus, Kosinus, Tangens, Logarithmus und Potenzrechnung, unterstützt mehrere Fenster gleichzeitig und benötigt keine Internetverbindung.

### Highlights für Recruiter:
- Wissenschaftliche Funktionen (sin, cos, tan, log, ln, Potenz, π, e)
- Vollständige Tastatur- und Nummernblock-Unterstützung
- Multi-Window-Unterstützung für parallele Berechnungen
- Datenschutzkonform: kein Netzwerkzugriff, keine Telemetrie

### Technologien:
`C#` · `.NET 10` · `WPF`

🔗 **Microsoft Store**: https://apps.microsoft.com/detail/9NCBKT3KXS5F
🔗 **GitHub Repository**: https://github.com/Developer3421/VCalc

---

## FileManager – Dateimanager

**Moderner, leichtgewichtiger Dateimanager für Windows mit Multi-Tab-Navigation**

Ein schlanker Dateimanager auf Basis von Avalonia UI mit Multi-Tab-Navigation, Listen- und Rasteransicht, integrierter Bildvorschau, nativen Windows-Shell-Kontextmenüs und einer Schnellzugriff-Seitenleiste für Desktop, Downloads, Dokumente, Bilder, Videos und Musik.

### Highlights für Recruiter:
- Multi-Tab-Navigation mit persistenter Tab-Wiederherstellung beim Start
- Unterstützung nativer Windows-Shell-Kontextmenüs
- Sortierung nach Name, Datum, Größe und Typ
- Eingebetteter Bildbetrachter für gängige Bildformate
- Mehrsprachige Oberfläche (Englisch, Ukrainisch, Deutsch)
- Laufwerksanzeige mit Nutzungsinformationen

### Technologien:
`C#` · `.NET` · `Avalonia UI`

🔗 **Microsoft Store**: https://apps.microsoft.com/detail/9PH9GFGXJDHK
🔗 **GitHub Repository**: https://github.com/Developer3421/FileManager

---

## Insait Video Player – Videoplayer

**Funktionsreicher Desktop-Videoplayer mit Sitzungsverwaltung und verschlüsselter Datenspeicherung**

Ein moderner Videoplayer für Windows, der auf Avalonia UI und LibVLC basiert. Er unterstützt eine Vielzahl von Videoformaten, bietet ein Tab-Interface für mehrere Videos gleichzeitig, automatische Sitzungsspeicherung, Wiedergabeverlauf mit Positionsspeicherung, Untertitelverwaltung und Audiospurauswahl.

### Highlights für Recruiter:
- Tabbed Interface mit Drag-to-Reorder und Überlaufmenü
- Sitzungsverwaltung mit verschlüsselter Speicherung via Windows DPAPI
- Vollbild-Modus mit automatischem UI-Ausblenden
- Drag-and-Drop zum Öffnen von Videodateien
- Mehrsprachige Oberfläche (Ukrainisch, Englisch, Deutsch, Russisch, Türkisch)
- Datenschutzkonform: alle Daten lokal und verschlüsselt

### Technologien:
`C#` · `.NET 10` · `Avalonia UI 11.3` · `LibVLCSharp 3.9.5` · `LiteDB 6.0` · `Windows DPAPI`

🔗 **Microsoft Store**: https://apps.microsoft.com/detail/9PKXCQFWDNFQ
🔗 **GitHub Repository**: https://github.com/Developer3421/Insait-Video-Player

---

## Insait Translator: German – Übersetzungsanwendung

**Hybrid-Desktop-App (C# + React) zum Übersetzen beliebiger Sprachen ins Deutsche mit optionaler Text-to-Speech-Funktion**

Eine datenschutzorientierte Windows-Desktop-Anwendung, die Text aus beliebigen Sprachen ins Deutsche übersetzt. Sie nutzt mehrere Übersetzungsanbieter mit automatischem Fallback (MyMemory, Google Translate via GTranslate, optional Google Gemini API), bietet deutsche Text-to-Speech-Ausgabe über Piper TTS und eine optionale lokale Web-Oberfläche auf React-Basis.

### Highlights für Recruiter:
- Hybride Architektur: Avalonia-Desktop-App mit eingebettetem React-Web-UI
- Anbieter-Fallback-System für robuste Übersetzungen ohne Unterbrechung
- Lokaler HTTP-Backend-Server für die React-UI (kein Node.js zur Laufzeit erforderlich)
- Verschlüsselte Einstellungsspeicherung (AES-256 + Windows DPAPI)
- German TTS mit Piper: Wiedergabe und MP3-Export
- Workspace-Tabs mit persistenter Speicherung via LiteDB
- Keine Entwickler-Telemetrie – Netzwerkanfragen nur an gewählte Anbieter

### Technologien:
`C#` · `.NET 10` · `Avalonia UI 11` · `ReactiveUI` · `React/Vite` · `LiteDB` · `Piper TTS` · `NAudio` · `LibVLCSharp` · `AES-256` · `Windows DPAPI`

🔗 **Microsoft Store**: https://apps.microsoft.com/detail/9PH8XTJ8BCJ7
🔗 **GitHub Repository**: https://github.com/Developer3421/Insait_Translator_German

---

## V-Task – Systemressourcen-Monitor

**Schlanker, moderner Ressourcenmonitor für Windows mit Echtzeit-Einblick in CPU, RAM, GPU, Festplatte und Netzwerk**

V-Task ist ein eleganter Systemmonitor mit warmem Fluent-UI-Design. Er zeigt Echtzeit-Metriken für CPU, Arbeitsspeicher, GPU, Festplattenaktivität und Netzwerkgeschwindigkeit – ohne Telemetrie, ohne Netzwerkzugriff, ohne Werbung. Alle Daten verbleiben lokal auf dem Gerät.

### Highlights für Recruiter:
- Echtzeit-CPU-Auslastung mit Prozessorname und Kernanzahl
- Detailliertes RAM-Panel mit Swap/Auslagerungsdatei, Frequenz, Typ und Steckplätzen
- GPU-Überwachung: Videospeicher, Treiber-Version, Schnittstelleninfos
- Netzwerk-Monitor: Download-/Upload-Geschwindigkeit, Gesamtdatenvolumen
- Konfigurierbare Aktualisierungsrate und Mehrsprachigkeit (5 Sprachen)
- Datenschutzkonform: keine Telemetrie, kein Netzwerkzugriff

### Technologien:
`C#` · `.NET 10` · `Avalonia UI 11.3` · `LibreHardwareMonitor` · `LiteDB` · `WMI` · `PerformanceCounter`

🔗 **Microsoft Store**: https://apps.microsoft.com/detail/9P405177WBX9
🔗 **GitHub Repository**: https://github.com/Developer3421/V-Task

---

## Vetale Browser – Legacy (WPF, 2024)

**Historisches Prototyp-Projekt: Erster Webbrowser auf WPF-Basis als Lernprojekt**

Das erste Vetale-Browser-Projekt aus dem Jahr 2024 – ein minimalistischer Desktop-Webbrowser auf Basis von WPF und Microsoft WebView2. Das Projekt diente als praktische Einführung in Desktop-Anwendungsentwicklung und WebView2-Integration und legte den Grundstein für alle späteren Vetale-Browser-Generationen.

### Highlights für Recruiter:
- Grundlegende Tab-Unterstützung, Navigationsverlauf und Multi-Window-Modus
- Nur ~22 MB Distributionsgröße inklusive WebView2-Runtime
- Kein Cloud-Sync, keine Telemetrie, minimaler interner Zustand
- Historisches Projekt: zeigt die Entwicklung und den Lernfortschritt über die Zeit

### Technologien:
`C#` · `WPF` · `.NET 7` · `Microsoft WebView2`

🔗 **GitHub Repository**: https://github.com/Developer3421/Vetale-Browser-Legacy-WPF-2024-

---

## Zusammenfassung für HR

✅ Mehrere produktionsreife Desktop-Anwendungen  
✅ Moderne .NET- und UI-Frameworks  
✅ Erfahrung mit KI-Integration (lokal & API-basiert)  
✅ Microsoft-Store-Erfahrung (Packaging, Deployment, Policies)  
✅ Fokus auf saubere Architektur, Datenschutz und Wartbarkeit  
✅ Hybride Anwendungsarchitektur (C# + React/Web)  
✅ Breites Anwendungsspektrum: IDE, Browser, Mediaplayer, Systemtools, Lern-Apps

---

**Lizenz**: MIT (außer Vetale Browser)

