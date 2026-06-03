# Conflictos en Git

## ¿Qué es un conflicto?

Un conflicto ocurre cuando Git no puede fusionar dos ramas de forma automática.
Esto sucede cuando dos o más integrantes modificaron la misma línea del mismo 
archivo en ramas distintas, y al intentar mergear, Git no sabe cuál de los dos 
cambios conservar.

## ¿Cuándo aparece?

Git detecta el conflicto al ejecutar:

```
git merge nombre-rama
```

Si hay conflicto, Git lo indica con el mensaje: