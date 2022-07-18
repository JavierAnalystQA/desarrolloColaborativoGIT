# Clase 02

## GIT REMOTE

### Agregar remoto

    git remote add origin <URL>
    git remote add origin https://github.com/mlapeducacionit/59710-git.git

### Verificar los remotos

    git remote
    git remote -v

### Para subir el repo local al remoto

    git push -u origin master

## GITIGNORE
Me permite descartar archivos y carpetas que no quiero subir.

## GITKEEP
Me permite mantener y versionar carpetas vacías.

## GIT COMMIT

### Para hacer un commit 

    git commit -m "Mensaje"

### Para hacer un git add y un git commit en simultaneo
Los archivos que quiero hacer commit deben estar en seguimiendo. Si los archivos no están en seguimiento (O sea Untraked) no me los va a agregar el git add.

    git commit -am "Mensaje"

### Para enmendar un commit

Agrego los archivos que me olvidé

    git add clase-02/cualquiera.md
Y luego hago el amend

    git commit --amend