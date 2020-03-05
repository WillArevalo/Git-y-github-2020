# Fusión de ramas con Git merge

El comando git merge nos permite crear un nuevo commit con la combinación de dos ramas (la rama donde nos encontramos cuando ejecutamos el comando y la rama que indiquemos después del comando).

Crear un nuevo commit en la rama master combinando
los cambios de la rama cabecera:

`git checkout master`

`git merge cabecera`

Crear un nuevo commit en la rama cabecera combinando
los cambios de cualquier otra rama:

`git checkout cabecera`

`git merge cualquier-otra-rama`
