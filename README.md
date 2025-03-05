<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# STORE LAUNCHER - MICROSERVICIOS

## DESARROLLO

1. Clonar el repositorio
2. Crear un `.env` basado en `.env.sample`
3. Ejecutar el comando `git submodule update --init --recursive`
4. Ejecutar el comando `docker compose up --build`

> [!INFO]
> Para el ambiente local, es necesario usar hookdeck
> `hookdeck listen [PORT] [DESTINATION]`

## PRODUCCION

1. Clonar el repositorio
2. Crear un .env basado en el .env.sample
3. Ejecutar el comando

   ```bash
    docker compose -f docker-compose.prod.yaml build
   ```
