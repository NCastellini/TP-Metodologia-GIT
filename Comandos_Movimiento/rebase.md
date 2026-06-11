# git rebase


La maquina del tiempo para organizar el pasado.

Al igual que merge, sirve para integrar cambios de una rama en otra, pero lo hace de una forma distinta: reescribe la historia. Toma tus cambios, los guarda un momento, actualiza tu base con los últimos cambios de la otra rama, y luego vuelve a aplicar tus cambios encima.

Como entenderlo? Imagina que sacaste una copia de un documento ayer para trabajar en algun codigo. Hoy, tu jefe actualizo el documento original. Con rebase, en lugar de fusionar los dos documentos (lo que haria con un merge), Git hace de cuenta que vos sacaste la copia hoy, con los cambios de tu jefe ya incluidos, y luego añade tus ideas arriba. Deja una línea de tiempo limpia y recta.

Ejemplo:
Estas en tu rama nueva-funcion y quieres que parezca que la creaste a partir del main más reciente:
git rebase main
