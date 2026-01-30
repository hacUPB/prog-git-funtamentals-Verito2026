# USO DE LA CONSOLA PARA NAVEGAR Y CREAR DIRECTORIOS Y ARCHIVOS

La consola o línea de comandos es una herramienta que permite comunicarnos con el sistema operativo mediante texto. En programación es muy importante porque permite manejar archivos y carpetas de forma rápida y profesional sin usar el mouse.

En esta unidad se aprendió a navegar entre carpetas, crear directorios, crear archivos y ver su contenido usando comandos básicos.

## NAVEGAR ENTRE DIRECTORIOS

Comando pwd — Mostrar la ruta actual
Sirve para saber en qué carpeta estamos ubicados.

### Ejemplo:
pwd

Resultado en pantalla:
/c/Users/Veronica/Documents

## Comando ls — Listar archivos y carpetas
Muestra todo lo que hay dentro de la carpeta actual.

### Ejemplo:
ls

Resultado:
tarea.txt proyecto notas.docx

## Comando cd — Cambiar de directorio
Se usa para entrar a una carpeta o retroceder.

Entrar a una carpeta:
cd proyecto

## Volver a la carpeta anterior:
cd ..

### Ejemplo completo:
cd proyecto
pwd

Resultado:
/c/Users/Veronica/Documents/proyecto

## CREAR DIRECTORIOS (CARPETAS)

Comando mkdir — Crear una nueva carpeta

### Ejemplo:
mkdir trabajos

Después si escribimos ls veremos:
trabajos

## CREAR ARCHIVOS

Comando touch — Crear un archivo vacío

### Ejemplo:
touch tarea1.txt

Si escribimos ls aparecerá:
tarea1.txt

## VER EL CONTENIDO DE UN ARCHIVO

Comando cat — Mostrar lo que hay dentro de un archivo

### Ejemplo:
cat tarea1.txt

Si el archivo está vacío, no mostrará nada.

## EDITAR ARCHIVOS DESDE LA CONSOLA

Comando vim — Abrir un archivo en el editor de texto Vim

### Ejemplo:
vim tarea1.txt

Este comando permite escribir y guardar cambios directamente desde la consola.

## LISTA DE LOS PRINCIPALES COMANDOS APRENDIDOS

pwd → Muestra la carpeta actual
ls → Lista archivos y carpetas
cd → Cambia de directorio
cd .. → Retrocede a la carpeta anterior
mkdir → Crea una nueva carpeta
touch → Crea un archivo vacío
cat → Muestra el contenido de un archivo
vim → Permite editar un archivo desde la consola

## CONCLUSIÓN

El uso de la consola facilita la navegación por el sistema, la organización de proyectos y la creación de archivos sin depender de la interfaz gráfica. Estos comandos son la base para trabajar con herramientas como Git y para desenvolverse mejor en el mundo de la programación.