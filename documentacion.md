# Documentación práctica de Git
## ¿Qué es Git?
Git es un Sis. de control de versiones que permite guardar el historial de cambios de un proyecto. Gracias a Git podemos saber qué cambios se han hecho, quién los hizo y volver a versiones anterios si es necesario 
## ¿Cuál es el flujo de trabajo de Git?
El flujo básico de trabajo de git es:
1. Crear o modificar archivos en el proyecto.
2. Añadir los archivos al área de preparación con git add.
3. Guardar los cambios con un commit usandolo.
4. Subir los cambios al repositorio remoto con git push.
5. descargar cambios del repositorio remoto con git pull o dit fetch.
![Descripción de la imagen](/imagenes/la%20rama%20del%20commit.PNG)

## Comandos realizados durante la practica
### Git add
El comando git add sirve para preparar los archivos modificados antes de hacer un commit.
### Git commit
El comando git commit guarda los cambios preparados en el historial del repositorio.
### Git push
El comando git push sube los commits locales al repositorio remoto en GitHub.
### Git pull 
El comando git pull descarga los cambios del repositorio remoto y los mezcla con la rama local.
### Git fetch
El comando git fetch descarga información del repositorio remoto, pero no mezcla los cambios automáticamente.
### Git merge
El comando git merge sirve para unir cambios de una rama o del repositorio remoto con nuestra rama actual.
## ¿Qué es un conflicto de git?
Un conflicto de Git ocurre cuando se modifica la misma parte de un archivo en dos lugares distintos, por ejemplo, en GitHub y en local. Git no puede decidir automáticamente qué versión debe conservar.

En esta práctica, el conflicto se produjo porque se modificó el mismo archivo en GitHub y después también en local.
### Ejemplo de conflicto:
![Descripción de la imagen](/imagenes/final%20como%20queda%20el%20index.PNG)