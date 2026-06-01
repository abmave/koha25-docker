# Proyecto KOHA 25 Docker

Objetivo:
Implementar una instalación limpia de KOHA 25 en Docker para la Biblioteca Municipal de Lima.

Fases:
1. Instalación limpia KOHA 25
2. Validación funcional
3. Restauración de backup
4. Migración de datos
5. Pruebas
6. Paso a producción
## Bitácora

### 2026-05-29

- Instalado Docker Desktop.
- Habilitada integración WSL2.
- Ubuntu configurado correctamente.
- Creada estructura inicial del proyecto:
  - data/
  - nginx/
  - README.md
  - .env
- VS Code conectado al entorno WSL.
### Verificación del entorno

- Docker Engine 29.4.3 operativo.
- Docker Compose v2.51.4 operativo.
- Git 2.53.0 operativo.
- VS Code integrado con WSL2.
- Docker Desktop funcionando correctamente.
### 2026-05-29

- Configurado archivo .gitignore.
- Excluidos datos persistentes del versionado.
- Repositorio preparado para desarrollo con Docker.
### Configuración Git

- Git inicializado.
- Usuario global configurado.
- Correo global configurado.
- Primer commit realizado.
- ### 2026-05-29

#### Control de versiones

- Repositorio Git inicializado.
- Archivo .gitignore configurado.
- Usuario Git configurado.
- Correo Git configurado.
- Primer commit realizado.
### Infraestructura Base Desplegada

Servicios operativos:

- MariaDB 10.11
- Memcached
- Elasticsearch 8.13.4

Puertos:

- MariaDB: 3307
- Elasticsearch: 9200

Estado:

- Contenedores desplegados correctamente mediante Docker Compose.
### Infraestructura Base Validada

Fecha: 2026-06-01

Servicios operativos:

- MariaDB 10.11
- Memcached
- Elasticsearch 8.13.4

Validaciones:

- MariaDB: ready for connections.
- Elasticsearch: API accesible en http://localhost:9200.
- Docker Compose operativo.
- Infraestructura versionada en Git.
### Estado del laboratorio

Infraestructura base desplegada:

- MariaDB 10.11
- Memcached
- Elasticsearch 8.13.4

Repositorio Git:

- Commit inicial.
- Commit infraestructura base.

Próxima fase:

- Instalación Koha 25.
## Estado actual

Infraestructura desplegada:

- MariaDB 10.11
- Memcached
- Elasticsearch 8.13.4

Docker:

- Red koha25-docker_default creada.
- Volúmenes persistentes preparados.

Repositorio Git:

- Commit inicial.
- Commit infraestructura base.

Próxima fase:

- Despliegue de Koha 25.