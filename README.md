# FacturaPro Suite (unificador-pdf)

Aplicación web de un solo archivo (`index.html`) para gestionar PDFs contables **100% en el navegador**, sin servidores.
Ábrela con doble clic en Edge/Chrome o publícala en GitHub Pages.

## Herramientas
1. **Extractor de facturas (1ª cara)**: carga masiva (archivos o carpeta), conserva solo la página 1 sin recomprimirla, descarga ZIP individual + PDF consolidado, y lee RUC, razón social, serie-número, fecha, moneda, subtotal, IGV y total (validando el dígito verificador del RUC). Tabla editable, exportación a Excel, OCR opcional (Tesseract.js) e IA opcional (Gemini).
2. **Unir PDFs**: une varios PDFs completos, con orden por arrastre.
3. **Dividir / extraer**: miniaturas seleccionables, rangos (`1, 3-5, 8-`), separar todo en ZIP, dividir cada N páginas, eliminar páginas.

## Privacidad
Todo se procesa localmente. Solo si activas la IA de Gemini (opcional, con tu propia clave gratuita) se envía la 1ª página a Google.
Las librerías (pdf-lib, JSZip, pdf.js, SheetJS, Tailwind) se cargan desde CDN, por lo que se necesita internet al abrir la página.
