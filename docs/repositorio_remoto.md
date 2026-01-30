

CREAR UN REPOSITORIO REMOTO EN GITHUB Y SINCRONIZARLO CON UNO LOCAL

Un repositorio remoto es una copia de tu proyecto que se guarda en internet (en este caso, en GitHub). Sirve para respaldar tu trabajo, compartirlo y colaborar con otras personas.

---

PARTE 1 — CREAR EL REPOSITORIO EN GITHUB

Paso 1: Entra a
[https://github.com](https://github.com)

Paso 2: Inicia sesión en tu cuenta.

Paso 3: Haz clic en el botón **New** (Nuevo repositorio).

Paso 4: Escribe el nombre del repositorio (por ejemplo: mi_proyecto).

Paso 5: Puedes agregar una descripción (opcional).

Paso 6: Elige si será:

* Public (público)
* Private (privado)

Paso 7: NO marques la opción de README si ya tienes un proyecto local creado.

Paso 8: Haz clic en **Create repository**.

GitHub te mostrará una página con instrucciones y una URL parecida a esta:
[https://github.com/usuario/mi_proyecto.git](https://github.com/usuario/mi_proyecto.git)

---

PARTE 2 — CONECTAR EL REPOSITORIO LOCAL CON GITHUB

Primero asegúrate de estar dentro de la carpeta de tu proyecto en la consola:

cd mi_proyecto

Si todavía no has iniciado Git en esa carpeta:

git init

---

Paso 1: Agregar los archivos al repositorio local

git add .

---

Paso 2: Hacer el primer commit

git commit -m "Primer commit"

---

Paso 3: Conectar tu repositorio local con el remoto de GitHub

git remote add origin [https://github.com/usuario/mi_proyecto.git](https://github.com/usuario/mi_proyecto.git)

(“origin” es el nombre que Git usa por defecto para el repositorio remoto)

---

Paso 4: Enviar los archivos a GitHub por primera vez

git branch -M main
git push -u origin main

Después de esto, tu proyecto local ya estará en GitHub.

---

PARTE 3 — TRABAJAR DESPUÉS DE LA PRIMERA SUBIDA

Cada vez que hagas cambios en tus archivos, debes hacer estos tres pasos:

1. Ver cambios
   git status

2. Agregar cambios
   git add .

3. Guardar cambios en Git
   git commit -m "Descripción de los cambios"

4. Subirlos a GitHub
   git push

---

RESUMEN DE COMANDOS IMPORTANTES

git init → Inicia repositorio local
git add . → Agrega archivos
git commit -m "mensaje" → Guarda cambios
git remote add origin URL → Conecta con GitHub
git branch -M main → Define la rama principal
git push -u origin main → Sube el proyecto por primera vez
git push → Sube cambios futuros

---

CONCLUSIÓN

Crear un repositorio remoto en GitHub permite guardar tu proyecto en la nube, tener respaldo de tu trabajo y colaborar con otros. Al sincronizarlo con tu repositorio local, puedes actualizar tu proyecto fácilmente cada vez que hagas cambios.
