# Tag 4 – Docker Projekt

## Projektbeschreibung
Dieses Projekt ist eine einfache Webanwendung mit eigenem Docker Image.
Die Website enthält HTML, Styling und ein Bild (Logo).
Das Image wurde mit Docker erstellt und auf GitHub Container Registry (ghcr.io) gepusht.
Die Anwendung kann mit Docker Compose gestartet werden.
Damit kann die Lehrperson das Projekt einfach lokal ausführen.

---

## Installation (für Lehrperson)

1. Repository klonen:

git clone https://github.com/kavisan2008/uebungsprojekt.git

2. In Projektordner wechseln:

cd uebungsprojekt

3. Container starten:

docker compose -f docker-compose/docker-compose.yml up -d

4. Website öffnen:

http://localhost:8088

---

## Docker Image

Image befindet sich auf:

ghcr.io/kavisan2008/tag4-web:v1
