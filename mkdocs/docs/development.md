# Themeentwicklung

## Sprachdateien
- Erzeuge mit `make make-pot` ein neues Template-File
- Öffne `languages/de_DE.po` mit PoEdit
- Gehe dort auf *Katalog -> Aus POT-Datei aktualisieren*
- Erstelle die Übersetzungen
- Klicke auf *Speichern*

## Dokumentation
- Starte `make mkdocs-serve` *mkdocs*
- Die Dokumentation siehst Du unter localhost:
- Bearbeite die Dokumentation unter *mkdocs/docs*
- Baue die Dokumentation mit `make mkdocs-build`

## CSS
- ``npm run watch``, um css zu kompilieren und eine Source-Map zu erhalten
- Dateien befinden sich im Ordner *sass*

## Blöcke
- ``npm run start``, um den Watcher für JS-Files zu starten
- Dateien befinden sich im Ordner *src*

### Neue Block-Vorlage hinzufügen
Lege dazu eine neue Datei im Verzeichnis *functions/block-patterns/seiten* an.
Fertig.

## Publishing
``make publish``

or
1. edit version in style.scss
1. git add . && git commit
1. git tag -a v0.1.9 -m "message"
1. edit release_notes.html
1 .git push --follow-tags
4. increment version in style.scss and add beta, nightly-build, etc.



