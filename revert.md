# `git revert`
Deshace los cambios de un commit anterior creando un nuevo commit que revierte esos cambios. A diferencia de `git reset`, no borra el historial.

```
git revert <hash-del-commit>    # revierte un commit específico
git revert HEAD                 # revierte el último commit
```

## Ejemplo en nuestro repositorio
```
git revert HEAD
```
Terminal:
```
[alumno_sanger d75a2b3] Revert "docs: explicacion antes del revert de prueba en revert.md"
 1 file changed, 10 deletions(-)
```

### git log --oneline (post revert)
```
d75a2b3 (HEAD -> alumno_sanger, origin/alumno_sanger) Revert "docs: explicacion antes del revert de prueba en revert.md"
85106ba docs: explicacion antes del revert de prueba en revert.md
70de0ea docs: agrega explicacion de git revert
```