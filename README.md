# Guía de comidas saludables (Chile)

Página interactiva: marcas los ingredientes que tienes (o agregas los tuyos) y te sugiere recetas pensadas para cuidar la glicemia y prevenir diabetes tipo 2, con ingredientes fáciles de conseguir en Chile.

Es un solo archivo (`index.html`), sin dependencias ni servidor.

## Cómo publicarla en GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `guia-comidas-chile`), público.
2. Sube `index.html` y este `README.md` (botón Add file > Upload files).
3. Ve a Settings > Pages. En Source elige "Deploy from a branch", rama `main`, carpeta `/ (root)`, y guarda.
4. En 1 o 2 minutos tendrás la página en `https://TU-USUARIO.github.io/guia-comidas-chile/`.

## Cómo agregar recetas
Abre `index.html` y busca la lista `var R=[`. Cada receta tiene: `n` (nombre), `t` (tipo de comida), `i` (ingredientes), `s` (pasos) y `k` (consejo).

## Aviso
Guía orientativa. No reemplaza a un médico ni a un nutricionista.
