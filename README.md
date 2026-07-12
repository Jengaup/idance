# IDANCE · Taller de Baile del Municipio de San Sebastián

Sitio web oficial de **IDANCE Performing Studio**, el taller de baile del
Municipio de San Sebastián, Puerto Rico. Página estática, moderna y llamativa,
con estética de escenario neón basada en los colores del logo.

🔗 **Redes:** [Facebook](https://www.facebook.com/idance.performingstudio/) ·
[Instagram @idanceperforming](https://www.instagram.com/idanceperforming/)

## 📁 Estructura

```
index.html            → página principal
assets/styles.css     → estilos (tema neón, responsive, accesible)
assets/script.js      → nav móvil, scroll-reveal, año dinámico
assets/Idancelogo.jpg → logo oficial (favicon, Open Graph y footer)
.nojekyll             → sirve la carpeta assets sin procesar con Jekyll
.github/workflows/    → despliegue automático a GitHub Pages
```

## 🚀 Publicar en GitHub Pages

Tienes dos opciones:

**Opción A — GitHub Actions (recomendada, ya incluida)**
1. Fusiona esta rama a `main`.
2. Ve a **Settings → Pages**.
3. En **Build and deployment → Source**, elige **GitHub Actions**.
4. El sitio se publica solo en cada push a `main`. La URL aparece en la
   pestaña **Actions** o en Settings → Pages.

**Opción B — Servir desde una rama**
1. Fusiona a `main`.
2. **Settings → Pages → Source: Deploy from a branch**.
3. Rama `main`, carpeta `/ (root)`. Guarda.

La URL será algo como: `https://<usuario>.github.io/idance/`

## ✏️ Personalizar

Todo el contenido está en `index.html`. Busca los comentarios `<!-- NOTA: ... -->`
para saber qué conviene ajustar con datos reales:

- **Logo:** `assets/Idancelogo.jpg` (ver `assets/README.md`).
- **Disciplinas:** ajusta las tarjetas a las clases reales del taller.
- **Contacto:** agrega teléfono, dirección exacta y correo cuando los tengas.
- **Fotos:** puedes añadir galería con imágenes reales de presentaciones.

Los colores de marca están al inicio de `assets/styles.css` (variables `--magenta`,
`--cyan`, `--yellow`, `--purple`).
