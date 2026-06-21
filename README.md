# Proyecto Capstone — Certificación IBM Full Stack Software Developer

> **Nota de transparencia:** este proyecto parte de una base de código proporcionada por el programa de certificación IBM Full Stack Software Developer (Coursera). Sobre esa base, implementé las funcionalidades requeridas por el programa.

## Descripción

Aplicación de concesionario de autos (dealership) construida como proyecto final de la certificación, con una arquitectura de microservicios: una aplicación principal en Django, un microservicio en Node.js/Express conectado a MongoDB, y un frontend dinámico en React.

## Stack tecnológico

- **Backend principal:** Django (Python)
- **Microservicio:** Node.js, Express
- **Base de datos:** MongoDB
- **Frontend:** React
- **Contenedores:** Docker
- **Despliegue:** IBM Cloud Code Engine

## Qué implementé

- Modelos y servicios proxy en Django para la gestión de marcas y modelos de auto.
- Componentes dinámicos en React para listado, filtrado por estado y visualización de detalle de concesionarios.
- Endpoints REST sobre Node.js/Express y MongoDB para la gestión de reseñas.
- Containerización con Docker del microservicio de Node.js/Express.
- Despliegue del servicio en IBM Cloud Code Engine.
