# Comandos útiles de Git
1. git init (inicia el git en la carpeta donde uno está ubicado)

2. git add . (Toma todos los archivos desde el último commit y los prepara para una fotografía o conmit) sube todos los archivos a un escenario conocido como Stage, aquí los archivos está esperando para que tú tomes la fotografía.
3. git reset . (realiza un paso atras a la acción de git add .)
4. git commit -m "nombre representativo de los cambios"(Aquí se hace la fotografía)
5. git checkuot -- .
6. git log (me permite ver todos los estados de los commits)
7.  git commit --amend (nos la la opción de cambiar el nombre del último commit. para editar insertamos la letra i (insert) luego de cambiar el nombre para confirmar y salir debemos de presionar la tecla escape, luego escribir el :wq! presionar enter y ya está editado el nombre del último commit)
8. git checkuot -b nombreNuevaRama (Crea una nueva rama y nos lleva directo a esta rama. No es aconsejable trabajar directamente en la rama master sino. cambiar de rama, y para esto debemos de crear otras ramas, normalmente una para cada usuario que lo vaya a editar)
9. git branch (Nos lista las ramas creadas y nos muestra en que rama estamos actualmente)
10. git checkout master (nos cambia de rama y nos lleva a la rama master)
11. git merge NombreRamaQueQuieresUnir (Une las ramas para que se puedan visualizar en el editor de texto y para poder hacer cambios dentro de un editor en una sola computadora)
12. git branch -d nombreDeLaRamaQueQuieresBorrar (Borra el nombre de la rama deseada y la elimina)
13. 