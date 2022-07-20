# Clase 03

## GIT RAMAS (Branchs) - REPASO

> Crear una rama

    git branch <nombre-rama>
    git branch dev

> Moverme entre ramas

    git switch <nombre-rama>
    git switch dev

> Para ver las ramas

    git branch

> Para borrar una ramas

    git branch -d <nombre-rama>
    git branch -d dev

> Para forzar el borrado de una ramas
Recuerden que este flag me sirve para confirmar el borrado de una rama que no fue fusionada con ninguna otra.

    git branch -D <nombre-rama>
    git branch -D dev