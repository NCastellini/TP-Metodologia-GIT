# Git Checkout 

El viajero del tiempo (versión antigua de lo que ahora es el switch).

Este comando sirve principalmente para dos cosas: cambiar de rama o restaurar archivos a un estado anterior. Era el "multiusos" de Git, aunque hoy en día se prefiere usar comandos más especificos (como git switch).

Como? Es como poner un punto de restauración en un videojuego o abrir una partida guardada anterior.

Ejemplo:

Queres ver como estaba tu codigo en una rama llamada Punto_de_Guardado1:
git checkout Punto_de_Guardado1

Queres descartar los cambios que hiciste en un archivo llamado index.html y dejarlo como estaba al principio:
git checkout index.html

Otro ejemplo es mas que nada por costumbre la creacion de ramas en general lo que hacemos o hago es hacer un git checkout -b <nombre de la rama>
es como un 2x1 ya que por atras git lo que hace son dos cosas:
crear la rama (como seria con el comando de git branch <nombre de la rama>) 
salta automaticamente a la rama que acabas de crear (como seria con el comando de git switch <nombre de la rama>)

