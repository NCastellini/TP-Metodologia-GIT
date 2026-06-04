# Git Switch


El teletransportador de ramas.

Este comando se creo para quitarle trabajo a git checkout. Su única y exclusiva misión es cambiar de una rama a otra o crear una nueva. Es mas seguro y mas facil de entender.

Como entenderlo? 
Tenes dos cuadernos de dibujo: uno para el proyecto principal (main) y otro para hacer bocetos (bocetos). git switch es el acto de cerrar un cuaderno y abrir el otro.

Ejemplo:

Queres irte a la rama modo-oscuro para trabajar en ella:
git switch modo-oscuro

Quieres crear una nueva rama llamada login y saltar a ella de inmediato:
git switch -c login
