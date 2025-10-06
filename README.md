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
