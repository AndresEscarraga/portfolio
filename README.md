# Portfolio Command Center

## Visualización local
Para visualizar la aplicación localmente:
1. Asegúrate de tener Python 3 instalado.
2. Desde la carpeta del proyecto ejecuta:
   ```bash
   python3 -m http.server 8000
   ```
3. Abre tu navegador y visita <http://localhost:8000> para ver el panel interactivo.
> Nota: Si prefieres otro puerto, cambia `8000` por el número de puerto disponible que quieras utilizar.

## Visualización en GitHub Pages
Si prefieres publicar el panel directamente desde GitHub y compartirlo sin necesidad de ejecutar un servidor local, puedes hacerlo con GitHub Pages:

1. Sube este repositorio a tu cuenta de GitHub.
2. En la pestaña **Settings** del repositorio, ve a la sección **Pages**.
3. En **Build and deployment**, selecciona la fuente **Deploy from a branch**.
4. Elige la rama que contiene este proyecto (por ejemplo, `main`) y la carpeta raíz (`/`).
5. Guarda los cambios y espera a que GitHub genere el sitio.
6. Una vez completado el despliegue, abre la URL que GitHub Pages te proporciona para navegar por el panel.

> Consejo: cada vez que actualices el contenido del repositorio, GitHub Pages reconstruirá automáticamente el sitio. Solo tienes que recargar la página publicada para ver los cambios.

## Cómo subir este repositorio a tu cuenta de GitHub
Sigue estos pasos para alojar el código en tu propia cuenta de GitHub:

1. **Crea un repositorio vacío en GitHub**
   - Inicia sesión en <https://github.com>.
   - Haz clic en el botón **New** (Nuevo) de la barra lateral izquierda o visita directamente <https://github.com/new>.
   - Asigna un nombre al repositorio (por ejemplo, `portfolio-command-center`) y deja la opción de inicializar con README desmarcada.
   - Presiona **Create repository**.

2. **Configura el repositorio local**
   - Abre una terminal en la carpeta que contiene este proyecto.
   - Comprueba el estado actual de Git:
     ```bash
     git status
     ```
     Si ves archivos sin seguimiento, confírmalos o elimínalos antes de continuar.

3. **Conecta tu repositorio local con GitHub**
   - Copia la URL `HTTPS` o `SSH` que GitHub te muestra después de crear el repositorio (por ejemplo, `https://github.com/tu-usuario/portfolio-command-center.git`).
   - En la terminal, agrega tu repositorio de GitHub como remoto:
     ```bash
     git remote add origin https://github.com/tu-usuario/portfolio-command-center.git
     ```
     Sustituye la URL por la de tu repositorio. Si ya existe un remoto llamado `origin`, actualízalo con:
     ```bash
     git remote set-url origin https://github.com/tu-usuario/portfolio-command-center.git
     ```

4. **Sube el código a GitHub**
   - Envía la rama principal al repositorio remoto:
     ```bash
     git push -u origin main
     ```
     Si tu rama se llama distinto (por ejemplo, `master`), reemplaza `main` por el nombre adecuado.

5. **Verifica en GitHub**
   - Actualiza la página del repositorio en GitHub y comprueba que los archivos aparezcan.
   - A partir de ahora puedes seguir trabajando localmente y usar `git add`, `git commit` y `git push` para enviar nuevos cambios.

> Tip: si necesitas colaborar con otras personas, puedes invitar colaboradores desde la pestaña **Settings → Collaborators** de tu repositorio en GitHub.
