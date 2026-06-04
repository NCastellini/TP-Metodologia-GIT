# git merge

La fusion pacifica.

Se usa para unir dos ramas. Toma los cambios de una rama (por ejemplo, una caracteristica nueva) y los integra en tu rama principal. Crea un "commit de fusión" que une ambas historias.

Como entenderlo? Imagina que vos estas escribiendo el capítulo 1 de un libro y tu compañero el capitulo 2. Cuando terminan, pegan el capitulo 2 justo después del capítulo 1. Ambos caminos se juntan en un evento final.

Ejemplo:
Estás en la rama main y quieres traer las mejoras que terminaste en la rama Dev:
git merge Dev

Una cosa que falto mencionar es que al momento de hacer el merge si dos o mas integrantes del equipo modifican lo mismo y cada uno manda su merge
lo que va a ocurrir es que se van a generar conflictos.

Esto no es mas que un aviso de que dos modificaciones simultaneas en la misma seccion ocurrieron y para solucionarlo 
solo se tiene que elegir entre 3 opciones:
aceptar los cambios enrantes
aceptar los dos cambios (ya existentes + nuevos)
rechazar los cambio nuevos (seguir con el codigo viejo)
