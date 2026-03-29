
# Webquest RSA (2º ESO) — 100% en la web (Quarto Live)

Este sitio **no usa Google Colab**. Todo el código Python se ejecuta en el navegador con **Pyodide/WebAssembly** mediante **Quarto Live**.

## Publicación en GitHub Pages
1. Crea un repo y sube estos archivos.
2. Activa **Settings → Pages → Build and deployment: GitHub Actions**.
3. Haz `git push` a `main`. El workflow instalará `quarto-live`, renderizará y publicará.

> Si prefieres, puedes *vendorizar* la extensión para reproducibilidad:
>
> ```bash
> quarto add r-wasm/quarto-live
> git add _extensions/ && git commit -m "vendor: quarto-live"
> ```

## Estilos
Se usa **theme: cosmo** + `styles.css` (navbar azul y tipografía ajustada).
