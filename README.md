# AniWorld Listen-Sicherung fuer Firefox

Diese Firefox-Erweiterung sichert deine **Watchlist** und die Liste **Abonniert** auf AniWorld (`aniworld.to` und `aniworld.cc`) lokal. Sie speichert keine Zugangsdaten und uebermittelt keine Daten an Dritte.

## Installation

1. Firefox oeffnen und `about:debugging#/runtime/this-firefox` aufrufen.
2. Auf **Temporeres Add-on laden...** klicken.
3. Die Datei `manifest.json` aus diesem Ordner auswaehlen.

Die temporaere Installation gilt bis zum Neustart von Firefox. Die mitgelieferte `aniworld-listen-sicherung.xpi` ist nicht signiert und kann deshalb in normalem Firefox nicht direkt installiert werden. Fuer eine dauerhafte private Installation muss die Erweiterung ueber Mozilla signiert werden.

## Sicherung erstellen

1. Bei AniWorld anmelden.
2. Die Seite deiner Watchlist oeffnen. Die Erweiterung erkennt sie und sichert sie automatisch.
3. Die Seite **Abonniert** oeffnen. Auch diese Liste wird automatisch gesichert.

Die Datei liegt danach unter `Downloads/AniWorld-Sicherung/aniworld-listen.json`. Bei jeder Aktualisierung wird sie ersetzt, sodass stets eine aktuelle Kopie vorhanden ist. Ueber das Erweiterungs-Symbol kann die aktuell gespeicherte Kopie jederzeit erneut heruntergeladen werden.

Die JSON-Datei enthaelt Titel, AniWorld-URL und gegebenenfalls das Cover-Bild jeder Serie. Sie enthaelt keine Cookies, Passwoerter oder Streamingdaten.
"# aniworld-sync" 
