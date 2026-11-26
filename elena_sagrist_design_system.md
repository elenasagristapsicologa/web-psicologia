---
name: "Elena Sagristá Psicología — Identidad Editorial"
description: "Sistema de diseño editorial, artístico y asimétrico para la práctica psicoterapéutica de Elena Sagristá. Inspirado en publicaciones independientes y marcas de bienestar con fuerte impronta humana."
---

## Overview

Este sistema de diseño digital evoluciona la identidad de Elena Sagristá hacia una experiencia puramente editorial y artística. Huyendo deliberadamente de los esquemas simétricos, las tarjetas homogéneas y los clichés visuales de plantillas automatizadas, este universo se inspira en estudios creativos contemporáneos (*Everbe*, *De La Tierra Wellness*, *Jaree Basgall*).

Se articulan tres pilares visuales inconfundibles:
1. **El corazón floral:** El logotipo e icono anatómico-botánico original de Elena, empleado como sello de autenticidad, emblema y remate editorial.
2. **Las matrioskas reales:** Metáfora viva del Sistema de la Familia Interna (IFS), el apego y las capas de la historia vital, integradas con variaciones de escala, recortes y superposiciones.
3. **Composición asimétrica y tipografía expresiva:** Grandes contrastes de escala, citas de gran formato, bloques de texto en prosa libre, notas al margen y ritmos que combinan densidad reflexiva con generosos silencios visuales.

## Colors

