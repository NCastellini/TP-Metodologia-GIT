# git commit

## ¿Qué es?

El comando `git commit` se utiliza para guardar de forma permanente los cambios que fueron agregados previamente al área de preparación (staging area). Cada commit representa una versión del proyecto en un momento determinado.

## Sintaxis

```bash
git commit -m "mensaje"
```

Crea un commit con el mensaje especificado.

## Ejemplo

Crear un commit luego de agregar un archivo:

```bash
git add init.md
git commit -m "feat: agregar explicación de git init"
```

## Ejemplo práctico

Durante este trabajo práctico, después de crear y agregar el archivo `branch.md`, se realizó el siguiente commit:

```bash
git add branch.md
git commit -m "docs: agregar explicación de git branch"
```
