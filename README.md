# Catalog_Workshop

# Shopping Catalog Microservice

Este repositorio contiene el código fuente de un microservicio de catálogo de productos para una tienda online, desarrollado con Java Spring Boot. El microservicio permite gestionar operaciones relacionadas con productos, como agregar nuevos productos, obtener información detallada de productos, actualizar detalles de productos y eliminar productos.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Características](#características)
- [Arquitectura](#arquitectura)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Requisitos Previos](#requisitos-previos)
- [Instalación](#instalación)
- [API Endpoints](#api-endpoints)

## Descripción

El microservicio de catálogo de productos permite administrar productos en una tienda online. Proporciona endpoints RESTful para agregar nuevos productos, obtener información detallada de productos, actualizar detalles de productos y eliminar productos de forma segura.

## Características

- Agregar nuevos productos
- Obtener información detallada de productos
- Actualizar detalles de productos
- Eliminar productos
- Búsqueda de productos por categoría, precio, etc.
- Validación de datos de productos

## Arquitectura

Este microservicio sigue una arquitectura de microservicios basada en Spring Boot. Utiliza una base de datos relacional para almacenar los datos de productos y proporciona una API RESTful para interactuar con los productos.

## Tecnologías Utilizadas

- Java 11
- Spring Boot
- Spring Data JPA
- H2 Database (para pruebas y desarrollo)
- MySQL (para producción)
- Maven

## Requisitos Previos

- JDK 11 o superior
- Maven 3.6.0 o superior
- MySQL (para entorno de producción)

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/nurvoz/Catalog_microservice.git
    ```
2. Navega al directorio del proyecto:
    ```bash
    cd Catalog_microservice
    ```
3. Compila y ejecuta el microservicio:
    ```bash
    mvn clean install
    mvn spring-boot:run
    ```
