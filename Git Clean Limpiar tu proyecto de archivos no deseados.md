# Git Clean: Limpiar tu proyecto de archivos no deseados

A veces creamos archivos cuando estamos realizando nuestro proyecto que realmente no forman parte de nuestro directorio de trabajo, que no se debería agregar y lo sabemos.

- Para saber qué archivos vamos a borrar tecleamos `git clean --dry-run`
- Para borrar todos los archivos listados (que no son carpetas) tecleamos `git clean -f`

Por supuesto, no tomará en cuenta los archivos en .gitignore. Porque son ignorados para todo lo que tenga que ver con git 😄

git clean solo borra las cosas que puede indexar