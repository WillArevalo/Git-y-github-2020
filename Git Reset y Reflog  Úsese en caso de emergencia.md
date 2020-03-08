# Git Reset y Reflog: Úsese en caso de emergencia

¿Qué pasa cuando todo se rompe y no sabemos qué está pasando? Con git reset HashDelHEAD nos devolveremos al estado en que el proyecto funcionaba.

- `git reflog` Sirve para ver en que momento un IDcommit especifico fue el HEAD de la rama
- git reset --soft HashDelHEAD te mantiene lo que tengas en staging ahí.
- git reset --hard HashDelHEAD resetea absolutamente todo incluyendo lo que tengas en staging.

__git reset es una mala práctica, no deberías usarlo en ningún momento; debe ser nuestro último recurso.__