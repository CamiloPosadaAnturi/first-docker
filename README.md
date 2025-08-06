# Proyecto Python

## Descripción

Este es un proyecto de ejemplo desarrollado en Python, el cual imprime un mensaje inicial en la consola. El propósito es demostrar una configuración básica utilizando Docker para contenerización.

## Tecnologías utilizadas

- 🐍 Python  
- 🐳 Docker  
- 📝 Markdown  

## Requisitos previos

- Tener Docker instalado.
- Conexión a internet para descargar las dependencias (si las hubiera).

## Estructura del proyecto

- `project.py`: Script principal de Python.  
- `Dockerfile`: Instrucciones para construir la imagen Docker.  
- `README.md`: Documentación del proyecto.  

## Ejecución

1. Abre la terminal en la carpeta del proyecto (Ejemplo en Windows):

```bash
cd %USERPROFILE%\Desktop\proyecto_python
o donde se encuentre en el archivo.
```

2. Construye la imagen de Docker:

```bash
docker build -t proyecto_python .
```

3. Ejecuta el contenedor:

```bash
docker run proyecto_python
```

## Autor

**Juan Camilo Posada Anturi**  
[GitHub](https://github.com/CamiloPosadaAnturi)  
camiloposada1005@gmail.com
