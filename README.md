# Grano Café (demo)

Sitio de una sola página para "Grano", cafetería de especialidad ficticia en Formosa Capital, Argentina. Pieza de demo/portfolio de [CEDETEC Digital](https://cedetec-digital.netlify.app/), para prospección en el rubro de cafeterías.

No representa un negocio real: nombre, dirección, teléfono y contenido son de ejemplo. Repo y sitio completamente independientes de otros proyectos de demo del portfolio: no comparten código, carpeta ni historial.

## Contenido

Sitio estático de un solo archivo (`index.html`, sin dependencias de build ni backend):

- Menú filtrable por categoría (cafés calientes, bebidas frías, pastelería).
- **Sistema de fidelidad (tarjeta de sellos digital)**: el cliente ingresa su WhatsApp para crear o recuperar su tarjeta, ve sus sellos acumulados (8 sellos = 1 café gratis), registra compras eligiendo un ítem del menú, y al completar la tarjeta se activa un cartel de premio y se reinicia el ciclo. Incluye historial de compras y canjes, todo persistido en `localStorage` por número de teléfono.
- Sección de valores del negocio y ubicación con mapa.

## Deploy

Al ser HTML estático, se puede publicar directo en GitHub Pages, Netlify o Vercel apuntando a la raíz del repo.
