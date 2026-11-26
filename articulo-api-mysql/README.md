# TechLab - API de artículos

Alumno: Pablo De Lillo

Proyecto final de Backend Java. Permite crear, consultar, modificar y eliminar artículos de tecnología.

## Tecnologías y requisitos
Java 17, Spring Boot, Maven, JPA/Hibernate, MySQL y Postman.

## Cómo ejecutar
1. Crear la base con `database/crear_base.sql` en MySQL Workbench.
2. Desde la carpeta del proyecto, configurar el usuario y contraseña en PowerShell:
   ```powershell
   $env:DB_USER="root"
   $env:DB_PASSWORD="TU_CLAVE"
   mvn spring-boot:run
   ```
3. Importar `Articulo API MySQL.postman_collection.json` en Postman. La API usa el puerto 8080.

## Endpoints
| Método | Ruta |
|---|---|
| GET | /api/articulos |
| GET | /api/articulos/{id} |
| POST | /api/articulos |
| PUT | /api/articulos/{id} |
| DELETE | /api/articulos/{id} |
| GET | /api/articulos/buscar?nombre=mouse |

## Video
YouTube: pendiente de agregar el enlace de la grabación.
