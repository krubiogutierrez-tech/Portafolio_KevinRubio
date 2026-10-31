# Portafolio — Kevin Rubio

Sitio estático. Publicar con GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

- `index.html` — página (los fondos de las diapositivas van incrustados).
- `assets/` — medios: `ilustraciones/`, `modelos/` (.glb) y `proyectos/<proyecto>/` (.webm / .gif).
- Rutas y posiciones de los medios: bloque `STATIC_MEDIA` dentro de `index.html`.
- Usa nombres en minúsculas: GitHub Pages distingue mayúsculas de minúsculas.
- Para probar en local usa un servidor (`python -m http.server`); con doble clic (`file://`) los modelos 3D no cargan.
