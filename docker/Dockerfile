# Usamos una imagen ligera de Alpine Linux (nuestra "nave espacial" ligera de pruebas)
FROM alpine:latest

# Instalamos herramientas básicas de red y seguridad para prácticas
RUN apk update && apk add --no-cache curl nmap iputils

# Mensaje de bienvenida al contenedor del laboratorio
CMD ["echo", "¡Bienvenido al contenedor de pruebas de ciber-labs! Entorno seguro activo."]
