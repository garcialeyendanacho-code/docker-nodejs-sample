# Docker Node.js Sample

## Installation

### 1. Repository klonen

```bash
git clone https://github.com/garcialeyendanacho-code/docker-nodejs-sample.git
cd docker-nodejs-sample
```

### 2. Notwendige Pakete installieren

```bash
npm install
```

### 3. Docker installieren

Docker Desktop installieren und anschliessend Docker Desktop starten.

### 4. Docker-Konfiguration erstellen

Dockerfile und die benötigten Docker-Konfigurationsdateien im Root-Verzeichnis des Projekts erstellen.

### 5. Docker-Image erstellen

```bash
docker build -t docker-nodejs-sample .
```

### 6. Docker-Container starten

```bash
docker compose up --build
```

```bash
docker run -p 3000:3000 docker-nodejs-sample
```

### 7. Applikation öffnen

Die Anwendung ist anschliessend unter folgender Adresse erreichbar:

```text
http://localhost:3000
```

### 8. Docker-Container überprüfen

Laufende Container anzeigen:

```bash
docker ps
```

### 9. Änderungen mit Git speichern

```bash
git add .
git commit -m "Docker und README hinzugefügt"
```

### 10. Änderungen auf GitHub übertragen

```bash
git push
```
