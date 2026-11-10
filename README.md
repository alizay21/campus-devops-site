# Campus DevOps Site

Static HTML/CSS website served by Nginx and managed with Docker Compose.

## Run
```powershell
docker compose config
docker compose up -d --build
docker compose ps
```
Open http://localhost:8080

## Update
Edit the heading in `index.html`, then run:
```powershell
docker compose up -d --build
```

## Stop and remove
```powershell
docker compose stop
docker compose start
docker compose down
```
