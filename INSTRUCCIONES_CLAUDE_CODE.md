# Tarea: publicar esta app en GitHub Pages para instalarla en iPhone

Esta carpeta ya contiene una app web instalable lista para publicar (`index.html`, `manifest.webmanifest`, `sw.js`, `icons/`, `.nojekyll`). Lee también `CLAUDE.md`. No modifiques el contenido de `index.html`.

Pasos:

1. Verifica que `git` y la CLI de GitHub (`gh`) estén instalados y que `gh` tenga sesión iniciada (`gh auth status`). Si falta algo, guíame paso a paso en español para instalarlo e iniciar sesión (`gh auth login`, por navegador). No me pidas pegar contraseñas ni tokens en el chat.
2. Inicializa el repositorio en esta carpeta, con rama `main`, y haz el primer commit.
3. Pregúntame el nombre del repositorio antes de crearlo (sugerencia: `pronunciacion-ingles`). Créalo **público** en mi cuenta con `gh repo create` y sube el código. (GitHub Pages gratuito requiere repositorio público.)
4. Activa GitHub Pages desde la rama `main`, carpeta raíz (por ejemplo, con `gh api` sobre `repos/<usuario>/<repo>/pages`).
5. Espera a que el sitio quede publicado y verifica que respondan `index.html`, `manifest.webmanifest` y `sw.js` en la URL `https://<usuario>.github.io/<repo>/`.
6. Entrégame la URL final y estos pasos para instalarla en el iPhone:
   - Abrir la URL en **Safari** (no en otra app).
   - Tocar **Compartir** → **Agregar a pantalla de inicio** → **Agregar**.
   - Abrir la app una vez con internet; desde ahí funciona sin conexión.
7. Explícame en dos líneas cómo pedirte cambios en el futuro (recordando subir `VERSION` en `sw.js` y hacer push).
