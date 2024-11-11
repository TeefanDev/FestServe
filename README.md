# FestServe

Eine mobile App für Bedienungen in localen/kleinen Festen, um Bedienungen die Arbeit zu erleichtern.

## Wissenswert für Verwendung

- Vorerst wird die App ohne Beachtung für IOS verwendung Erstellt.

- Datenbank und externe Speicherung sowie Verbinung untereinander wird erst nach dem Aufbau der Grundstruktur durchgeführt.

- Zur Ausführung wird entweder flutter und android studio auf dem eigenen rechner benötigt oder die apk datei muss auf einem mobilgerät installiert werden.
  - die apk datei wird nur für große testversionen erstellt und ist für den anfang noch überhaupt nicht vorhanden.

## Ziel

Eine App für jede Bedienung, welche verschiedene Bestellungen aufnehmen können und diese landen direkt auf einem Bildschirm bei der Essensausgabe und bei der Getränkeausgabe.

Wichtig ist, dass die Rechnungen gespeichert werden und von einem admin gesammelt aufgerufen werden können.

Als Aufbau wird ein Raspberry Pi verwendet, welcher die datenbank laufen lässt und eine locale Kopie der Rechnungen speicher. Ebenfalls spannt dieser mit der hilfe von Versstärkern ein Wlan Netzwerk auf, über welches die Bedienungen sich verbinden können um sich dann mit der Datenbank zu verbinden und dann die Bestellungen Automatisch an die Ausgabe Geräte gelangt.

## Befehle

- flutter doctor

- flutter -version

- flutter create festserve

- flutter run

## Versionierung

### Version 0.0.1

- Erstellung des projekts.

- Erstellung der Windows für die App.


© Stefan Ptacek | November 2024
