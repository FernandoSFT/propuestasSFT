# CSS — Referencia (v2 legacy)

Estos archivos CSS se mantienen como **referencia histórica** del diseño v2.

Desde **v3 Luxury (Mayo 2026)**, todas las propuestas HTML usan **CSS 100% inline** (self-contained).

## Cambios v3 Luxury

- **Tipografía**: Playfair Display (headings) + Inter (body) — ya no Nunito Sans
- **Logos**: SVG oro (dark bg) + SVG elegante (light bg) — ya no PNG
- **Nav**: Negro sticky con links dorados
- **Hero**: Full-width con overlay negro + nombre del cliente en dorado
- **CTA**: 3 botones (WhatsApp + Llamar + Email) sobre fondo negro
- **Fondos oscuros**: Todo el texto es dorado (`var(--st-accent)` / `var(--st-accent-light)`), NUNCA gris
- **Contenido**: 100% completo — nunca simplificar precios, habitaciones o regímenes

## Variables v3

```css
:root {
  --st-primary: #1B3A4B;
  --st-primary-light: #2A5468;
  --st-accent: #E8A838;
  --st-accent-light: #F2C56B;
  --st-accent-dark: #C88A1E;
  --st-bg: #FAFAF8;
  --st-bg-alt: #F0EFEB;
  --st-surface: #FFFFFF;
  --st-text: #2C3E50;
  --st-text-light: #5D6D7E;
  --st-text-muted: #95A5A6;
  --st-font-heading: 'Playfair Display', Georgia, serif;
  --st-font-body: 'Inter', system-ui, sans-serif;
}
```

## Plantillas v3

Ver `/plantillas/` para las 4 plantillas actualizadas:
- `plantilla-express.html` — 🟢 1 opción simple
- `plantilla-estandar.html` — 🔵 1-2 opciones, paquete completo
- `plantilla-comparativa.html` — 🟣 2-5 alternativas
- `plantilla-circuito.html` — 🟠 Multidestino, día a día
