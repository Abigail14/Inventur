# Lagerbuch – Inventur & automatische Bestellung für die Gastronomie

Eine einzelne HTML-Datei für Küche und Bar: Bestände zählen, Meldebestände überwachen und Bestellungen pro Lieferant automatisch vorbereiten.

## Funktionen

- **Inventur** nach Lagerort (Kühlhaus, Bar, Keller …) mit Soll/Ist-Differenz in Menge und Euro, CSV-Export
- **Automatische Bestellvorschläge**: Bestand + offene Bestellungen − Tagesverbrauch × Lieferzeit ≤ Meldebestand → auffüllen bis Sollbestand, gerundet auf ganze Gebinde
- **Bestellentwürfe** an den Bestelltagen eines Lieferanten, Hinweis auf Mindestbestellwert, fertiger Bestelltext zum Kopieren
- **Wareneingang** bucht Bestände automatisch hoch
- **Verbrauch lernen**: Tagesverbrauch wird aus aufeinanderfolgenden Inventuren berechnet
- Artikel- und Lieferantenverwaltung, Verlauf aller Inventuren und Bestellungen
- Hell- und Dunkelmodus, funktioniert auf dem Handy

## Benutzung

`index.html` im Browser öffnen oder über GitHub Pages bereitstellen. Ohne Server werden die Daten im `localStorage` des Browsers gespeichert (nur auf diesem Gerät). Als claude.ai-Artifact läuft dieselbe Datei mit gemeinsamer Online-Datenbank.

## Lizenz

MIT
