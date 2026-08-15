# MyM Soluciones

Sitio corporativo inspirado en [Eleconar](https://eleconar.com.ar/), construido con [Jekyll](https://jekyllrb.com/) y el tema [Minimal Mistakes 4.28.0](https://github.com/mmistakes/minimal-mistakes) para GitHub Pages.

## Estructura

- `index.html` — Página principal (hero, servicios, socios, contacto)
- `_config.yml` — Configuración del sitio y datos de contacto
- `_data/navigation.yml` — Menú de navegación
- `_includes/masthead.html` — Barra superior y navegación estilo Eleconar
- `_sass/custom.scss` — Estilos personalizados
- `assets/css/main.scss` — Entrada Sass del tema

## GitHub Pages

1. Subí el repositorio a GitHub.
2. En **Settings → Pages**, elegí la rama `main` como origen.
3. Si el sitio es un **Project Page** (`usuario.github.io/mymsoluciones`), actualizá en `_config.yml`:

   ```yaml
   url: "https://TU_USUARIO.github.io"
   baseurl: "/mymsoluciones"
   ```

4. Editá teléfono, email y WhatsApp en `_config.yml`:

   ```yaml
   phone: "+54 9 11 XXXX-XXXX"
   phone_link: "+54911XXXXXXXX"
   email: "info@tuempresa.com.ar"
   whatsapp: "54911XXXXXXXX"
   ```

## Desarrollo local

```bash
bundle install
bundle exec jekyll serve
```

Luego abrí `http://localhost:4000`.
