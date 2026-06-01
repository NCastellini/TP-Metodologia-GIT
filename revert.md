# `git revert`
Deshace los cambios de un commit anterior creando un nuevo commit que revierte esos cambios. A diferencia de `git reset`, no borra el historial.

```
git revert <hash-del-commit>    # revierte un commit específico
git revert HEAD                 # revierte el último commit
```

## Ejemplo en nuestro repositorio

### `git log --oneline`
```
70de0ea (HEAD -> alumno_sanger, origin/alumno_sanger) docs: agrega explicacion de git revert
```

### `git revert`
```
git revert 70de0ea
``` 