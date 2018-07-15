# NodeRED Hackathon Handwerk Stack
Speziell für den Hackathon Handwerk konzipiert Stack, aufbauend auf NodeRED und erweitert um Datenbanken und Services.

Folgende Dienste sind nach erfolgreichem Start dieser Applikationen verfügbar:

* NodeRED unter [team].rancher.hackathon-handwerk.de
* Adminer zur Verwaltung einer MariaDB (MySQL) unter mariadb.[team].rancher.hackathon-handwerk.de
* AdminMongo zur Verwaltung einer MongoDB unter mongodb.[team].rancher.hackathon-handwerk.de

**[team]** bezieht sich dabei auf die Eingabe im Feld "Team".

# Verwendung der Datenbanken in NodeRED
* MariaDB / MySQL ist unter dem Namen **mariadb** erreichbar.
* Mongodb ist unter dem Namen **mongodb** erreichbar.
..* "Collections" sind Listen von Dokumenten in MongoDB und können beliebig erstellt werden.
* Benutzernamen, Passwörter und Datenbanken beziehen sich auf die Eingaben in den entsprechenden Feldern.

# Verwendung von Adminer
1. Folgende Url aufrufen ** mariadb.[team].rancher.hackathon-handwerk.de
2. Im Anmeldefenster folgende Einträge machen
..* Datenbank System: **MySQL**
..* Server: **db** oder **mariadb**
..* Benutzer: siehe eingabe unter **Benutzer**
..* Passwort: siehe eingabe unter **Passwort**
..* Datenbank: siehe eingabe unter **Datenbank** (Standard: **hackathon-handwerk**)

# Verwendung von AdminMongo