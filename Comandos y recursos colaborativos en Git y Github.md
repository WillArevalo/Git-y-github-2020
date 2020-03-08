# Comandos y recursos colaborativos en Git y Github

* `git shortlog -sn` Nos muestra el número de commit por cada colaborador.
* `git shortlog -sn --all` Nos muestra el número de commit por cada colaborador incluidos los eliminados.
* `git shortlog -sn --all --no-merges` Nos muestra el número de commit por cada colaborador incluidos los eliminados pero que no incluya los merge

* `git config --global alias.<nombre> “comando(s)_git”` Definir un alias en git. Ejemplo:
`git config --global alias.stats "git shortlog -sn --all --no-merges"`
Despues solo ejecutamos
`git stats`
* `git blame <nombre_archivo>` Para lograr identificar quien realizo alguna acción en el archivo.
* `git blame -c <nombre_archivo>` Para lograr identificar quien realizo alguna acción en el archivo incluyendo identación para mayor claridad
* `git blame <nombre_archivo> -L#i,#f` Identificamos quien modifica algo por última vez desde un rango de líneas. La línea inicial (L#i) y línea final (L#f)