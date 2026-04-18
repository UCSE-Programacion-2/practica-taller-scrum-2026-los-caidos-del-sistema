# Issues semilla — Sprint 0 y 1 (Rent&Go / alquiler de vehículos)

Textos para crear en GitHub usando los templates del repo (Épica, Historia de usuario). Ajustar números `#` al crear primero la épica.

---

## Épica E1 — Búsqueda y reserva por fechas

**Título:** `EPIC — Búsqueda y reserva de vehículos por fechas`

**Descripción:**  
Permitir que un cliente encuentre vehículos disponibles entre fecha de retiro y devolución y avance hacia la reserva. Alineado a [docs/product-brief.md](../product-brief.md) y al [caso de uso](../material-practica/caso-de-uso-alquiler-vehiculos.md).

---

## Sprint 0 — Historias / tareas sugeridas

### HU-S0-01 — README del equipo

**Historia:**  
Como **miembro del equipo** quiero un **README** con datos del equipo y enlace al tablero para que la cátedra pueda auditar el proyecto.

**Criterios de aceptación:**

- [ ] Dado el repositorio, cuando abro el `README.md`, entonces veo nombre del equipo e integrantes con link a GitHub.
- [ ] Dado el brief, cuando busco la referencia, entonces hay enlace a `docs/product-brief.md`.
- [ ] Dado el tablero, cuando sigo el link del README, entonces abro el GitHub Project del equipo.

**Rama sugerida:** `docs/readme-sprint0`

---

### HU-S0-02 — Relevamiento de contexto

**Historia:**  
Como **equipo** quiero documentar el contexto de una **agencia de alquiler ficticia** para fundamentar el diseño del Sprint 1.

**Criterios de aceptación:**

- [ ] Dado `docs/sprint-0/relevamiento.md`, cuando lo leo, entonces hay al menos tres necesidades alineadas al brief.
- [ ] Dado `docs/sprint-0/fotos/`, cuando reviso el relevamiento, entonces las imágenes tienen origen/licencia indicada.
- [ ] Dado `docs/sprint-0/logo/`, cuando reviso, entonces hay propuesta visual con justificación breve.

**Rama sugerida:** `docs/sprint0-relevamiento`

---

## Sprint 1 — Historia para demo de PR

### HU-S1-01 — Landing Rent&Go

**Historia:**  
Como **cliente** quiero una **landing** clara con acceso a la búsqueda de vehículos para entender el valor del servicio.

**Criterios de aceptación:**

- [ ] Dado la home estática, cuando la abro en móvil y desktop, entonces se ve navbar, mensaje principal y footer sin romper layout.
- [ ] Dado el CTA de búsqueda, cuando hago clic, entonces navego a la página de búsqueda maquetada.

**Épica padre:** `#<id-E1>`  
**Rama sugerida:** `feat/ui-home`

---

### HU-S1-02 — Búsqueda por fechas (UI)

**Historia:**  
Como **cliente** quiero **filtrar** por fechas de retiro/devolución y tipo de vehículo (mock) para ver resultados coherentes con el dominio.

**Criterios de aceptación:**

- [ ] Dado el formulario de búsqueda, cuando aplico filtros, entonces la grilla muestra al menos tres vehículos de ejemplo.
- [ ] Dado un resultado, cuando abro detalle, entonces veo tarifa diaria y total estimado (mock).

**Épica padre:** `#<id-E1>`  
**Rama sugerida:** `feat/ui-busqueda`
