# QR-Code Scanner mit GUI - 
![npm bundle size (version)](https://img.shields.io/badge/version-0.0.1-green) ![npm bundle size (version)](https://img.shields.io/badge/language-Java-red) ![npm bundle size (version)](https://img.shields.io/badge/shell-bash-green)
## Übersicht
Dies ist eine Java-Anwendung mit grafischer Benutzeroberfläche (GUI) zum Scannen von QR-Codes über die integrierte Webcam. Die App nutzt die ZXing-Bibliothek ("Zebra Crossing") zur QR-Code-Erkennung und die Webcam Capture API für den Kamerazugriff.

## Funktionen
- Echtzeit-QR-Code-Scanning
- Einfache und übersichtliche Benutzeroberfläche
- Anzeige des gescannten QR-Code-Inhalts
- Webcam-Livebild mit FPS-Anzeige (Bilder pro Sekunde)
- Plattformübergreifend (Windows, macOS, Linux)

## Voraussetzungen
- Java Runtime Environment (JRE) 8 oder neuer
- Funktionierende Webcam
- Internetverbindung (für Abhängigkeiten)

## Abhängigkeiten
- [Webcam Capture API](https://github.com/sarxos/webcam-capture)
- [ZXing ("Zebra Crossing")](https://github.com/zxing/zxing)

## Installation
1. Repository klonen oder herunterladen
2. Java Development Kit (JDK 8+) installieren
3. Projekt mit den benötigten Abhängigkeiten kompilieren

## Verwendung
1. Anwendung starten
2. Webcam auf einen QR-Code richten
3. Der gescannte Inhalt erscheint automatisch im Textfeld

## Screenshot
![QR-Scanner GUI](screenshot.png) *(Beispielbild einfügen)*

## Build-Anleitung
```bash
mvn clean package
