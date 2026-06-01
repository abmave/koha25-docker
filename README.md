# Proyecto KOHA 25 Docker

Objetivo:
Migrar KOHA 21.11 a KOHA 25 usando Docker.

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