# Clase 01

## COMANDO DE CONSOLA BÁSICOS

* ls : Listar directorios
* cd : Cambiar de directorio
    
    cd <directorio>
    cd clase-01

* cd .. : Salgo de un directorio
* touch : Creo archivos vacios

    touch <nombre-archivo>
    touch archivo1.txt archivos2.txt

* mkdir : Creo directorios

    mkdir <nombre-directorio>
    mkdir dir1 dir2 dir3

* rm: Borrar archivos

    rm <archivo-a-borrar>
    rm index.html

* rmdir : Borro directorio 

    rmdir <directorio-a-borrar>
    rmdir dir1

* clear : Limpio la consola

## GIT

> Saber si tengo git instalado

    git --version

> Configuración importante de git
GLOBAL: Para todos los repositorios que se creen en el equipo

    git config --global user.name "nombre"
    git config --global user.email "correo"

> Inicializar repositorio git (Crear un repositorio)

    git init

> Configuración de repositorio con un usuario y mail diferente
LOCAL: Configura usuario y mail para el repositorio actual

    git config --local user.name "nombre"
    git config --local user.email "correo"

