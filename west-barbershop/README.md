# West Barber Shop · Landing page

Sitio estático (HTML + CSS + JS, sin build) para West Barber Shop, Plaza Norte, Tijuana.

## Estructura
```
index.html        # toda la página (estilos y scripts incluidos)
assets/logo.webp  # logo con fondo transparente
assets/local.webp # foto de la fachada
assets/favicon.png
```

## Funciones
- Bilingüe ES / EN (detecta el idioma del navegador y recuerda la elección).
- Menú de servicios con precios en MXN o USD.
- Promo de miércoles ($1 USD = $20 MXN) con calculadora y términos.
- Tarjeta de lealtad animada (7mo corte gratis) con cláusulas y vigencia.
- Reseñas de Google (4.9★, 265) y enlace al perfil.
- Agenda: formulario que abre WhatsApp con la solicitud lista (664 848 2494).
- Mapa de Google embebido, horario con estado "Abierto/Cerrado" en hora de Tijuana y botón "Cómo llegar".

## Publicar
1. Sube la carpeta a un repo de GitHub.
2. Cloudflare Pages → Create project → Connect to Git → selecciona el repo.
3. Framework preset: **None** · Build command: *(vacío)* · Output directory: `/`.

Para cambiar el número de WhatsApp, edita `const WA` en el `<script>` de `index.html`.
