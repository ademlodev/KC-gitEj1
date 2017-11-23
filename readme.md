# Cuestionario


## ¿Qué comando utilizaste en el paso 11? ¿Por qué?

~~~~
git reset --hard HEAD~1
~~~~

Para volver justo al nodo anterior del ultimo commit moviendo el puntero HEAD y con el --hard limpiando el Working copy

## ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

~~~~
$ git reflog
$ git reset --hard df62b66
~~~~

Primero reflog para obtener el listado de commits desde el primero al último ejecutado, al comprobar que justo el anterior commit era el que tenía que rehacer, seleccionamos su hash y realizamos el cambio del puntero a la dirección indicada.

## El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No. Porque al estar en la rama styled y esta ser el ultimo commit realizado, no tenía nada que mergear con master y devuelve el mensaje “Already up-to-date”.

## El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si. Porque al unir la rrama styled con la rama htmlify contenían diferentes cambios en el algunas líneas del mismo fichero que se quería unir. Por lo tanto git no sabe como solucionarlo y genera conflicto.

## El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No. Porque el fichero de la rama master no cotenia las líneas que añadimos en el fichero de la rama styled y por lo tanto las añadió sin problema.

## ¿Qué comando o comandos utilizaste en el paso 25?

~~~
$ git log –graph
~~~~

## El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Si, porque la rama del title es la única rama y por lo tanto se podría haber colocado el puntero directamente en el ultimo commit de la rama title y no crear el nuevo commit.

## ¿Qué comando o comandos utilizaste en el paso 27?

~~~~
$ git reset HEAD~1
~~~~

## ¿Qué comando o comandos utilizaste en el paso 28?

~~~~
$ git checkout git-nuestro.md
~~~~

## ¿Qué comando o comandos utilizaste en el paso 29?

~~~~
$ git branch -D title
~~~~

## ¿Qué comando o comandos utilizaste en el paso 30?

~~~~
$ git reflog
$ git reset --hard cef7adf
~~~~

## ¿Qué comando o comandos usaste en el paso 32?

~~~~
$ git reflog
$ git reset --hard cef66b3
~~~~

## ¿Qué comando o comandos usaste en el punto 33?

~~~~
git reflog
git reset --hard 825ed2e
~~~~
