# Heizungssystem Visualisierung & Steuerung

![Heizungssystem Touchscreen]

Ein Touchscreen-fähiges Heizungssteuerungssystem für Kessel und Puffer.  
Dieses Projekt ermöglicht die Visualisierung, Steuerung und Konfiguration deines Heizsystems direkt über einen 7-Zoll Touchscreen oder Browser.

---

## Funktionen

### 1. Live-Visualisierung
- Kesseltemperatur anzeigen
- Puffertemperatur anzeigen
- Pumpenstatus (Puffer, Heizung, Pool)
- Gebläse AN/AUS
- Austragung/Schnecken Animation
- Störungsanzeige blinkend

### 2. Heizungssteuerung
- Heizung ein-/ausschalten über Touchbutton
- Gebläse ein-/ausschalten
- Pumpenstatus anzeigen
- Austragung aktivieren/deaktivieren

### 3. Temperatur-Setup (Tag/Nacht)
- Tag- und Nachttemperaturen einstellen (Start/Endtemperatur)
- Zeiträume für Tag und Nacht konfigurieren
- Alles über Touchbuttons steuerbar – keine Tastatur nötig
- Änderungen werden direkt in die SQLite-Datenbank gespeichert

### 4. Historie & Logging
- Alle wichtigen Änderungen werden in der `history`-Tabelle protokolliert
- Ereignisse: Heizung AN/AUS, Gebläse, Austragung, Störung
- Letzte 15 Einträge über API abrufbar

---

## Installation

### Voraussetzungen
- Node.js 18+
- SQLite3
- PM2 (optional für Autostart)

### Setup
