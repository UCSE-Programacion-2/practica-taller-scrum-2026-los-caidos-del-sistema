# Trazabilidad: Módulos 1 y 2 + Manual GitHub ↔ repositorio

En **este** repositorio de práctica se replica la **estructura** del demo docente (issues, tablero, PR, sprints). El material largo del curso (Módulo 1, Módulo 2, Manual GitHub en Markdown) vive en el repo **`demo-proyecto-integrador`**, carpeta `docs/material-taller/`, para no duplicar archivos.

Tabla de **evidencia pedagógica**: qué concepto del material del taller se materializa en qué parte de este repo.

| Concepto / fuente | Dónde se evidencia en el repo |
|-------------------|------------------------------|
| Roles Scrum (PO, SM, Developers) | Guión de referencia docente: [guion-demostracion-docentes-referencia.md](guion-demostracion-docentes-referencia.md); issues con asignación y tablero. |
| Historia de usuario + INVEST | Template [.github/ISSUE_TEMPLATE/historia-de-usuario.yml](../../.github/ISSUE_TEMPLATE/historia-de-usuario.yml); [issues-semilla-sprint-0-1.md](issues-semilla-sprint-0-1.md). |
| Criterios Given / When / Then | Mismo template de historia; ejemplos en issues semilla. |
| Product Goal / épicas | [docs/product-brief.md](../product-brief.md); template Épica; labels `epic` / `feature` en [.github/labels.md](../../.github/labels.md). |
| Product Backlog vs Sprint Backlog | [tablero-y-automatizacion.md](tablero-y-automatizacion.md) + Manual GitHub en el repo demo (`docs/material-taller/Manual GitHub EcosistemaAgil.docx.md`). |
| Definition of Done | [docs/sprint-1/README.md](../sprint-1/README.md); DoD en template de historia. |
| Conventional Commits | [docs/convencional-commits.md](../convencional-commits.md); hook [.githooks/commit-msg](../../.githooks/commit-msg); workflow [conventional-commits.yml](../../.github/workflows/conventional-commits.yml). |
| PR + revisión | [.github/PULL_REQUEST_TEMPLATE.md](../../.github/PULL_REQUEST_TEMPLATE.md); [03-ejecucion-en-vivo.md](03-ejecucion-en-vivo.md). |
| Transparencia / inspección / adaptación | [04-review-retro.md](04-review-retro.md); material Módulo 1 en repo demo. |
| IA como copiloto (Módulo 2) | Módulo 2 en repo demo; recordatorio de revisión humana antes de merge. |
| Comment-Driven Development | Opcional en `frontend/` cuando avancen a código. |
| Tests + Copilot (Módulo 2) | Cuando agreguen lógica en `backend/`, enlazar pruebas según guía del integrador. |

## Lectura sugerida para alumnos (orden)

1. [docs/product-brief.md](../product-brief.md)  
2. Repo **demo docente** → `docs/material-taller/Modulo1.docx.md` (secciones 1.1–1.2)  
3. Repo **demo docente** → `docs/material-taller/Manual GitHub EcosistemaAgil.docx.md` (tablero + PR)  
4. [docs/sprint-0/README.md](../sprint-0/README.md) y [docs/sprint-1/README.md](../sprint-1/README.md)  
5. Repo **demo docente** → `docs/material-taller/Modulo2.docx.md` (Copilot y flujo de PR/commits)
