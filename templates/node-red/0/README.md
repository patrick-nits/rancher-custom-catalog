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
1. Folgende Url aufrufen ** mariadb.[team].rancher.hackathon-handwerk.de**
2. Im Anmeldefenster folgende Einträge machen
..* Datenbank System: **MySQL**
..* Server: **db** oder **mariadb**
..* Benutzer: siehe eingabe unter **Benutzer**
..* Passwort: siehe eingabe unter **Passwort**
..* Datenbank: siehe eingabe unter **Datenbank** (Standard: **hackathon-handwerk**)
3. Auf **login** klicken.

# Verwendung von AdminMongo
1. Folgende Url aufrufen **mongodb.[team].rancher.hackathon-handwerk.de**
2. Es erscheint eine Eingabemaske mit **Connection name**, **Connection string** und **Action**
3. Bei **Connection name** ein beliebigen Namen eingaben.
4. Bei **Connection string** folgende Eingabe machen, eckige Klammern müssen entfernt werden.
..* mongodb://[Benutzer]:[Passwort]@mongodb:27017/[Datenbank]
..* Benutzer: siehe eingabe unter **Benutzer**
..* Passwort: siehe eingabe unter **Passwort**
..* Datenbank: siehe eingabe unter **Datenbank** (Standard: **hackathon-handwerk**)
5. Auf **Add connection** klicken.