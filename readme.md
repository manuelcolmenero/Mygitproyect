# Ejercicio 1

Se deberá crear un repositorio y realizar una serie de operaciones desde la consola de comandos sobre el mismo para posteriormente subir el repositorio a Github. En el
repositorio, deberá existir un archivo readme.md con las respuestas a las siguientes preguntas:


- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
*git reset --hard HEAD~1*
Con este comando se cambian los punteros sobre el que nos encontramos un commit previo y descarta todos los cambios del directorio, actualizando la carpeta con todos los datos que posea el commit.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
*git reflog* >> checkout: moving from htmlify to styled
Con este comando se obtienen todas las instrucciones realizadas recuperando así la dirección del anterior commit

*git merge 8b2db7f* 
Se realiza un merge con el commit al que deseamos volver para que haga un Fast Forward llevando los puntos y recuperando el estado anterior de los ficheros.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No causa ningun conflicto dado que se encuentra en la misma linea de actuaciación que styled y por lo tanto no hay nada que modificar por ser una versión anterior.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Causa conflicto porque ambas ramas poseen el fichero git-nuestro.md modificado en las mismas líneas.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No causa ningun conflicto dado que los datos que poseia styled y master son iguales. El merge realiza un Fast Forward.

- ¿Qué comando o comandos utilizaste en el paso 25?
*git log --graph --decorate*

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, podia haber sido fast forward dado que el fichero de title poseia todos los cambios de la rama master

- ¿Qué comando o comandos utilizaste en el paso 27?
*git reset HEAD~1*

- ¿Qué comando o comandos utilizaste en el paso 28?
*git checkout -- git-nuestro.md*

- ¿Qué comando o comandos utilizaste en el paso 29?
*git branch -D title*

- ¿Qué comando o  comandos utilizaste en el paso 30?
*git reflog* >> merge title: Merge made by the 'recursive' strategy.
*git merge 758aa8e*

- ¿Qué comando o comandos usaste en el paso 32?
*git reflog* >> Se añade git-nuestro.md a la rama master
*git checkout 4639c09*

- ¿Qué comando o comandos usaste en el punto 33?
*git reflog* >> Se modifica git-nuestro.md en rama title para incluir una linea de titulo
*git checkout 6ab8ecb*

