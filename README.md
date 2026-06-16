# Wasap 3.0 - Proyecto de Microservicios

## Descripción

Wasap 3.0 es una aplicación desarrollada bajo una arquitectura basada en microservicios. La solución está compuesta por un Frontend, un Backend For Frontend (BFF) y dos microservicios especializados para la gestión de usuarios y mensajes.

El objetivo del proyecto es demostrar la implementación de una arquitectura distribuida utilizando Spring Boot, persistencia de datos, documentación de APIs y pruebas automatizadas.

## Arquitectura

La solución se encuentra compuesta por los siguientes componentes:

* Frontend
* Backend For Frontend (BFF)
* Microservicio de Usuarios
* Microservicio de Mensajes

```text
Frontend
    |
    v
BFF (8080)
    |
+---+---+
|       |
v       v
MSUser  MSMessages
(8081)  (8082)
 |         |
 v         v
H2 DB    H2 DB
```

## Tecnologías Utilizadas

### Backend

* Java 17
* Spring Boot
* Spring Data JPA
* H2 Database
* Swagger/OpenAPI

### Frontend

* HTML5
* CSS3
* JavaScript
* Node.js

### Testing

* JUnit 5
* Spring Boot Test
* JaCoCo

## Cobertura de Pruebas

Los reportes de cobertura fueron generados utilizando JaCoCo.

| Componente  | Cobertura |
| ----------- | --------- |
| MS User     | 78%       |
| MS Messages | 70%       |
| BFF         | 80%       |

## Repositorios

### Repositorio Principal

Contiene la documentación general del proyecto, diagramas de arquitectura, evidencias e informes técnicos.

### Repositorio Frontend

Contiene la interfaz de usuario de la aplicación.

### Repositorio Backend For Frontend

Centraliza las peticiones provenientes del frontend y coordina la comunicación entre los microservicios.

### Repositorio Microservio de Usuarios

Gestiona la información de usuarios y su persistencia.

### Repositorio Microservio de Mensajes

Gestiona la información de mensajes y su persistencia.

## Documentación

Este repositorio contiene:

* Informe de la Evaluación 3.
* Diagrama de arquitectura.
* Evidencias de Swagger.
* Evidencias de persistencia H2.
* Evidencias de pruebas unitarias.
* Reportes de cobertura JaCoCo.
* Archivo repositorios.txt.

