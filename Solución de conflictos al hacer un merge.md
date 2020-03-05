# Solución de conflictos al hacer un merge

Git nunca borra nada a menos que nosotros se lo indiquemos. Cuando usamos los comandos `git merge` o `git checkout` estamos cambiando de rama o creando un nuevo commit, no borrando ramas ni commits (recuerda que puedes borrar commits con `git reset` y ramas con `git branch -d`).

Los archivos con conflictos por el comando `git merge` entran en un nuevo estado que conocemos como _Unmerged_. Funcionan muy parecido a los archivos en estado _Unstaged_, algo así como un estado intermedio entre _Untracked_ y _Unstaged_, solo debemos ejecutar git add para pasarlos al área de staging y git commit para aplicar los cambios en el repositorio.