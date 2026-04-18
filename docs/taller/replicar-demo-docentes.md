# Cómo replicar lo del demo docente en esta práctica

El repositorio **demo-proyecto-integrador** muestra el flujo completo con el caso **TurniMed**. Este repo (**practica-taller-scrum**) tiene la **misma estructura** (raíz, `docs/`, `docs/sprint-*`, `docs/taller/`, `.github/`, `scripts/`, `backend/`, `frontend/`) pero el dominio es **Rent&Go** (alquiler de vehículos).

## Tabla de correspondencia

| Paso en el demo docente (TurniMed) | Qué hacés acá (alquiler) | Dónde |
|-----------------------------------|--------------------------|--------|
| Presentar `docs/product-brief.md` | Leer [docs/product-brief.md](../product-brief.md) | Brief Rent&Go |
| Material curricular en `docs/material-taller/` | Módulos y manual: usá el **mismo** material en el repo `demo-proyecto-integrador` (no se copia acá para no duplicar) | Referencia externa |
| Crear tablero + columnas + labels + milestones | Igual: [01-sprint-setup.md](./01-sprint-setup.md) | GitHub |
| Issues semilla TurniMed | Issues semilla alquiler: [issues-semilla-sprint-0-1.md](./issues-semilla-sprint-0-1.md) | GitHub Issues |
| Sprint 0 relevamiento centro salud | Sprint 0 relevamiento **agencia de alquiler** ficticia: [docs/sprint-0/README.md](../sprint-0/README.md) + [ejemplo-relevamiento-sprint-0.md](./ejemplo-relevamiento-sprint-0.md) | `docs/sprint-0/` |
| Sprint 1 vistas TurniMed | Sprint 1 vistas alquiler: [docs/sprint-1/README.md](../sprint-1/README.md) | `docs/sprint-1/` + `frontend/` |
| PR con `Closes #N` + hooks commits | Idéntico: [03-ejecucion-en-vivo.md](./03-ejecucion-en-vivo.md) + [docs/convencional-commits.md](../convencional-commits.md) | Git + GitHub |
| GitHub Classroom (template + assignment) | **Group assignment**, equipos de **3**: [github-classroom-y-template.md](./github-classroom-y-template.md) | Classroom + un repo por equipo |

## Regla simple para alumnos

**Misma cadena de herramientas y ceremonias, otro dominio.** Si entendés el flujo acá, el integrador real solo cambia el producto y la profundidad técnica.
