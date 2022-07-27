# Clase 05

## GIT RESET

### GIT Reset soft
Elimina los commits que seleccioné pero la info se guarda en el staging area. O index

    git reset --soft <hash>

### GIT Reset mixed
Elimina los commits que seleccioné pero la info se guarda en el working directory.

    git reset <hash>
    git reset --mixed <hash>

### GIT Reset hard (Peligroso)
Por que pierdo lo que tenía dentro de los commits. Es destructivo

    git reset --hard <hash>