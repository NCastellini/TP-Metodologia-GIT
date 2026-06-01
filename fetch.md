# git fetch

El chismoso (mira pero no toca).

Este comando va al servidor remoto (como GitHub) y descarga todo lo nuevo que hayan subido tus compañeros (ramas, commits, etc.), pero no toca tu código de trabajo. Solo actualiza el "radar" de tu Git local.

Como entenderlo? Es como mirar el menú de un restaurante o revisar si tienes correos nuevos. Te enteras de lo que hay, pero aun no pediste la comida ni abriste los sobres. Tu codigo sigue intacto hasta que decidas traer esos cambios de verdad (normalmente con un git pull o git merge).

Ejemplo:
Queres ver si alguien del equipo subio algo nuevo a GitHub antes de empezar a trabajar:
git fetch
(Después de esto, Git te tira un mensaje: "Che, hay 3 commits nuevos en la nube", pero tu pantalla no cambiara en nada).