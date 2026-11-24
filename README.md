# Rechnungen CH — App Web Instalable (PWA)

Aplicación web progresiva (PWA) 100% offline para gestionar facturas en Suiza (CHF), completamente en alemán (`de-CH`).

## Características
- **Instalable** en Android, iOS y PC (Windows/macOS/Linux) sin pasar por App Store ni Google Play.
- **Funciona sin conexión** gracias a `sw.js` (Service Worker) y sin dependencias externas.
- **Alertas de vencimiento**: amarillo (≤ 5 días), rojo (vencida), verde (pagada).
- **Entrada de facturas**: manual (con fecha de hoy por defecto), cámara directa, galería (una o varias fotos con lector de QR suizo) y archivos PDF.
- **Recálculo automático** al añadir, marcar como pagada o eliminar (`🗑️ Entfernen`) cualquier factura.

## Cómo instalarla en tu móvil o PC

Para que el navegador permita instalarla como app, solo necesitas servir la carpeta `rechnungen-ch-pwa/` por HTTPS (por ejemplo, subiéndola gratis a **GitHub Pages**, **Netlify Drop** o **Vercel**):

1. **Android (Chrome)**: abre la URL y pulsa el botón **📲 App installieren** (o menú ⋮ → *Instalar aplicación*).
2. **iPhone / iPad (Safari)**: abre la URL, pulsa el botón **Compartir** y elige **Añadir a pantalla de inicio**.
3. **PC (Chrome / Edge)**: abre la URL y pulsa **📲 App installieren** en la cabecera o el icono de instalación en la barra de direcciones.
