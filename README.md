# Practica_1_Backend
## Autor
Este proyecto fue desarrollado por **Oscar Joel Choque Flores**
## Practica 1 de la materia TAW-251 Desarrollo Web Backend
El objetivo principal es implementar un sistema backend utilizando **Spring Boot**, que permita gestionar información de estudiantes a través de una API REST.

## Características
- **Gestión de estudiantes**: Permite realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) sobre los datos de los estudiantes.
- **Arquitectura REST**: Implementación de controladores REST para manejar solicitudes HTTP.
- **Inyección de dependencias**: Uso de Spring para gestionar servicios y controladores.
- **Configuración personalizada**: El servidor está configurado para ejecutarse en el puerto `8082`.

## Endpoints principales

- `GET /api/estudiantes`: Obtiene la lista de todos los estudiantes.
- `POST /api/estudiantes`: Crea un nuevo estudiante.
- `GET /api/estudiantes/{id}`: Obtiene un estudiante por su ID.
- `PUT /api/estudiantes/{id}`: Actualiza la información de un estudiante.
- `DELETE /api/estudiantes/{id}`: Elimina un estudiante.

## Requisitos previos

- **Java 24**.
- **Maven** para la gestión de dependencias.
- **Spring Boot** como framework principal.