La paleta conserva las señas de identidad esenciales de Elena: el beige cálido (#E1D7C7) y el granate terroso (#664242). Se enriquece con terracota tostado (#8C5E58), marfil satinado (#FAF7F2), blanco roto (#FDFBF7), verde hoja desaturado (#4F5D48) procedente del bordado de las matrioskas, y tinta café profunda (#2A1E1E) para contraste WCAG 2.2 AA superior a 6:1.

```yaml
colors:
  brand-beige: "#E1D7C7"
  brand-garnet: "#664242"
  sand: "#EDE4D6"
  dusty-rose: "#C99B90"
  moss-green: "#4F5D48"
  light:
    primary: "#664242"
    on-primary: "#FFFFFF"
    primary-container: "#F0E4E1"
    on-primary-container: "#3C2121"
    secondary: "#7A4E48"
    on-secondary: "#FFFFFF"
    secondary-container: "#F5ECE9"
    on-secondary-container: "#3A211E"
    tertiary: "#5C6B55"
    on-tertiary: "#FFFFFF"
    surface: "#FAF7F2"
    on-surface: "#2A1E1E"
    surface-variant: "#EFE8DC"
    on-surface-variant: "#4A3A38"
    surface-container-low: "#F5EFE7"
    surface-container: "#EBE3D6"
    surface-container-high: "#E1D7C7"
    outline: "#63504D"
    outline-variant: "#D3C5BC"
    background: "#FDFBF7"
    on-background: "#2A1E1E"
    error: "#9E2A2B"
    on-error: "#FFFFFF"
```

## Typography

Una combinación tipográfica con marcado pulso literario:
- **Playfair Display:** Para titulares rotundos, citas poéticas y encabezados de capítulo.
- **Poppins:** Para texto corrido, datos de consulta y navegación.
- **Red Hat Mono:** Para anotaciones al margen, folios editoriales y marcadores de fase.

```yaml
typography:
  display-lg:
    fontFamily: "Playfair Display"
    fontSize: 56px
    fontWeight: 600
    lineHeight: 64px
    letterSpacing: -0.5px
  display-lg-mobile:
    fontFamily: "Playfair Display"
    fontSize: 34px
    fontWeight: 600
    lineHeight: 40px
    letterSpacing: -0.25px
  display-md:
    fontFamily: "Playfair Display"
    fontSize: 42px
    fontWeight: 600
    lineHeight: 50px
    letterSpacing: -0.5px
  display-md-mobile:
    fontFamily: "Playfair Display"
    fontSize: 28px
    fontWeight: 600
    lineHeight: 34px
    letterSpacing: -0.2px
  headline-lg:
    fontFamily: "Playfair Display"
    fontSize: 34px
    fontWeight: 600
    lineHeight: 42px
    letterSpacing: -0.25px
  headline-lg-mobile:
    fontFamily: "Playfair Display"
    fontSize: 26px
    fontWeight: 600
    lineHeight: 32px
    letterSpacing: -0.15px
  headline-md:
    fontFamily: "Playfair Display"
    fontSize: 28px
    fontWeight: 500
    lineHeight: 36px
  headline-md-mobile:
    fontFamily: "Playfair Display"
    fontSize: 22px
    fontWeight: 500
    lineHeight: 28px
  headline-sm:
    fontFamily: "Playfair Display"
    fontSize: 22px
    fontWeight: 500
    lineHeight: 30px
  title-lg:
    fontFamily: "Poppins"
    fontSize: 20px
    fontWeight: 500
    lineHeight: 28px
  title-md:
    fontFamily: "Poppins"
    fontSize: 18px
    fontWeight: 500
    lineHeight: 26px
  body-lg:
    fontFamily: "Poppins"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 28px
    letterSpacing: 0.1px
  body-md:
    fontFamily: "Poppins"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 24px
    letterSpacing: 0.15px
  body-sm:
    fontFamily: "Poppins"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 20px
    letterSpacing: 0.2px
  label-lg:
    fontFamily: "Poppins"
    fontSize: 15px
    fontWeight: 500
    lineHeight: 22px
    letterSpacing: 0.25px
  label-md:
    fontFamily: "Poppins"
    fontSize: 13px
    fontWeight: 500
    lineHeight: 18px
    letterSpacing: 0.3px
  label-sm:
    fontFamily: "Poppins"
    fontSize: 11px
    fontWeight: 500
    lineHeight: 16px
    letterSpacing: 0.4px
```

## Layout & Spacing

Ritmo asimétrico y libre:
- Alternancia de fondos completos (lienzo claro, beige táctil #E1D7C7 y granate solemne #664242).
- Ruptura intencionada de la cuadrícula: textos superpuestos a imágenes, márgenes desalineados con elegancia, sangrías francesas en citas.
- Anchuras diferenciadas: columnas estrechas para reflexiones íntimas, franjas expansivas para títulos y fotografías vivas.

```yaml
spacing:
  gutter-xs: 4px
  gutter-sm: 8px
  gutter-md: 16px
  gutter-lg: 24px
  gutter-xl: 32px
  gutter-2xl: 48px
  section-sm: 64px
  section: 96px
  section-lg: 128px
  page-margin: 24px
```

## Elevation & Depth

La profundidad se genera mediante capas físicas del plano: recortes de imágenes con bordes vivos, fondos de tono sobre tono, y sombras ópticas casi imperceptibles.

## Shapes

Líneas limpias, bordes orgánicos sutiles (redondeo discreto de 4 a 12px) y siluetas libres inspiradas en el papel editorial.

```yaml
rounded:
  sm: 4px
  DEFAULT: 8px
  md: 12px
  lg: 20px
  xl: 32px
  full: 9999px
```

## Motion & Micro-interaction

Microinteracciones lentas y orgánicas, emulando la cadencia de una lectura atenta y pausada.

```yaml
motion:
  state-change:
    duration: 150ms
    delay: 0ms
    timingFunction: ease-out
  surface-enter:
    duration: 350ms
    delay: 0ms
    timingFunction: cubic-bezier(0.16, 1, 0.3, 1)
  surface-exit:
    duration: 200ms
    delay: 0ms
    timingFunction: cubic-bezier(0.4, 0, 1, 1)
```

## Voice & Content Strategy

Autenticidad absoluta: la voz de Elena Sagristá, sin simplificaciones ni resúmenes cosméticos.

## Components

- `components/button.html`
- `components/card.html`
- `components/typography.html`
- `components/input-field.html`
