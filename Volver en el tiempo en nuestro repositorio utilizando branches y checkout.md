# Volver en el tiempo en nuestro repositorio utilizando branches y checkout

El comando `git checkout ID archivo.ext` del *commit* nos permite viajar en el tiempo. Podemos volver a cualquier versión anterior de un archivo específico o incluso del proyecto entero. Esta también es la forma de crear ramas y movernos entre ellas.

También hay una forma de hacerlo un poco más “ruda”: usando el comando `git reset ID arg` . En este caso, no solo “volvemos en el tiempo”, sino que borramos los cambios que hicimos después de este commit.

Hay dos formas de usar `git reset` : con el argumento `--hard`, borrando toda la información que tengamos en el área de staging (y perdiendo todo para siempre). O, un poco más seguro, con el argumento `--soft`, que mantiene allí los archivos del área de staging para que podamos aplicar nuestros últimos cambios pero desde un commit anterior.

`git reset fca5d64476033ae83af5bdc6539c6a57d4e354c5 --soft`


Para ver los logs en una linea(mas conveniente)
`git log --oneline`

Para ver los cambios a nivel de bytes
`git log --stat`

Para eliminar los ultimos cambios en el Stage

`git reset HEAD`

`git rm --cached` : Elimina los archivos del área de Staging y del próximo commit pero los mantiene en nuestro disco duro.

`git rm --force` : Elimina los archivos de Git y del disco duro. Git siempre guarda todo, por lo que podemos acceder al registro de la existencia de los archivos, de modo que podremos recuperarlos si es necesario (pero debemos usar comandos más avanzados).
