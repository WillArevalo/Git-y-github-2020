# Tags y versiones en Git y GitHub

Los tags o etiquetas nos permiten asignar versiones a los commits con cambios más importantes o significativos de nuestro proyecto.

Comandos para trabajar con etiquetas:

- Crear un nuevo tag y asignarlo a un commit: `git tag -a nombre-del-tag id-del-commit.`
- Borrar un tag en el repositorio local: `git tag -d nombre-del-tag.`
- Listar los tags de nuestro repositorio local: `git tag o git show-ref --tags.`
- Publicar un tag en el repositorio remoto: `git push origin --tags.`
- Borrar un tag del repositorio remoto: `git tag -d nombre-del-tag` y `git push origin :refs/tags/nombre-del-tag.`
