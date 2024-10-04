# Ramas y Fusiones

![Ramas y fusiones Github](images/ramas.png)

---

## {==Mostrar y gestionar ramas==}

- **`git branch`**: Muestra una lista de las ramas que existen en este proyecto.
- **`git branch -a`**: Muestra una lista de todas las ramas (locales y remotas).
- **`git branch [nombre de la rama]`**: Crea una nueva rama.
- **`git branch -d [nombre de la rama]`**: Elimina una rama local.
- **`git push origin --delete [nombre de la rama]`**: Elimina una rama remota.

## {==Cambiar entre ramas==}

- **`git checkout -b [nombre de la rama]`**: Crea una nueva rama y nos desplaza hasta ella.
- **`git checkout -b [nombre de la rama] origin/[nombre de la rama]`**: Clona una rama remota y nos desplaza hasta ella.
- **`git branch -m [nombre de la rama antigua] [nombre de la rama nueva]`**: Renombra una rama local.
- **`git checkout [nombre de la rama]`**: Cambia a una rama concreta.
- **`git checkout -`**: Cambia a la última rama activa.

## {==Descartar cambios==}

- **`git checkout -- [nombre-del-archivo.txt]`**: Descarta cambios en un archivo.

## {==Fusionar ramas==}

- **`git merge [nombre de la rama]`**: Combina una rama concreta con la rama activa.
- **`git merge [nombre de la rama de origen] [nombre de la rama de destino]`**: Combina una rama concreta (rama de origen) con una rama nueva (rama de destino).

## {==Guardar y revertir cambios==}

- **`git stash`**: Revierte los últimos cambios y errores en el directorio actual, guardando el estado del trabajo sin hacer commit.
- **`git stash clear`**: Elimina todas las entradas de `git stash`, descartando los cambios guardados.
