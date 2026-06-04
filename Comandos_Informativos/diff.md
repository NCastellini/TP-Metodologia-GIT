# `git diff`
Muestra las diferencias entre archivos. Sirve para ver que cambio antes de hacer un commit.

```
git diff                        # cambios aún no agregados al staging
git diff --staged               # cambios ya en staging
git diff <hash1> <hash2>        # diferencia entre dos commits
```

## Ejemplo en nuestro repositorio

### `git add diff.md` + `git diff --staged`

Terminal:
```
diff --git a/diff.md b/diff.md
new file mode 100644
index 0000000..bac7e4c
--- /dev/null
+++ b/diff.md
@@ -0,0 +1,9 @@
+# `git diff`
+Muestra las diferencias entre archivos. Sirve para ver que cambio antes de hacer un commit.
+
+```
:
diff --git a/diff.md b/diff.md
new file mode 100644
index 0000000..bac7e4c
--- /dev/null
+++ b/diff.md
@@ -0,0 +1,9 @@
+# `git diff`
+Muestra las diferencias entre archivos. Sirve para ver que cambio antes de hacer un commit.
+
+```
+git diff                        # cambios aún no agregados al staging
```

En la salida, las líneas que comienzan con `+` son líneas agregadas y las que comienzan con `-` son líneas eliminadas. El encabezado `@@ -0,0 +1,9 @@` indica que en el archivo original no había líneas y en el nuevo hay 9 líneas agregadas.