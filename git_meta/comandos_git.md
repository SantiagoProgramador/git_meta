#Configuración Comando para conocer la versión de github

-   git -v
-   git --version

Comandos para configurar git por primera vez:

-   git config --global user.name "Your name"
-   git config --global user.email "Your name@correo.com"

Comando para ver que usuario está configurado o con que correo electrónico.

-   git config --global user.name
-   git config --global user.email
-   git config --list

Comando para inicializar git en un directorio

-   git init

Comando para ver el estado de los archivos

-   git status

Comando para ver todas las versiones de mi proyecto

-   git log
-   git log --oneline

Pasos para crear una versión de mi código

1. Agregar cambios

-   git add . (si se quiere agregar solo un archivo git add \*.js - homa.html)

2. Comprometer los archivos

-   git commit -m "Descripción del commit"

Comandos para cambiar de versión del proyecto

-   git checkout "ID de la última versión"
-   git checkout --.
