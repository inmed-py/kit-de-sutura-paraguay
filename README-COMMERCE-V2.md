# InMed Kit de Sutura — versión Commerce v2

Sitio estático HTML/CSS/JS listo para GitHub Pages.

## Cambios principales
- Hero y CTAs orientados a compra.
- Barra de compra fija en mobile.
- Flujo mayorista y formulario mejorado.
- Atribución UTM preservada hasta WhatsApp.
- Eventos listos en `window.dataLayer` mediante `site-analytics.js`.
- Sin pixels/trackers externos activados por defecto.
- Sitemap completo con todos los artículos.
- Enlaces rotos de logo y captions corregidos.
- Structured data de producto depurado para evitar ratings/reviews no verificables en Schema.
- `product-feed.csv` listo como base para integraciones comerciales futuras.

## Analytics
`site-analytics.js` registra eventos en `window.dataLayer` y los reenvía a `gtag` si GA4/GTM se añade después. No requiere dependencias y no envía datos a terceros por sí solo.

Eventos principales: `page_view_custom`, `whatsapp_click`, `cta_click`, `generate_lead`, `scroll_depth`, `video_start`, `video_complete`.
