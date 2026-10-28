# 📊 Salsa Tabú — Diccionario de Datos y Especificaciones de Packaging

Este directorio documenta el esquema de datos y metadatos de los 60 diseños de packaging generados bajo el estándar **Git-as-a-Database** del framework IN2TECHMX.

## 🗂️ Esquema JSON de Diseños (`cards.json`)

Cada tarjeta de diseño responde a la siguiente estructura determinista:

```json
{
  "id": "01-frascos-gourmet-clasica-01",
  "folder": "01-frascos-gourmet-clasica",
  "categoryName": "Frascos Gourmet Clásica (130g)",
  "title": "Diseño 01: Clásica Oro Mate Cilíndrico",
  "subtitle": "Frasco de vidrio pesado con fondo grueso, etiqueta negra mate y hot-stamping oro.",
  "badge": "CRISTAL ~130G",
  "specDetail": "Vidrio flint pesado 130g, tapa metálica twist-off negra mate con compuesto plastisol para pasteurización a baño maría.",
  "color": "#d4af37",
  "relPath": "01-frascos-gourmet-clasica/diseno-01-01-frascos-gourmet-clasica.jpg",
  "idx": 1
}
```

## 📐 Métricas Generales del Dataset
- **Total de Diseños:** 60 archivos JPG de alta fidelidad.
- **Dimensiones:** 1000 x 1000 px por tarjeta.
- **Espacio de Color:** RGB sRGB IEC61966-2.1.
- **Compresión:** JPEG Quality 94 con antialiasing Lanczos.
- **Gobernanza:** IN2TECHMX Governance Suite v2.0.
