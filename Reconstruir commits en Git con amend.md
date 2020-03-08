# Reconstruir commits en Git con amend

A veces hacemos un commit, pero resulta que no queríamos mandarlo porque faltaba algo más. Utilizamos `git commit --amend`, amend en inglés es remendar y lo que hará es que los cambios que hicimos nos lo agregará al commit anterior.

Cuando se te olvida modificar algo y ya mandaste el commit y no querías que se fuera sin esa modificación, debes hacer lo siguiente:

1. Hacer lo que se te olvidó.
2. Es importante añadirlo con un: `git add [archivo_modificado]`
3. `git commit --amend`
