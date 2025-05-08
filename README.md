# Introducci¢n a Docker ??

Este repositorio contiene materiales y ejemplos pr cticos para aprender los fundamentos de Docker, una plataforma para desarrollar, enviar y ejecutar aplicaciones dentro de contenedores.

## ¨Qu‚ es Docker?

Docker es una herramienta que permite empaquetar una aplicaci¢n y todas sus dependencias en un contenedor, garantizando que se ejecutar  de la misma forma sin importar el entorno.

## ¨Por qu‚ usar Docker?

- ? Aislamiento de aplicaciones
- ?? Facilita la configuraci¢n y despliegue
- ?? Ideal para pruebas y entornos de desarrollo
- ?? Portabilidad entre entornos (local, staging, producci¢n)

## Contenido

- `01-hello-docker/`: Primeros pasos con Docker (Hello World)
- `02-dockerfile/`: Creaci¢n de im genes personalizadas usando Dockerfile
- `03-volumes/`: Uso de vol£menes para persistencia de datos
- `04-networks/`: Comunicaci¢n entre contenedores
- `05-docker-compose/`: Orquestaci¢n b sica con Docker Compose

## Requisitos

- Tener instalado [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- (Opcional) Tener instalado [Docker Compose](https://docs.docker.com/compose/install/), aunque ya viene incluido en versiones recientes

## Comandos b sicos

```bash
# Ver versi¢n de Docker
docker --version

# Descargar imagen desde Docker Hub
docker pull nombre-de-la-imagen

# Ejecutar contenedor
docker run nombre-de-la-imagen

# Listar contenedores
docker ps -a

# Detener contenedor
docker stop nombre-del-contenedor

# Eliminar contenedor
docker rm nombre-del-contenedor
