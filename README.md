# La IA ya está aquí: úsala con criterio

Webinar de **AcademIAS** para docentes (es-MX). Slidev, 16:9, ~42 min, dos ponentes.
Tesis: **usa la IA para _aumentar_ tu juicio, nunca para _delegarlo_.**
Guía de diseño: la **andragogía de Malcolm Knowles** (cada sección = un principio de aprendizaje adulto).

## Correr localmente

```bash
npm install
npm run dev      # abre en localhost:3030
```

- Presione `.` en el navegador o abra `/presenter` para las **notas del orador** (llevan el reparto `[GABY]` / `[HESUS]` y los tiempos).
- Export a PDF de respaldo para el Zoom: `npm run export` (genera `slides-export.pdf`).

## Estructura del deck (andragogía)

| # | Sección | Principio Knowles | Voz |
|---|---------|-------------------|-----|
| 0 | La IA ya está en tu aula | Necesidad de saber + motivación | Ambos |
| 1 | La nueva electricidad | Experiencia previa (analogía) | Gaby |
| 2 | No necesitas ser mecánico | Orientación / desmitificar | Hesus |
| 3 | Las 6 preguntas | Centrado en el problema | Ambos |
| 4 | Con criterio: hype vs realidad | Aprendiz autodirigido | Hesus |
| 5 | Empieza el lunes | Disposición / motivación interna | Gaby → Hesus |

## Marca (fuente de verdad)

Tokens tomados de `academia-consulting/assets/styles.css`:
azul `#023BF2`, papel `#FAFCFE`, navy `#0B1C45`, tinta `#0F1624`, amarillo `#EDF400`.
Tipos: **Archivo** (display), **IBM Plex Mono** (cuerpo/etiquetas), **Bodoni Moda** (wordmark).
Marco azul mate, grano de papel, viñetas cuadradas, duotono azul + grabados.
Layouts en `layouts/`; estilos en `styles/index.css`; utilidades en `uno.config.ts`.

## Pendiente (no incluido en esta versión)

- **Recetas** (prompts listos para docentes) — material aparte.
- **Ilustraciones** — hoy hay marca + diagramas + fotos; los `.ph` marcan huecos para
  ilustraciones mejores (electricidad: farolero, fábrica de vapor vs eléctrica, Niágara, línea rural).
- **Ejemplos/demos por slide** — se afinan al construir: preferir capturas + clips cortos y
  **proyectos/personas reales** por encima de demos en vivo sobre Zoom.

## Deploy

GitHub Pages vía `.github/workflows/deploy.yml` (build `--base /ia-con-criterio/`).
Repo destino: organización `academia-latam`.
