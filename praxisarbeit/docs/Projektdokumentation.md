# Projekt Dokumentation

[[_TOC_]]

## Lösungsdesign
Anhand der Analyse wurde folgendes Lösungsdesign entworfen.

### Aufruf der Skripte

Skript 1: User create skript

        vagrant@vagrant:~$ ./usercreate.sh NAME_OF_FILE.txt
        
        
Skript 2: Backup create skript

        vagrant@vagrant:~$ ./backupcreate.sh

### Ablauf der Automation

Skript 1: User create skript

![image](img/skript1_ad.png)

Skript 2: Backup create skript

![image](img/skript2_ad.png)

### Konfigurationsdateien

TODO: Definieren sie welche Parameter in welchen Konfigurationsdateien gespeichert werden.

Skript 2: 

Groupname-Config: Im config-file sind pro Zeile Groupnames definiert, welche im Skript verwendet werden

Settings-Config: in diesem config-file sind filename, directory, time-of-delete und anzahl archives definiert


## Abgrenzungen zum Lösungsdesign

TODO: Nachdem das Programm verwirklicht wurde, hier die Unterschiede von der Implementation zum Lösungsdesign beschreiben (was wurde anders gemacht, was wurde nicht gemacht, was wurde zusaetzlich gemacht)
