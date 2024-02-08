# wordpress
Ejercicios para Docker:
Desplegar la imagen mediante comandos de docker, docker compose y kubernetes.

Investiga y elige un tema de WordPress existente o crea uno personalizado.
Modifica el tema según tus preferencias.
Crear un Dockerfile para WordPress:

Crea un Dockerfile que extienda la imagen oficial de WordPress.
Agrega instrucciones para copiar el tema personalizado en el directorio correcto de WordPress.
Construir la imagen de Docker:

Usa el comando docker build para construir la imagen de Docker.
Etiqueta la imagen según la convención adecuada.
Montar un volumen para los datos persistentes:

Crea un volumen de Docker para almacenar los datos de WordPress de forma persistente.
Modifica tu Dockerfile para que WordPress use este volumen para almacenar los datos.
Ejecutar un contenedor de WordPress:

Usa el comando docker run para ejecutar un contenedor de WordPress basado en la imagen que construiste.
Verifica que el tema personalizado esté correctamente instalado y funcionando.
Ejercicios para Docker Compose:
Escribir un archivo docker-compose.yml:

Crea un archivo docker-compose.yml que defina un servicio de WordPress usando la imagen que construiste.
Configura el servicio para montar el volumen para los datos persistentes.
Ejecutar WordPress con Docker Compose:

Usa el comando docker-compose up para ejecutar WordPress y su base de datos asociada.
Accede a WordPress a través del navegador y verifica que el tema personalizado esté funcionando correctamente.
Ejercicios para Kubernetes:
Escribir un manifiesto de despliegue de Kubernetes:

Crea un archivo YAML que describa un despliegue de WordPress en Kubernetes.
Especifica la imagen de contenedor que construiste previamente y monta un volumen para los datos persistentes.
Crear un servicio de Kubernetes:

Crea un archivo YAML que defina un servicio de Kubernetes para exponer WordPress al exterior.
Aplicar los manifiestos de Kubernetes:

Usa el comando kubectl apply para aplicar los manifiestos de despliegue y servicio de Kubernetes.
Verifica que WordPress esté desplegado correctamente en Kubernetes y que el tema personalizado esté disponible.
Estos ejercicios te ayudarán a familiarizarte con la creación de imágenes Docker personalizadas, el montaje de volúmenes, el uso de Docker Compose para orquestar servicios y el despliegue de aplicaciones en Kubernetes.
