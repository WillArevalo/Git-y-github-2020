# Introducción a las ramas o branches de Git

Las ramas son la forma de hacer cambios en nuestro proyecto sin afectar el flujo de trabajo de la rama principal. Esto porque queremos trabajar una parte muy específica de la aplicación o simplemente experimentar.

La cabecera o _HEAD_ representan la rama y el commit de esa rama donde estamos trabajando. Por defecto, esta cabecera aparecerá en el último commit de nuestra rama principal. Pero podemos cambiarlo al crear una rama (`git branch rama`, `git checkout -b rama`) o movernos en el tiempo a cualquier otro commit de cualquier otra rama con los comandos (`git reset id-commit`, `git checkout rama-o-id-commit`).

`git commit -am`
Comando que hace add y commit al mismo tiempo a archivos a los que se ha hecho commit previamente.

`git branch <nombre que quieres poner a tu nueva rama>`
Comando para crear tu nueva rama

`git checkout <nombre de rama que creaste previamente>`
Comando para moverte a las ramas que hayas creado

_HEAD_ puede considerarse como un indicador de cuál versión de commit se está viendo de los últimos archivos.