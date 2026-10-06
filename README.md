# Calendario Comercial Hipotecario · Itaú

Herramienta web (un solo `index.html`, sin instalación) del equipo hipotecario para gestionar:

- Calendario de **eventos y comunicaciones**
- **Inventario y entregas** del kit de merchandising (pendones, manteles, kits)
- Panel resumen, listado con filtros, importación/exportación CSV y respaldo JSON

## Cómo funciona

Publicada con **GitHub Pages**. Los datos se guardan en la nube (JSONBin.io) para que todo el equipo vea la misma información.
La primera vez cada persona ingresa su nombre, la **Master Key** y el **BIN ID** (solo una vez por dispositivo).
Cada cambio se envía automáticamente y se mezcla con lo que haya guardado otra persona; sin conexión, queda en el equipo y se envía al reconectar.

## Actualizar la herramienta

Editar `index.html` en este repositorio (o reemplazarlo) y confirmar el cambio: GitHub Pages publica la nueva versión en ~1 minuto.
Los datos del equipo **no** se pierden al actualizar la página, porque viven en JSONBin.

> No se deben publicar aquí la Master Key ni el BIN ID.
