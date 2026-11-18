# ESTRUCTA – Sitio web

Este repositorio contiene únicamente el frontend público de ESTRUCTA.

## Archivos
- `index.html`: página web.
- `.nojekyll`: evita el procesamiento Jekyll de GitHub Pages.

## Datos y servicios
La página se comunica con Google Apps Script mediante la URL de implementación configurada en `index.html`. Los datos permanecen en Google Sheets/Drive; no subir a este repositorio archivos Excel, datos de clientes, pedidos, credenciales ni el código privado de Apps Script.

## Publicación
En GitHub: Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.

## Importante
Antes de anunciar el sitio, probar en el enlace de GitHub Pages: carga de cursos, formularios de contacto, pedidos y cualquier flujo de pago. La API de Apps Script debe estar desplegada con acceso adecuado y sus funciones públicas deben limitarse a las operaciones necesarias.
Actualización para activar la publicación de ESTRUCTA en GitHub Pages.
