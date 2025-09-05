README — Sitio One‑Page para Peluquería (Gratis)

Estructura
- index.html — página única con secciones: Hero, Servicios, Galería, Reserva, Contacto.
- styles.css — estilos con contraste AA, foco visible y tamaños táctiles adecuados.
- favicon.svg — icono simple.

1) Reemplaza tu enlace de reservas
- Si usas Calendly: en index.html busca `calendly-inline-widget` y reemplaza
  https://calendly.com/TU_USUARIO/TU_EVENTO
  por tu enlace real (Calendly → Share → Add to Website → Inline).
- Si prefieres Fresha o AgendaPro: borra el bloque Calendly y deja el botón
  con el link a tu perfil de reservas.

2) Cambia textos e imágenes
- Edita títulos, servicios y descripciones en index.html.
- En la galería, reemplaza las 4 URLs de picsum por tus fotos reales o sigue usando picsum.
- Escribe `alt` descriptivos (qué se ve + servicio).

3) Publicar GRATIS (dos opciones)

A) Netlify Drop (sin cuentas, súper rápido)
- Abre https://app.netlify.com/drop
- Arrastra la carpeta completa `peluqueria_site/`.
- Te entrega una URL pública inmediata. Crea cuenta si quieres mantenerla y customizar.
(Referencias: Netlify Drop docs.)

B) GitHub Pages (subdominio *.github.io)
- Crea un repositorio (p. ej., `peluqueria-site`) y sube estos archivos a la rama `main`.
- En Settings → Pages → Source = `Deploy from a branch`, Branch = `main` (o `/root`).
- Tu sitio quedará disponible en: https://TU_USUARIO.github.io/peluqueria-site/
(Referencias: GitHub Pages docs.)

4) Accesibilidad rápida
- Contraste mínimo 4.5:1 en texto normal.
- Un H1 en la página; H2 por sección; foco de teclado visible.
- Botones ≥44x44 px; sin auto‑play.
- Todas las imágenes con `alt` significativo.

5) SEO básico
- Edita `<title>` y `<meta name="description">`.
- Revisa Open Graph en el `<head>`.
- Crea un Google Business Profile y agrega tu enlace de reservas en el botón "Reservar".

6) Soporte WhatsApp e Instagram
- Edita el enlace de WhatsApp (incluye código de país sin +, p. ej. 569...).
- Cambia el `href` de Instagram por tu perfil.
