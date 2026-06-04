# git add

## ¿Qué es?

El comando `git add` se utiliza para agregar archivos o cambios al área de preparación (staging area). Los archivos agregados quedarán listos para formar parte del próximo commit.

## Sintaxis

```bash
git add nombre_archivo
```

Agrega un archivo específico al área de preparación.

```bash
git add .
```

Agrega todos los archivos modificados de la carpeta actual y sus subdirectorios.

## Ejemplo

Agregar el archivo `init.md`:

```bash
git add init.md
```

Agregar varios archivos:

```bash
git add init.md clone.md branch.md
```

Agregar todos los cambios:

```bash
git add .
```
