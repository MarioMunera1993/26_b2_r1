# Actividad 1 - Backend 2 (Miércoles)
**Nombre Completo:** Mario Alosno Munera Velez
**Institución:** Cesde

---

## 1. Instancia de Base de Datos
* **Enlace a la instancia:** [Prisma Studio - Base de Datos](https://console.prisma.io/cmliquj9500nlyhd2q763dvot/cmlirulmt006y4tfllveikoiy/cmlirulmt006w4tfl2obrd8rw/studio#table=students&schema=public&view=table?)

* **Configuración de Base de Datos en Prisma.io:**
![Configuración Base de Datos - URL y Usuario (sin contraseña)](01-prisma-bd-config.png)

* **Cadena de Conexión:**
```
postgresql://usuario:****@db.prisma.io:5432/postgres?sslmode=require
```
*(URL y usuario visibles, contraseña oculta por seguridad)*

---

## 2. Conexión desde Spring Boot
![Log de Conexión Exitosa en Spring Boot](02-spring-boot-connection-log.png)

---

## 3. Pruebas de la API (CRUD)

### [POST] Crear Registro
*Captura de la solicitud (Request) y la respuesta (Response) en Postman/Insomnia:*
![POST Request](03-api-post-request.png)
![POST Response](04-api-post-response.png)
### [GET] Obtener Todos (All)
![GET All Request](05-api-getall-request.png)
![GET All Response](06-api-getall-response.png)
### [GET] Obtener por ID
![GET by ID Request](07-api-getbyid-request.png)
![GET by ID Response](07-api-getbyid-response.png)

### [GET] Obtener por Email
![GET by Email Request](08-api-getbyemail-request.png)
![GET by Email Response](09-api-getbyemail-response.png)
### [PUT] Actualizar Registro
![PUT Request](10-api-put-request.png)
![PUT Response](11-api-put-response.png)
### [DELETE] Eliminar Registro
![DELETE Request](12-api-delete-request.png)
![DELETE Response](13-api-delete-response.png)
---

## 4. Pruebas Internas del Proyecto
![Resultados de Pruebas Internas](14-internal-tests-results.png)

> **Estado final:** Todas las pruebas pasaron exitosamente.

---
*Este repositorio es un fork del proyecto original para la asignatura de Backend 2.*