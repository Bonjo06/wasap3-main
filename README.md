# Wasap 3 - Documentación General

## Descripción

Wasap 3 es una solución desarrollada bajo una arquitectura de microservicios compuesta por un Frontend, un Backend For Frontend (BFF) y dos microservicios especializados para la gestión de usuarios y mensajes.

## Arquitectura

Frontend → BFF → Microservicio Usuarios / Microservicio Mensajes

* Frontend: Interfaz de usuario de la aplicación.
* BFF: Orquesta las llamadas a los microservicios y centraliza el acceso desde el frontend.
* MS User: Gestiona usuarios y perfiles.
* MS Messages: Gestiona mensajes y su persistencia.

## Tecnologías Utilizadas

* Java 17
* Spring Boot
* Spring Data JPA
* H2 Database
* Swagger / OpenAPI
* JUnit
* JaCoCo
* React

## Cobertura de Pruebas

* MS User: 78%
* MS Messages: 70%
* BFF: 80%

## Documentación

Este repositorio contiene:

* Diagrama de arquitectura.
* Evidencias de persistencia.
* Evidencias de Swagger.
* Evidencias de pruebas unitarias.
* Reportes de cobertura JaCoCo.
* Archivo repositorios.txt.

