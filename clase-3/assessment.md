## Tarea: Crear una Página Web Personalizada

En esta tarea, crearás una página web que describa quién eres. La página debe incluir un título con tu nombre, una lista no ordenada con tus hobbies, una imagen de ti mismo y una pequeña descripción sobre ti.

### Paso 1: Crear una Nueva Rama

1. Abre tu terminal y navega al directorio del repositorio del curso.
2. Crea una nueva rama con tu nombre:
   ```bash
   git checkout -b <nombre-de-tu-rama>
   ```

````

### Paso 2: Crear el Archivo HTML

1. Crea un nuevo archivo HTML con tu nombre como nombre de archivo dentro de la carpeta `clase-3`. Por ejemplo, si tu nombre es Juan Pérez, el nombre del archivo será `juan_perez.html`.
2. Abre el archivo HTML en tu editor de texto favorito.

### Paso 3: Estructura del HTML

1. Escribe la estructura básica de un documento HTML:
   ```html
   <!DOCTYPE html>
   <html lang="es">
     <head>
       <meta charset="UTF-8" />
       <meta name="viewport" content="width=device-width, initial-scale=1.0" />
       <title>Tu Nombre</title>
     </head>
     <body>
       <!-- Contenido de tu página -->
     </body>
   </html>
   ```

### Paso 4: Contenido de la Página

1. Agrega el título de la página con tu nombre:
   ```html
   <h1>Tu Nombre</h1>
   ```
2. Crea una lista no ordenada con tus hobbies:
   ```html
   <h2>Mis Hobbies</h2>
   <ul>
     <li>Hobby 1</li>
     <li>Hobby 2</li>
     <li>Hobby 3</li>
     <!-- Agrega más hobbies si lo deseas -->
   </ul>
   ```
3. Inserta una imagen tuya:
   ```html
   <img src="ruta/a/tu/imagen.jpg" alt="Tu Nombre" />
   ```
4. Escribe una pequeña descripción sobre ti:
   ```html
   <p>Descripción sobre ti...</p>
   ```

### Paso 5: Guardar y Confirmar los Cambios

1. Guarda los cambios en tu archivo HTML.
2. Vuelve a tu terminal.
3. Agrega el archivo al área de preparación y confirma los cambios:
   ```bash
   git add <nombre-de-tu-archivo.html>
   git commit -m "Añadido página web personalizada"
   ```

### Paso 6: Subir la Rama al Repositorio Remoto

1. Sube la nueva rama al repositorio remoto:
   ```bash
   git push origin <nombre-de-tu-rama>
   ```

### Paso 7: Crear una Solicitud de Extracción (Pull Request)

1. Ve al repositorio en GitHub.
2. Cambia a la nueva rama que acabas de crear.
3. Haz clic en el botón "Pull Request".
4. Completa la información requerida y envía la solicitud.

¡Felicidades! Has completado la tarea de crear tu propia página web personalizada.
````
