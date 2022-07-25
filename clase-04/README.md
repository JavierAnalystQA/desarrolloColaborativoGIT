# Clase 04

## GIT CHERRY PICK

**IMPORTANTE:** Tengo que estar ubicado en la rama que espero traerme el o los commits.

    git cherry-pick <hash>
    git cherry-pick <hash1> <hash2> <hash3>

```sh
    git cherry-pick <hash>^..<hash> #Todos los commits incluidos en el rango y además los extremos
```
```sh
    git cherry-pick <hash>..<hash> #Solo me trae los que están entre esos 2 commits, no las puntas
```

### SI tengo varios commits, no uno. Voy a tener que hacer

    git cherry-pick --continue

### Para abortar el proceso de cherry-picking

    git cherry-pick --abort

## GIT ALIAS

### Para crear alias

    git config --global alias.ll "log --oneline --decorate --all --graph"
    git config --global alias.l "log --oneline"
    git config --global alias.s "status --short"
## Para listar alias

    git config --get-regexp alias

## Para quitar un alias

    git config --global --unset alias.s


## GIT STASH
Es construido basado en una estructura de datos conocida como pila.

> ¿Qué me permite el stash?

Me permite registrar temporalmente los cambios del Working Directory y el Staging AREA.

### Crear un stash

    git stash

### Listar los stash

    git stash list

### Recuperar un stash

**Nota:** Si el stash que estoy tratando de recuperar genera un conflico con mi código, o sea con el código que esta en el working directory. Me va a dejar en la caja de stash el stash. Si no hay conflictos, borra el stash.

    git stash pop





