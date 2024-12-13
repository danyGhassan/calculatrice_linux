## commande pour build
```
docker build -t calc .
```
## up docker-compose.yml
```
docker compose up 
```
## Pour modifier le port d'écoute 
```
docker run -e CALC_PORT=6767 -d calc
```