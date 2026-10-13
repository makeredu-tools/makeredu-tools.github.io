# MakerEdu Tools

Browser-Werkzeuge für den Making-Unterricht auf der Sekundarstufe: Beurteilung von Making-Prozessen und digitale Hilfsmittel für Lasercutter und 3D-Drucker.

**Startseite:** https://makeredu-tools.github.io

## Tools

### Beurteilung

| Tool | Beschreibung |
|---|---|
| [Beurteilungs-Generator](https://makeredu-tools.github.io/beurteilung/generator.html) | Indikatoren aus vier Kompetenzfeldern wählen und ein druckfertiges Beurteilungsblatt (PDF) für Selbst- und Fremdeinschätzung erstellen. Zusammenstellungen lassen sich als Link speichern und teilen. |
| [Lektions-Tracker](https://makeredu-tools.github.io/beurteilung/tracker.html) | Schüler:innen Lektion für Lektion beurteilen, den Verlauf über ein Projekt verfolgen und mit Boxplots und Verlaufsgrafiken auswerten. |

### Digitale Werkzeuge

| Tool | Beschreibung |
|---|---|
| [Scan-Digitizer](https://makeredu-tools.github.io/werkzeuge/scan-digitizer.html) | Flachbettscan einer Skizze laden, Massstab kalibrieren, Nullpunkt setzen, Koordinaten in mm ablesen und ein massstabgetreues PDF drucken. |
| [STL-Viewer](https://makeredu-tools.github.io/werkzeuge/stl-viewer.html) | STL-Datei öffnen und frei drehen, mit Dreiecksanzahl und Abmessungen in mm. Funktioniert auch auf dem Handy. |
| [STL zu SVG](https://makeredu-tools.github.io/werkzeuge/stl-zu-svg.html) | STL-Dateien in SVG-Aussenkonturen umwandeln und auf einer Platte anordnen, für Lasercutter oder Plotter. |

## Nutzung

- Alle Tools laufen direkt im Browser. Es ist keine Installation und kein Konto nötig.
- **Daten bleiben auf dem Gerät.** Dateien und Eingaben werden nicht hochgeladen. Der Tracker speichert im Browser (localStorage); für Sicherungen und den Wechsel auf ein anderes Gerät gibt es im Tab «Daten» einen JSON-Export und -Import.
- Jedes Tool ist eine einzelne HTML-Datei und kann heruntergeladen und lokal geöffnet werden. Schrift und PDF-Bibliothek werden dabei beim ersten Öffnen aus dem Internet geladen.

## Quellen

Die Kompetenzfelder und Indikatoren im Generator und im Tracker basieren auf:

> Ingold, S. & Maurer, B. (Hrsg.) (2024). *Making und Schule. Praxishandbuch für Schulentwicklung und Unterricht.* München: kopaed. Kapitel 3.2.1 «Vier Kompetenzfelder» und 5.6 «Making-Leistungen begutachten». Im Auftrag des Amts für Volksschule Thurgau. Lizenz: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de).

Die Texte wurden für die Tools angepasst und ergänzt.

## Lizenz

- **Tools (Code und Gestaltung):** © Raphael Fisch, MakerEdu Tools, unter [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.de). Schulen und Lehrpersonen dürfen die Tools frei nutzen, anpassen und weitergeben, mit Namensnennung, nicht kommerziell und unter derselben Lizenz.
- **Indikatortexte:** unter [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de) gemäss der oben genannten Quelle.

Details in [LICENSE](LICENSE). Für Nutzungen ausserhalb dieser Lizenz bitte über ein [Issue](https://github.com/makeredu-tools/makeredu-tools.github.io/issues) anfragen.

### Verwendete Komponenten

| Komponente | Verwendet in | Lizenz |
|---|---|---|
| [jsPDF](https://github.com/parallax/jsPDF) | Generator, Scan-Digitizer | MIT |
| [SheetJS](https://sheetjs.com) | Tracker | Apache 2.0 |
| [DM Sans](https://fonts.google.com/specimen/DM+Sans) (über Google Fonts) | alle Tools | SIL Open Font License 1.1 |

## Rückmeldungen

Fehler und Ideen gerne als [Issue](https://github.com/makeredu-tools/makeredu-tools.github.io/issues).
