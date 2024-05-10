## Cómo Contribuir al Repositorio en GitHub

1. **Clonar el Repositorio:**

   - Abre tu terminal y navega a la carpeta donde deseas clonar el repositorio.
   - Ejecuta el siguiente comando:
     ```bash
     git clone <URL-del-repositorio>
     ```

2. **Crear una Nueva Rama:**

   - Navega al directorio del repositorio clonado usando `cd`.
   - Crea una nueva rama con un nombre descriptivo (por ejemplo, `añadir-nombres`):
     ```bash
     git checkout -b añadir-nombres
     ```

3. **Editar el README.md:**

   - Abre el archivo `README.md` en tu editor de texto favorito.
   - Añade tu nombre a la lista de estudiantes siguiendo el formato adecuado.
   - Añade tu usuario y link del perfil de GitHub siguiendo el formato adecuado.

4. **Guardar los Cambios:**

   - Guarda los cambios en el archivo `README.md`.
   - Vuelve a tu terminal.

5. **Agregar y Confirmar los Cambios:**

   - Agrega los cambios al área de preparación:
     ```bash
     git add README.md
     ```
   - Confirma los cambios:
     ```bash
     git commit -m "Añadido nombre de estudiante"
     ```

6. **Subir la Rama al Repositorio Remoto:**

   - Sube la nueva rama al repositorio remoto:
     ```bash
     git push origin añadir-nombres
     ```

7. **Crear una Solicitud de Extracción (Pull Request):**
   - Ve al repositorio en GitHub.
   - Cambia a la nueva rama que acabas de crear.
   - Haz clic en el botón "Pull Request".
   - Completa la información requerida y envía la solicitud.
