# CLAUDE.md — Instrucciones persistentes del proyecto

## Regla de flujo de trabajo (OBLIGATORIA, sin excepción)

> **SIEMPRE** proponer un plan detallado y esperar autorización explícita del usuario ANTES de modificar cualquier archivo.
> Esto aplica a: estilos, HTML, JavaScript, estructura de carpetas, commits, pushes y cualquier otro cambio.
> No avanzar con ninguna acción de escritura hasta recibir un "adelante", "ok", "aprobado" o equivalente explícito.

## Proyecto

Landing page personal de Hernán H. — primer día en Caja 18 de Septiembre (vía Kibernum) y asistencia a V21 Open Fest y Chile Fintech Forum 2026.

Archivo principal: `index.html` (HTML + CSS + JS en un único fichero autocontenido).

## Decisiones de diseño acordadas

### Tema global (Chile Fintech Forum)
- Fondo base oscuro casi negro, acentos en **azul esmeralda** (`#00d4c0` teal-esmeralda).
- Todo el layout global (nav, hero, secciones, contact, footer) sigue este tema.

### Tarjeta Caja 18 de Septiembre
- Estructura en **blanco y azul bandera chilena** (`#003DA5`).
- **Rojo bandera chilena** (`#D52B1E`) en bordes destacados y elementos de énfasis.
- Es la ÚNICA tarjeta/componente que rompe con el tema oscuro global hacia el interior.

### Tarjeta V21 Open Fest
- Fondo **negro** (`#0a0a0a`) + detalles, bordes y textos en **verde pistacho** (`#93c572`).

### Tarjeta Chile Fintech Forum 2026
- Mantiene el tema oscuro global; acento esmeralda al expandir.

## Stack técnico

- HTML5 + CSS (custom properties / design tokens) + Vanilla JS.
- Sin frameworks externos de CSS (no Tailwind, no Bootstrap).
- Fuentes: Inter + JetBrains Mono (Google Fonts).
