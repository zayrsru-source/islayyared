# IsLA & YaRED · La RED

Sitio web de La RED: Inicio, Nosotras, Nuestro libro, Blog y Contacto.

- Todo el sitio vive en `index.html`; las fotos y la portada están en `img/`.
- Las secciones se abren con `#inicio`, `#nosotras`, `#libro`, `#blog`, `#contacto` y `#unete`.
- Los formularios y botones abren WhatsApp (+52 1 81 3407 5051) con el mensaje ya escrito.

## Publicarlo con GitHub Pages
1. En el repositorio: **Settings → Pages**.
2. En *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
3. En un par de minutos el sitio queda en `https://<usuario>.github.io/<repositorio>/`.
4. Para usar `islayyared.com`, escribe el dominio en *Custom domain* y configura el DNS como indica GitHub.

## Cómo publicar en el blog
En `index.html`, busca `NUEVA PUBLICACIÓN`. Copia un `<article class="post">` completo y pégalo arriba del más reciente. Cambia:
- `id="post-N"` (el siguiente número) y `data-title` (la primera frase o el título).
- La fecha en `<time datetime="AAAA-MM-DD">`.
- La etiqueta (`ph-tag`) y el hashtag (`pa-tag`).
- Los párrafos dentro de `post-bd`. El primer párrafo se ve grande, como titular.

La liga directa a cada publicación es `https://islayyared.com/#post-N`.
