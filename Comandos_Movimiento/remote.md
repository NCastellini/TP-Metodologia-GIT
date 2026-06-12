# Remote

## Definición

Un **remote** es la conexión entre mi repositorio local y el repositorio que está en GitHub. Me permite enviar cambios al repositorio remoto y traer cambios realizados por otros integrantes del equipo.

---

## Sintaxis

### Ver los remotos configurados

```bash
git remote -v
```

### Traer información del repositorio remoto

```bash
git fetch origin
```

### Subir cambios al repositorio remoto

```bash
git push origin nombre-rama
```

---

## Ejemplo

Estoy trabajando en mi rama `NCastellini` y un compañero realizó cambios en la rama `dev` del repositorio en GitHub.

Primero actualizo la información del repositorio remoto:

```bash
git fetch origin
```

Luego incorporo los cambios de la rama `dev` a mi rama actual:

```bash
git merge origin/dev
```
## Ver remotos configurados

```bash
git remote -v
```

Muestra los repositorios remotos asociados al proyecto.