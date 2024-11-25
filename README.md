# RepasoGit
Repositorio de repaso de git 2024 11-11

Recopilacion de comandos en gitbash.

git status: Comprueba el estado de sincronización con la rama donde está
    Al no haberlo sincronizado, hay que utilizar add

git add: con el archivo que queramos guardar en la rama (puede ser todos o uno especifico)
    Al usarlo se abre la opción de hacer un commit

git commit -m "nombre.html con ejemplo"
    Hay que añadir -m ; nombre y un texto descriptivo
    Luego comprobamos con status si hay algun commit pendiente ("nothing to commit")

git push origin : para subirlo a github
    pide la contraseña ssh
    (podemos comprobar con git log para ver el estado)

-- Vamos a github para comprobar que está actualizado --

Luego podemos crear ramas (como develop) para no utilizar siempre la rama main

git checkout -b develop : con checkout salimos de la rama main y entramos en -b para crear develop.
    Automaticamente se cambia

git branch: vemos las ramas que hay y donde estamos *

git log: vemos la evolucion de los estados de git

-- comandos extra --

touch : sirve para crear archivos 

git restore readme.md : sirve para volver a un punto anterior