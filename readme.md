## Installion et lancement du serveur
```
cd project

git clone https://github.com/Myogamevideo/starter_sf6.git nom_du_projet

docker build --build-arg PROJECT_NAME=nom_du_projet

docker-compose up -d
```

## Access bash
```
docker exec -it php8-sf6 bash
```

## Start yarn :
```
docker exec -it php8-sf6 bash

yarn watch
```

## Access 
- PHPMyAdmin : http://localhost:8080/
- Website : http://localhost:9000/

DATABASE_URL="mysql://root:password@localhost:3306/cours_symfony?serverVersion=8&charset=utf8mb4"

## IPConfig
Open powershell

```
ipconfig
```

> Adresse IPv4 : 192.168.130.149

# Mailer
```
docker exec -it php8-sf6 bash

cd nom_du_projet

symfony open:local:webmail
```

> Opened: http://127.0.0.1:58275
