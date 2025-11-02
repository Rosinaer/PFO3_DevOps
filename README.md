# Seminario de Actualización DevOps

## Aplicación PHP en Kubernetes con Minikube

Este proyecto forma parte del trabajo práctico del seminario de DevOps.
Consiste en una aplicación PHP simple, contenerizada con Docker y desplegada en un clúster local de Kubernetes utilizando Minikube.

## Objetivos de la práctica

• Entender el origen, funcionamiento y manejo de contenedores.
• Administrar distintos contenedores y sus enlaces.
• Familiarizarse con los comandos de Docker.
• Manejar y configurar contenedores.
• Configurar el acceso de red de los contenedores.

## Contenido del repositorio:

src/index.php: archivo PHP que muestra el mensaje “Seminario DevOps! Bienvenido a mi repo” junto al nombre del host del contenedor.

Dockerfile: archivo que define la imagen Docker con PHP y copia el código fuente dentro del contenedor.

deploy-mi-app.yaml: archivo de configuración de Kubernetes que define el Deployment utilizado para ejecutar la aplicación.

.gitignore: archivo que excluye archivos temporales o de configuración local.

## Tecnologías utilizadas:

PHP

Docker

Kubernetes

Minikube
