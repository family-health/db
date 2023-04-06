<p align="center">
  <a href="https://www.docker.com/" target="blank"><img src="https://logopng.com.br/logos/docker-27.png" width="200" alt="Docker Logo" /></a>
</p>

# Imagen de docker de postgresql

1) clone el repositorio


```bash
  git clone https://github.com/family-health/db.git

  cd db
```
    
2) Configure sus credenciales de la base de datos en el archivo **.env**
```bash
POSTGRES_USER=postgres
POSTGRES_PASSWORD=password
POSTGRES_DB=family_health
```

3) Levante el servicio con
```bash
  docker-compose up -d
```

4) Para bajar el servicio
```bash
  docker-compose down
```
