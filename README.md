# CuentasCRM

App PWA instalable de finanzas personales multipaís (🇧🇷 Brasil · 🇻🇪 Venezuela · 🇺🇸 EE.UU.).

Centraliza tarjetas de crédito y cuentas bancarias con consolidación multidivisa (USD/BRL/VES),
alertas de vencimiento escalonadas, lectura inteligente de estados de cuenta (OCR) y resúmenes visuales.

## Cómo usar

Abre la URL de GitHub Pages en Chrome (Android) y elige **"Agregar a pantalla de inicio"** para instalarla como app.

## Archivos

- `index.html` — la app completa (UI + lógica, un solo archivo).
- `manifest.webmanifest` — metadatos para instalación PWA.
- `sw.js` — service worker (funciona offline tras la primera carga).
- `icon-192.png`, `icon-512.png`, `icon-512-maskable.png` — íconos.
- `CuentasCRM_Documento_Maestro.md` — documento de diseño y arquitectura.

## Privacidad

Los datos se guardan localmente en el dispositivo (localStorage). El motor de OCR (pdf.js + Tesseract.js)
se descarga la primera vez desde CDN; los archivos que subes no salen del teléfono.

MVP v1 · 2026
