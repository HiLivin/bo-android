# TODO:
 * layer configuration
 * custom layers

# Changelogs

## English

### Version 1.2 (Android 4.0+)
 * enabled Hardware acceleration

### Version 1.1
 * use AlarmManager and WakeLocks to ensure background service operation
 * reduce amount of transferred data, when running in background
 * alarm signal only at situation changes
 * updated Blitzortung.org data access

### Version 1.0
 * tap on histogram zooms to full data area
 * tap on alarm radar zooms to current location
 * improved UI scaling
 * added alarm signal settings to configure vibration and/or sounds 
 * refactored alarm logic
 * fixed data updates on parameter change
 * fixed background task behaviour
 * fixed GPS signal detection
 
### Version 0.9
 * added GPS based and manual location
 * added support for devices without menu button
 * reorganized menu
 * added ability to disable stations layer in Blitzortung.org mode
 * optimized alarm handling
 * manual location entry: enabled negative numbers in input fields
 * GPS signal loss detection

### Version 0.8
 * access to historical lightning data
 * configurable time-length of data display

### Version 0.7
 * transparent infobar
 * added legend overlay
 * added histogram overlay
 * added local alarm overlay
 * package cleanup
 * raster display fix
 * metric/imperia systems of measurement
 * alternative data service running on port 80
 * option to disable sleep mode of device
 * added summary texts to preferences
 * fading of map
 * selectable color schemes

### Version 0.6
 * display of stroke counts for higher zoom levels
 * display of raster data area extent
 * notification and vibration alarm with preference integration
 
## German

### Version 1.3 (Android 4.0+)
 - Probleme mit Warntönen auf einigen Geräten beseitigt
 - Hintergrundabfrage ab Neustart
 - Überarbeitete Struktur mit Service

### Version 1.2 (Android 4.0+)
 - Hardwarebeschleunigung aktiviert

### Version 1.1
 - verwendet AlarmManager und WakeLocks um den Betrieb des Hintergrunddienstes sicherzustellen
 - die Größe der im Hintergrund übertragenen Daten wurde stark reduziert.
 - Alarmsignal nur bei Änderung der Situation
 - Zugriff auf Blitzortung.org Daten angepasst

### Version 1.0
 * Zoom auf vollen Datenbereich bei Tippen auf Histogram
 * Zoom auf aktuelle Position bei Tippen auf Alarm-Radar
 * Verbesserte Skalierung der Oberfläche
 * neue Alarm-Signal Einstellungen konfigurieren Vibration und/oder Tonsignal 
 * Überarbeitung der Alarm-Logik
 * Verbesserte Behandlung von Parameteränderungen
 * Verbessertes Verhalten des Hintergrundtasks
 * Verbesesrte Erkennung des GPS-Signals
 
### Version 0.9
 * GPS-basierte und manuelle Ortung hinzugefügt
 * Unterstützung für Geräte ohne Menüknopf
 * Reorganisation des Menüs
 * Stationsanzeige im Blitzortung.org Modus ist abschaltbar
 * Alarmverarbeitung optimiert und überarbeitet
 * negative Koordinaten bei der manuellen Ortsangabe ermöglicht

### Version 0.8
 * Zugriff auf Blitzdaten der letzten 24 Stunden
 * Konfigurierbare Länge des Datenzeitraums

### Version 0.7
 * Transparente Infoleiste
 * Anzeige von Legende, Zeit-Histogramm und Alarmübersicht
 * Aufräumarbeiten
 * Fix für Rasteranzeige
 * Metrisches/imperiales Einheitensystem
 * alternativer Datenservice über Port 80 erreichbar
 * Voreinstellung zur Unterdrückung des Ruhezustands bei aktiver App
 * Beschreibungstexte für Voreinstellungen
 * Verblassen der Karte
 * wählbare Farbschemata

### Version 0.6
 * Darstellung der Blitzzahlen
 * Darstellung der Gesamtfläche der Rasterdaten
 * Benachrichtigungen und Vibrationsalarm
