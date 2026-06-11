# Praenataltermin

Statische HTML-Seite (browser-only) zur Berechnung des möglichen Untersuchungszeitraums in der Schwangerschaft.

## Funktion

- **Eingabemodus** wählbar: Errechneter Geburtstermin (ET) oder Letzte Periode (LMP)
- **Leistung** wählbar: Ersttrimester-Untersuchung (12+2 bis 13+6 SSW) oder Organ-Screening (21+2 bis 23+6 SSW)
- **Ergebnis**: Konkreter Datumszeitraum (frühester / spätester Termin) für die gewählte Untersuchung
- Automatische Neuberechnung bei jeder Änderung (kein Button nötig)
- Fußnote zeigt den jeweils anderen Wert (bei ET-Eingabe → LMP, bei LMP-Eingabe → berechneter ET)

## Verwendung

Einfach `index.html` im Browser öffnen. Keine Abhängigkeiten, kein Server, keine Internetverbindung nötig.

## Technik

Reines HTML + CSS + JavaScript (ES6), keine Frameworks oder externen Ressourcen.
