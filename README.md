# Airrohr-Cli
*Deine Airrohr Sensordaten im Terminal*

![alt text](https://github.com/ices-dev/airrohr-cli/blob/master/screenshots/airrohr-cli.png "Screenshot Debian Stretch")

### Beschreibung
Airrohr-Cli ist ein Bash Skript welches dir die Sensordaten eines Airrohrs im Terminal anzeigt.

Ein Airrohr ist ein [Selbstbau Feinstaubsensor](http://luftdaten.info/feinstaubsensor-bauen/) des OK Lab Stuttgart. Auf Luftdaten.info entstand so eine sich ständig aktualisierende [Feinstaub-Karte](http://deutschland.maps.luftdaten.info). Der Sensor misst zusätzlich Temperatur und Luftfeuchtigkeit. Die Sensordaten werden über die [Luftdaten.info](http://luftdaten.info) API ausgelesen. 
### Installation
Einfach das Skript aus dem Repo clonen und ausführen. Benötigt Python, curl, ansonsten keine besonderen Abhängigkeiten.
Getestet unter macOS und Debian Linux.
### Benutzung
Das Skript startet beim ersten Start oder mit der Option `-c` ein interaktives Menü bei dem die Karten-IDs des Sensors eingetragen werden.
### Konfiguration
Das Skript speichert seine Einstellungen in der Datei `~/.airrohr.conf`. Durch editieren der Datei kann die Ausgabe von Sensorwerten aus und eingeschaltet werden, das Trennzeichen geändert und die Farbe der Ausgabe angepasst werden.
