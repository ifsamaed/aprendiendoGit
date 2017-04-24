### COMANDOS

Los comandos que debes saber como la regla del dos son: comandos git, merge, push y pull así como hacer checkouts de diferentes ramas y borrarlas

.

* `$ git init`

* `$ git status`

  * Si el nombre de tus ficheros aparecen en rojo, no están ~~guardados ~~

* `$ git add [NOMBRE FICHERO]`

* `$ git add -A : AGREGA TODOS, tener cuidado con este comando.`

* `$ git branch: Nos muestra todas las ramas`

  * * La rama principal estará señalada por un asterisco. 

* `$ git branch -D [Rama]: borrar rama`

* `$ git branch -l [Rama]: crea la rama`

* `$ git branch push -u origin [Rama]: Push un branch local a remoto`

--------------- CAMBIOS ENTRE RAMAS  ---------------

* `$ git checkout:  viajamos a través de nuestros commits o nuestras ramas`

* `$ git checkout [Rama] : viajamos a la Rama especificada`

* `$ git checkout [6 primeros dígitos de un commit]  : Nos indica que archivos han sido modificados.`

* `$ git checkout -b [Rama] : Crear una nueva rama y saltar a ella`

---------------  COMMITS ---------------

* `$ git commit -m “mensaje”`

* `$ git commit --amend : Añadir al ultimo commit, para archivos olvidados, para modificar el último commit , nos ayudará mucho 😉 .`

--------------- MOSTRAR ---------------

* `$ git log //lista todos los commit`

* `$ git log --graph //Listamos todos los gráficos como un grafo *`

--------------- LIMPIAR ---------------

* `$ git reset // similar a checkout a diferencia que elimina los commits`

* `$ git reset ——soft //No toca nuestro working area`

* `$ git reset ——mixed //borra el “staging area”, sin tocar el “working area”`

* `$ git reset ——hard // borra absolutamente todo`

--------------- AYUDA ---------------

* `$ git help`



