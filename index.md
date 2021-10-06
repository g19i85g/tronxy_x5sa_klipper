# Tronxy X5SA-500 Pro V9 Board Klipper umbau

## Teile Liste
- Raspberry Pi
- Netzteil für den Raspberry Pi
- USB Kabel
- SD Karte

## FluiddPi installieren
[Anleitung von FluiddPI](https://docs.fluidd.xyz/installation/fluiddpi)

## FluiddPi konfigurieren
1. SD Karte in den Raspberry Pi stecken
1. Raspberry Pi mit Storm versorgen und warten bis er hochgefahren ist
1. mit SSH auf dem Pi eingloggen Benutzername ist `pi` und das Passwort ist `raspberry`
1. password ändern `passwd`
1. als root einloggen `sudo -i`
1. Pakeht Listen updaten `apt update`
1. System upgraden `apt dist-upgrade -y`
1. http://fluiddpi.local aufrufen
1. printer.cfg hochladen
![Bild mit den Schritten zum Datei hochladen](/bilder/fluidd-config-hochladen.png)
1. Klipper neu starten
![Bild Klipper neu starten](/bilder/fluidd-klipper-neustarten.png)
1. Alles aktualisieren
![Bild Klipper neu starten](/bilder/fluidd-alles-aktualisieren.png)
