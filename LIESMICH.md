# Tulpenstrasse 15, Sindelfingen, Wohnung Nr. 2

## Was in diesem Ordner liegt

    index.html          das Expose
    bilder/             18 Bilddateien, vom Expose eingebunden
    unterlagen/         11 PDF, ueber die Downloadkarten verlinkt

Alle drei muessen beieinander bleiben. Fehlt "bilder", zeigt die Seite
keine Fotos. Fehlt "unterlagen", laufen die Downloads ins Leere.

## Hochladen

Ein eigenes Repository fuer diese Wohnung anlegen. Dann auf
"Add file", danach "Upload files", und in das Fenster alles drei
zusammen ziehen:

    index.html
    bilder            (der ganze Ordner)
    unterlagen        (der ganze Ordner)

Wichtig: nicht den Ordner "Wohnung-2" hochladen, sondern seinen Inhalt.
Die index.html muss im Repository ganz oben liegen.

## Pages einschalten

Settings, dann Pages. Bei Source "Deploy from a branch" waehlen,
Branch `main`, Ordner `/ (root)`. Speichern. Der erste Aufbau dauert
ein bis zwei Minuten, danach steht die Adresse oben auf der Seite.

## Groessen

Keine Datei ist groesser als rund 3,6 MB. Der Weblader von GitHub nimmt
einzelne Dateien bis 25 MB, das ist also unproblematisch.
Die Seite selbst laedt beim Besucher mit rund 2,8 MB, davon 2,65 MB Bilder,
die nach dem Text nachgeladen werden.

## Nicht enthalten, mit Absicht

Das Restnutzungsdauergutachten liegt nicht in "unterlagen". Es enthaelt
personenbezogene Daten. Auf GitHub Pages ist jede Datei im Repository
oeffentlich abrufbar, auch wenn sie auf der Seite nicht verlinkt ist.
Im Expose steht deshalb, dass Grundbuchauszug, Restnutzungsdauergutachten
und Mietvertrag bei ernsthaftem Kaufinteresse nachgereicht werden.
Dasselbe gilt fuer den Mietvertrag und den Grundbuchauszug.

## Falls ein Ordner anders heissen soll

In der index.html steht im Skript genau eine Zeile:

    var DOKBASE='unterlagen/';

Nur diese aendern. Der Schraegstrich am Ende muss bleiben.
Der Bildordner ist in den Bildpfaden hinterlegt und heisst "bilder".

## Hinweis zum Oeffnen von der Festplatte

Oeffnest du die index.html per Doppelklick, sperrt der Browser bei
manchen Einstellungen den Zugriff auf Nachbarordner. Die Seite erscheint,
die Downloads funktionieren dort aber nicht immer. Auf der
veroeffentlichten Seite laeuft alles.
