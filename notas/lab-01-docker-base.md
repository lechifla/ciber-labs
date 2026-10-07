# Lab 01: Contenedor Base con Alpine y Herramientas de Seguridad

## Descripción
Creación de un entorno contenerizado ligero basado en Alpine Linux (lpine:latest) para prácticas de ciberseguridad y análisis de redes.

## Herramientas Instaladas
- **Alpine Package Keeper (apk)**
- **curl**: Transferencia de datos mediante URLs.
- **nmap**: Escaneo de redes y auditoría de seguridad (Versión 7.99 verificada).
- **iputils**: Utilidades de red básicas (ping, etc.).

## Comandos Clave Aprendidos
- docker build -t ciber-alpine .: Construcción de la imagen local.
- docker run --rm ciber-alpine: Ejecución y prueba automática.
- docker run --rm -it ciber-alpine sh: Acceso interactivo a la terminal del contenedor.
