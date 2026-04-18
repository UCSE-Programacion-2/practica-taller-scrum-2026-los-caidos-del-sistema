# 03 - Ejecución en vivo (flujo Git + Scrum)

## Objetivo del paso

Practicar el flujo completo de ejecución de una tarea Scrum con GitHub.

## Tiempo estimado

25-30 minutos.

## Flujo obligatorio del alumno

Issue -> Tablero -> Rama -> Commit -> PR -> Review -> Merge -> Done

## Acciones (paso a paso)

1. Elegir una historia del `Sprint Backlog` (por ejemplo HU-01).
2. Asignarse la tarjeta y moverla a `In Progress`.
3. Crear rama desde `main`:
   - Ejemplo: `feat/hu-01-busqueda-por-fechas`
4. Realizar un cambio documental mínimo en el repo de práctica:
   - Ejemplo: agregar un archivo `entregables/hu-01.md` con definición funcional de la historia.
5. Crear commit semántico:
   - Ejemplo: `feat(hu-01): define flujo de busqueda por fechas`
6. Subir rama y abrir Pull Request.
7. En la descripción del PR incluir:
   - `Closes #ID_DE_ISSUE`
   - Resumen breve de qué se completó
8. Pedir revisión a **al menos un** compañero del grupo (en equipos de 3, quien no abrió el PR suele ser el revisor).
9. Al aprobarse, hacer merge a `main`.
10. Mover tarjeta a `Done` (o verificar automatización si aplica).

## Convenciones recomendadas

- Rama: `tipo/hu-xx-descripcion-corta`
- Commits:
  - `feat(...)`
  - `fix(...)`
  - `docs(...)`

## Resultado esperado

- Al menos 1 PR mergeado y vinculado a issue.
- Trazabilidad completa entre issue, rama, commit y PR.

## Si falla, revisar

- El PR no menciona `Closes #...`.
- Se trabajó directo sobre `main`.
- La tarjeta no estaba vinculada al issue correcto.
