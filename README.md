# Installationsschritte des Projekte


## Klonen des Repositorie

1. Zuerst muss man das Fenster aufmachen wo man den SSH Link findet, den findet man im ```code``` Icon 
2. Man Kopiert den gegebenen SSH URL und öffnest den Explorer (Dateien) und machst einen neuen Ordner und benennen ihn einen passenden Namen. 
3. Du gehst in den Ordnern rein und gibst cmd in die Leiste, die dir sagt, wo du gerade bist in den Dateien. Dies öffnet die Kommandozeile.
4. Hier gibst du ```git clone``` und dann den geklonten SSH URL. Das kopiert die Datei in den neu gemachten Ordner.

## Installation der notwendigen Pakete

Um die Anleitunf für die richtige instalation muss man auf [Docs.Doker](https://docs.docker.com/guides/language/nodejs/containerize/) die Anleitung befolgen.

Geben sie in die Komandozeile ```docker init``` ein.
Es sollten Fragen auftauchen, die so aussenhen:

```? What application platform does your project use? Node```
```? What version of Node do you want to use? 18.0.0```
```? Which package manager do you want to use? npm```
```? What command do you want to use to start the app? node src/index.js```
```? What port does your server listen on? 3000```

Nachdem Man die Fragen beantwortet hat sollen die Dateien Dockfile, 
.dockignore und compose.yaml sollen in dem Docker-Nodejs-Sample datei sein.

## Docker-Konfiguration und -Installation

Um Docker Desktop herunterzuladen, gehe auf die Website Docker Docs. Wähle auf der linken Seite ["Docker Desktop"](https://docs.docker.com/manuals/) aus, klicke dann auf "Install", wähle dein Betriebssystem aus und entscheide abschließend, welche Version du herunterladen möchtest.

## Starten der Applikation in einem Docker-Container

Um die Applikation zu starten, gib in der Kommandozeile den Befehl ```docker compose up --build``` ein. Wenn keine Fehler auftreten, ist alles korrekt eingerichtet. Anschließend kannst du Docker Desktop öffnen, um die Applikation zu verwalten. Zum Stoppen der Applikation verwende den Befehl ```docker compose down``` in der Kommandozeile.

<img src= Abschlussaufgabe.png>