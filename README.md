# LEE 60 · IE 121 Virgen de Fátima (Rímac)

Plan de 1 hora diaria de lectura (MINEDU). App web estática (HTML + localStorage) que registra sesiones,
lecturas y respuestas en Google Sheets y lee la biblioteca (texto, PDF, imágenes) desde Google Drive.

## Archivos de este repositorio
- `index.html`: la aplicación completa
- `sw.js`: modo sin conexión
- `manifest.json`: permite instalarla como app
- `README.md`: este archivo

## Configuración
Al inicio del `<script>` de `index.html`:
- `URL_SHEETS`: URL `/exec` de tu Google Apps Script
- `TOKEN_SHEETS`: mismo token que `TOKEN` en `Code.gs`

`Code.gs` NO se sube a GitHub: se pega en Apps Script desde tu hoja de cálculo.

© 2026 EdTech - Ingeniería Educativa · Prof. Pedro Acevedo Elguera | IE 121 Virgen de Fátima - Rímac
