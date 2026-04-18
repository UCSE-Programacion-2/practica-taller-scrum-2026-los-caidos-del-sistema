# GitHub Classroom — asignación grupal (equipos de 3)

Esta práctica está pensada para distribuirse con **GitHub Classroom**: cada equipo de **exactamente 3 alumnos** acepta la misma **assignment** y obtiene **un repositorio compartido** por grupo (misma mecánica que usarán en el proyecto integrador).

## 1. Publicar este repositorio como plantilla

1. Subir este contenido a un repositorio en la **organización** de la cátedra (por ejemplo `ucse-prog-ii/practica-taller-scrum`).
2. En GitHub: **Settings** → **General** → activar **Template repository** → Save.
3. (Recomendado) Descripción: “Práctica Scrum — Alquiler de vehículos — Grupos de 3 — Programación II”.

Los alumnos no clonan el template: Classroom crea una **copia nueva** por cada equipo al aceptar la tarea.

## 2. Crear la assignment en GitHub Classroom (docentes)

1. Entrar en [https://classroom.github.com](https://classroom.github.com) y elegir la **classroom** de la materia.
2. **New assignment**.
3. Título y fechas según el calendario del taller.
4. **Assignment type:** elegir **Group assignment** (trabajo en equipo).
5. **Define teams** (o equivalente según la UI actual):
   - Tamaño de equipo: **mínimo 3 y máximo 4**.
   - Si la classroom usa **team sets** (conjuntos de equipos), crear o elegir el set “Equipos-Prog2-2026” para no mezclar con otros cursos.
6. En **Starter code**, seleccionar el repositorio **template** del paso 1.
7. Visibilidad de los repos generados: **private** si la organización lo permite.
8. Publicar y copiar el **invitation link** para compartirlo en el aula (LMS, mail, etc.).

## 3. Qué hacen los alumnos (equipo de 3)

1. Cada integrante entra al **invitation link** con su cuenta de GitHub (la misma que usarán en la materia).
2. La **primera persona** del grupo suele **crear el nombre del equipo** al aceptar (ej. `Grupo-07`, `Equipo-Alfa`). Las otras dos **se unen al mismo equipo** cuando aceptan el link (no creen tres equipos distintos).
3. Verificar que las **tres** cuentas tienen acceso al mismo repositorio generado (un solo URL tipo `github.com/org/practica-taller-scrum-grupo-XX`).
4. Clonar ese repo en sus máquinas y seguir [00-preparacion.md](./00-preparacion.md) y el resto de [README.md](./README.md) del taller.

## 4. Roles sugeridos dentro del grupo de 3

Para imitar el taller docente sin ser 9 personas:

| Rol (en la sesión) | Cantidad en el grupo | Notas |
|--------------------|----------------------|--------|
| Product Owner | 1 | Prioriza backlog y redacta o valida historias. |
| Scrum Master | 1 | Tablero, milestones, facilita mover tarjetas y revisar DoD. |
| Developer | 1 (o rotan) | Ramas, commits, PR; el que no abrió el PR puede **aprobar** el PR del compañero. |

En la siguiente clase pueden **rotar roles**.

## 5. Qué NO hace Classroom por vos

Sigue siendo responsabilidad del equipo (como en el integrador):

- Crear **GitHub Projects** y columnas.
- Crear **labels** y **milestones** (ver [.github/labels.md](../../.github/labels.md)).
- Reglas de rama en la org (si la cátedra las exige).

Dejarlo explícito en el enunciado o en [01-sprint-setup.md](./01-sprint-setup.md).

## 6. Checklist post-aceptación (cada equipo de 3)

- [ ] Las tres personas abren el **mismo** URL del repositorio y ven la rama `main`.
- [ ] En **Settings → Collaborators and teams** (o “Manage access”) figuran los tres miembros con permiso de escritura.
- [ ] `README.md` raíz actualizado: nombre del equipo, **tres** integrantes con link a GitHub, link al **Project**.
- [ ] Tablero creado y enlazado desde el README.
- [ ] Milestone del mini sprint creado.
- [ ] Al menos un PR mergeado con revisión de **otro** integrante del grupo.

## 7. Ensayo docente (opcional)

Los docentes pueden crear un assignment de prueba “Equipo docente”, aceptar con tres cuentas o invitaciones de prueba, y usar ese repo como demo en vivo.

## 8. Relación con el proyecto integrador

La misma dinámica **Group assignment + repo compartido + PR con revisión** es la que se espera en el integrador; esta práctica adelanta solo el **dominio** (alquiler) y el alcance acotado del taller.
