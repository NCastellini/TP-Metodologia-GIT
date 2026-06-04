# `git status`

```
git status
```

## Ejemplo en nuestro repositorio

### `git status`
```
On branch alumno_sanger
Your branch is up to date with 'origin/alumno_sanger'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   log.md
        modified:   status.md

no changes added to commit (use "git add" and/or "git commit -a")
```

### Interpretación
- `On branch alumno_sanger`: indica la rama actual en la que estamos trabajando.
- `Your branch is up to date with 'origin/alumno_sanger'`: la rama local está sincronizada con la remota.
- `Changes not staged for commit`: existen cambios realizados que aún no fueron agregados al área de preparación (staging).
- `modified: log.md` y `modified: status.md`: estos archivos fueron modificados desde el último commit.
- `no changes added to commit`: todavía no hay cambios preparados para ser confirmados.