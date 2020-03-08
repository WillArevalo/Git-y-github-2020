# Git Rebase: Reorganizando el trabajo realizado

El comando rebase es una mala práctica, nunca se debe usar, pero para efectos de curso te lo vamos a enseñar para que hagas tus propios experimentos. Con rebase puedes recoger todos los cambios confirmados en una rama y ponerlos sobre otra.
```
# Cambiamos a la rama que queremos traer los cambios
git checkout experiment
# Aplicamos rebase para traer los cambios de la rama que queremos 
git rebase master
```

_Para desaparecer la rama y unirla a la historia del master, primero se hace rebase desde la rama que se quiere eliminar hacia el master y luego del master hacia la rama que se quiere eliminar, por ultimo eliminar la rama con `git branch -d rama_a_eliminar`_