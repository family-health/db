
# Imagen de docker de mysql

1) clone el repositorio


```bash
  git clone https://github.com/family-health/db.git

  cd db
```
    
2) Configure sus credenciales de la base de datos en el archivo **.env**
```bash
MYSQL_ROOT_PASSWORD=password
MYSQL_USER=user
MYSQL_PASSWORD=password
```

3) Levante el servicio con
```bash
  docker-compose up -d
```

4) Para bajar el servicio
```bash
  docker-compose down
```
## Para poder gestionar la base de datos en **phpmyadmin** escriba en su navegador

```bash
  http://localhost:8080/
```

Ingresa las credenciales que configuraste y listo!
