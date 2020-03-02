# Crea un repositorio de Git y haz tu primer commit

### Inicializar un nuevo proyecto
`git init`

### Configuracion de perfil 
`git config --global user.email "tu@email.com"`

`git config --global user.name "Tu Nombre"`

### Añadir cambios al Stage
Si queremos agregar todos lo cambios de los archivos en la carpeta se usa el '.' (punto), si se quiere añadir el cambio a solo un archivo se coloca el nombre del archivo.

`git add .`

Si se desea eliminar el cambio que ya se encuentra en el *Stage* se utiliza

`git rm --cached archivo.ext`

#### Guardando un cambio en la base (Commit)

`git commit -m 'mensaje wuay'`

### Verificar el historial de cambios de un archivo

`git log archivo.ext`

### Mirar el status del Stage

`git status`


