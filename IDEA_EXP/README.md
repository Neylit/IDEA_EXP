# IDEA_EXP — Página web con Quarto

## Archivos
- `_quarto.yml`: configuración del sitio web.
- `index.qmd`: contenido de la propuesta experimental.
- `styles.css`: estilos visuales.

## Cómo abrirlo en RStudio
1. Instala Quarto desde https://quarto.org/docs/get-started/ .
2. En RStudio, crea o abre un proyecto en la carpeta `IDEA_EXP`.
3. Copia estos archivos en la carpeta principal del proyecto.
4. Abre `index.qmd` y pulsa **Render** para generar el sitio.
5. Se creará la carpeta `docs/` con el sitio web listo para GitHub Pages.

## Publicar en GitHub Pages
1. Sube `_quarto.yml`, `index.qmd`, `styles.css` y la carpeta `docs/` al repositorio `IDEA_EXP`.
2. En GitHub abre `Settings` → `Pages`.
3. En **Build and deployment**, elige **Deploy from a branch**.
4. Selecciona la rama `main` y la carpeta `/docs`, y guarda.
5. Espera a que termine la publicación. La dirección normalmente será:
   `https://TU-USUARIO.github.io/IDEA_EXP/`
   Sustituye `TU-USUARIO` por tu nombre de usuario de GitHub.

Si GitHub no publica, revisa que `docs/index.html` exista y que la carpeta `/docs` esté seleccionada en Settings → Pages.
