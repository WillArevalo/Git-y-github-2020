# Git Stash: Guardar cambios en memoria y recuperarlos después
Cuando necesitamos regresar en el tiempo porque borramos alguna línea de código pero no queremos pasarnos a otra rama porque nos daría un error ya que debemos pasar ese “mal cambio” que hicimos a stage, podemos usar git stash para regresar el cambio anterior que hicimos.

`git stash` es típico cuando estamos cambios que no merecen una rama o no merecen un rebase si no simplemente estamos probando algo y luego quieres volver rápidamente a tu versión anterior la cual es la correcta.

`Git Stash` es una forma útil de mantener mis cambios en temporal y poder moverme entre ramas.

- Para guardar cambios temporalmente: `git stash`
- Para ver los cambios en stash: `git stash -list`
- Para mover los cambios en stash a una rama: `git stash branch <nombre de rama>`
- Para borrar cambios en stash: `git stash -drop`
