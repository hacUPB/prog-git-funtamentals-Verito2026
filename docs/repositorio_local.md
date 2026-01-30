# CÓMO CREAR UN REPOSITORIO LOCAL CON COMANDOS DE GIT

Un repositorio local es una carpeta de tu computadora que Git empieza a “vigilar” para guardar el historial de cambios de tus archivos.

## PASO 1 — Abrir la consola
Primero abre Git Bash, la terminal de VS Code o cualquier consola donde tengas Git instalado.

## PASO 2 — Ir a la carpeta donde quieres tu proyecto
Usa el comando cd para moverte a la ubicación donde crearás el repositorio.

Ejemplo:
cd Documentos

Si quieres crear una carpeta nueva para el proyecto:

mkdir mi_proyecto
cd mi_proyecto

## PASO 3 — Inicializar el repositorio Git
Aquí es donde empieza oficialmente el repositorio.

Comando:
git init

Este comando crea una carpeta oculta llamada .git que guarda toda la información y el historial de versiones.

La consola mostrará algo como:
Initialized empty Git repository in /ruta/de/tu/proyecto/.git/

## PASO 4 — Ver el estado del repositorio
Para ver qué archivos están siendo rastreados por Git se usa:

git status

Al inicio dirá que no hay commits y que los archivos están “untracked” (no seguidos).

## PASO 5 — Agregar archivos al repositorio
Primero creas o agregas archivos a la carpeta. Luego le dices a Git que los empiece a seguir.

Agregar un archivo específico:
git add archivo.txt

Agregar todos los archivos:
git add .

## PASO 6 — Hacer el primer commit
Un commit es como una “foto” de cómo están los archivos en ese momento.

Comando:
git commit -m "Primer commit"

Ese mensaje entre comillas describe los cambios que hiciste.

## RESUMEN DE COMANDOS PRINCIPALES

git init → Inicia el repositorio en la carpeta
git status → Muestra el estado de los archivos
git add . → Agrega todos los archivos al seguimiento
git commit -m "mensaje" → Guarda los cambios en el historial

En conclusión, crear un repositorio local significa preparar una carpeta para que Git controle los cambios de tus archivos. Desde ese momento puedes guardar versiones, volver atrás si algo falla y trabajar de forma organizada como lo hacen los desarrolladores profesionales.