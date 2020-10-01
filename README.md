# TPESGI

Pour installer/démarrer le projet, dans un terminal exécuter la commande :
```bash
make up
```
OU
```bash
docker-compose up -d
```

Pour arrêter l'exécution :
```bash
make down
```
OU
```bash
docker-compose down
```

Note : faire `cd app` puis `composer install` à l'intérieur du conteneur (`docker exec -it tpesgi_app_1 sh` pour y accéder)
