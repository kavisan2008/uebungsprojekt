# Tag 4 – Docker Projekt

## Projektbeschreibung
Dieses Projekt zeigt eine einfache Website, die mit Docker gebaut wurde.
Das Image wurde erstellt und in GitHub Container Registry (ghcr.io) gepusht.
Die Anwendung kann mit Docker Compose gestartet werden.
Das Projekt dient als Beispiel für Deployment mit Docker.
Die Website läuft auf Port 8088.

---

## Starten der Anwendung

git clone https://github.com/kavisan2008/uebungsprojekt
cd uebungsprojekt
docker compose -f docker-compose/docker-compose.yml up -d

Website öffnen:
http://localhost:8088

---

## Stoppen der Anwendung

docker compose -f docker-compose/docker-compose.yml down
