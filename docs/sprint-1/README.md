# Sprint 1 — Wireframes y maquetado estático (alquiler de vehículos)

## Objetivo

Traducir el Sprint 0 y el [Product Brief](../product-brief.md) en pantallas (wireframes) y **HTML/CSS estático** del flujo principal de alquiler.

Misma metodología que el integrador y el demo docente: **issues, ramas, PRs, sin push directo a `main`**.

## Errores comunes

Ver [errores-comunes.md](./errores-comunes.md).

## Entregables en `docs/sprint-1/`

1. `figma/` — link a Figma y exportaciones (mínimo 3 pantallas).
2. `wireframes/` — PNG/PDF por pantalla principal.
3. `decisiones-ui.md` — componentes, paleta, tipografías, estados.
4. `flujo/` — mapa de navegación (cliente, empleado, admin).
5. `resumen-sprint-1.md` — logros, 3 decisiones, 3 riesgos.

## Vistas obligatorias (mini práctica)

1. **Home / Landing** — valor del servicio, CTA a búsqueda.
2. **Búsqueda** — filtros por ciudad/sucursal, fechas retiro/devolución, tipo de vehículo (mock).
3. **Detalle de vehículo** — fotos, tarifa diaria, disponibilidad simulada.
4. **Reserva / carrito** — línea de tiempo del alquiler y total estimado (estático).
5. **Checkout** — formulario de datos y confirmación (sin pago real).
6. **Mis reservas** — listado mock y acción cancelar (UI).
7. **404**
8. **Backoffice empleado** — tabla de vehículos con acciones visuales y formulario “alta vehículo” (mock).

## Backlog sugerido (tarjetas = ramas)

1. `chore/initial-setup` — README, `.gitignore`, equipo.
2. `design/style-guide` — `variables.css` con tokens.
3. `feat/layout-base` — navbar y footer en todas las páginas.
4. `feat/ui-home` — landing.
5. `feat/ui-busqueda` — búsqueda con filtros mock.
6. `feat/ui-detalle-reserva` — detalle + flujo reserva/carrito estático.
7. `feat/ui-checkout-mis-reservas` — checkout y listado.
8. `feat/ui-backoffice` — tabla empleado + modal alta.

## Flujo de trabajo

1. Issue en GitHub + tarjeta en Projects.
2. Rama desde `main`.
3. Commits con [Conventional Commits](../convencional-commits.md).
4. PR con `Closes #N` en el cuerpo y revisión de un compañero.

## Entregable

Link al repo, al tablero, listado de PRs mergeados y URL de deploy estático si la cátedra lo pide.
