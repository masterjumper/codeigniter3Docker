# Proyecto de Contenedores con Docker

Este proyecto consta de tres contenedores Docker que trabajan en red bajo el nombre de red "mynetwork". Cada contenedor tiene un propósito específico para crear un entorno de desarrollo local para una aplicación web basada en Codeigniter 3.

## Contenedores

### 1. Contenedor Codeigniter 3

El primer contenedor aloja una instancia del framework Codeigniter 3. Este contenedor proporciona el entorno de ejecución necesario para tu aplicación web.

### 2. Contenedor PhpMyAdmin

El segundo contenedor contiene PhpMyAdmin, una interfaz web para administrar el sistema de gestión de bases de datos MySQL. Puedes acceder a PhpMyAdmin para gestionar la base de datos de manera gráfica.

### 3. Contenedor MySQL

El tercer contenedor alberga una instancia de MySQL, que actúa como la base de datos para tu aplicación. Puedes configurar y gestionar tu base de datos MySQL a través de este contenedor.

## Instrucciones de Uso

1. Clona este repositorio en tu máquina local.

```bash
git clone <URL_del_repositorio>
cd <nombre_del_directorio>
```

2. Ejecuta el docker-compose
```bash
docker compose up -d
```

3. Accede a la aplicación y PhpMyAdmin en tu navegador.

    Aplicación Codeigniter: http://localhost:8080/aplicacion/

    PhpMyAdmin: http://localhost:8081
