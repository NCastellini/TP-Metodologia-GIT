usamos la IA para crear una hoja de ruta para hacer de foma mas eficiente los cambios, confilctos y demas.
todo fue hecho por nuestras manos, simplemente usamos la IA para ayudar en la planificacion, nada mas

Utilizamos la ayuda de la IA para hacer una correcciones criticas de ultimo moemnto pork somos deficientes mentales ya que mal entendimos el tema de la separaciond e ramas 
y creamos ramas personales y cada uno tomo 6 comandos, realizamos los cambios dentro de estas (cuando era dentro de cada rama para cada comando) 
asi que nada, con 3 horas para terminar estas correcciones le pedimos a la IA que nos de la forma mas eficiente de hacerlo (ya que este trabajo lo terminamos con mas de una semana de tiempo pero hoy nos enteramso gracias a usted que teniamos que corregir esto)
los comando utilizados fueron:

# 1. Pararce en la dev
git checkout dev

# 2. crear la rama desde la dev
git checkout -b feature/documentacion-ia

# 3. Limpiamos todas las carpetas y dejamos la raíz vacía para esta rama
Remove-Item -Recurse -Force Comandos_generales
Remove-Item -Recurse -Force Comandos_Informativos
Remove-Item -Recurse -Force Comandos_Movimiento
Remove-Item -Recurse -Force imagenes
Get-ChildItem -File | Where-Object { $_.Name -ne ".gitignore" -and $_.Name -ne "IA.md" } | Remove-Item -Force

# 4. Forzamos el cambio en IA.md para que Git lo registre en esta rama
Add-Content -Path IA.md -Value ""

# 5. Registramos, metemos el commit reglamentario y subimos
git add -A
git commit -m "docs: registrar uso de modelo de lenguaje en archivo IA.md"
git push origin feature/documentacion-ia


## estos comandos son solo el ejemplo de esta rama para el archivo de IA.md esto lo tuvimos que adaptar para cada rama propia ##

pd: y para corregir un bug en el VScode de uno de los integrantes ya que no le aparecia la opcion para corregir los cambios dentro de un conflico 
rarisimo, pero bueno 

