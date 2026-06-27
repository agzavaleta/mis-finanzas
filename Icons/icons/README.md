# Iconos PWA

Sube la carpeta `icons` a la raíz de tu proyecto.

En `manifest.json`, agrega o reemplaza:

```json
"icons": [
  {
    "src": "/icons/icon-192x192.png",
    "sizes": "192x192",
    "type": "image/png",
    "purpose": "any maskable"
  },
  {
    "src": "/icons/icon-512x512.png",
    "sizes": "512x512",
    "type": "image/png",
    "purpose": "any maskable"
  }
]
```

En `index.html`, dentro de `<head>`, agrega:

```html
<link rel="icon" href="/icons/favicon.ico" />
<link rel="apple-touch-icon" href="/icons/apple-touch-icon.png" />
```
