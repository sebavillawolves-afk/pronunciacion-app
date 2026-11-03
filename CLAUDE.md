# Pronunciación en inglés — reglas del proyecto

App web instalable (PWA) de un solo archivo, publicada en GitHub Pages para usarla en iPhone desde la pantalla de inicio.

- `index.html` contiene toda la app (HTML, CSS, JavaScript y datos). No agregar frameworks, dependencias ni pasos de compilación.
- `sw.js` guarda la app en el teléfono para usarla sin internet. **Cada vez que cambie cualquier archivo, subir `VERSION` en `sw.js`** (v1 → v2…), o el teléfono seguirá mostrando la versión anterior.
- Si se agrega un archivo nuevo que la app necesite, sumarlo a la lista `FILES` de `sw.js`.
- No cargar recursos de otros dominios (fuentes, scripts, imágenes): la app debe funcionar sin conexión.
- El audio usa la voz del sistema (Web Speech API, `en-US`). No reemplazarlo por servicios externos.
- Después de cada cambio: commit con mensaje en español y `git push`. GitHub Pages publica solo.
- El usuario no es programador: explicar en español simple, sin jerga, y confirmar antes de borrar o renombrar el repositorio.
