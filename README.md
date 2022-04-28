# curso-docker

## Introducción <a name="introduccion"></a>

En este repositorio se presenta toda la info y practicas necesarias para impartir un curso de Docker.

## Indice <a name="instalacion"></a>

    * [Introducción](#introduccion)
    * [Instalación](#instalacion)
    * [Best practices](#best-practices)

### Best practices <a name="best-practices"></a>

Una mejor explicación se puede observar en el video: [enlace al video](https://www.youtube.com/watch?v=8vXoMqWgbQQ)

1. Usar imágenes oficiales como base.
2. Usar versiones específicas de dichas imágenes.
3. Usar las imágenes de menor tamaño posible.
4. Optimizar el caché de la construcción con capas.
5. Usar el .dockerignore para evitar cargar cosas innecesarias.
6. Si hay que realizar un proceso de build, separar la imágen en múltiples etapas.
7. Usar un usuario con los privilegios necesarios.
8. Escanear en búsqueda de vulnerabilidades.

Un ejemplo de uso de múltiples etapas se ve en la carpeta multi-stage del presente repositorio.