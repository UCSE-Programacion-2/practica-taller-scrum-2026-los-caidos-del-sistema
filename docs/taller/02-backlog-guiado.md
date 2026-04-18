# 02 - Backlog Guiado (caso alquiler de vehículos)

## Objetivo del paso

Construir un backlog inicial usable para un mini Sprint 1.

## Tiempo estimado

25-30 minutos.

## Fuente funcional obligatoria

Usar como base: [caso-de-uso-alquiler-vehiculos.md](../material-practica/caso-de-uso-alquiler-vehiculos.md)

## Acciones (paso a paso)

1. Crear 1 épica principal para el sprint de práctica.
2. Crear 2 historias de usuario hijas de esa épica.
3. Asignar labels (`feature`, prioridad).
4. Agregar las 3 tarjetas al tablero.
5. Mover al menos 2 historias a `Sprint Backlog`.

## Épica sugerida (copiar y ajustar)

**EPIC:** Búsqueda y reserva de vehículos por fechas.

**Objetivo:** Permitir que un cliente encuentre un vehículo disponible para un rango de fechas y pueda reservarlo.

## Historias sugeridas (usar en clase)

### HU-01

Como cliente, quiero buscar vehículos disponibles entre dos fechas, para alquilar uno durante mi viaje.

**Criterios de aceptación (Given/When/Then):**

- Dado que ingreso fecha de retiro y devolución, cuando ejecuto la búsqueda, entonces solo veo vehículos disponibles.
- Dado que existe disponibilidad, cuando veo resultados, entonces puedo identificar tipo de vehículo, sucursal y tarifa diaria.

### HU-02

Como cliente, quiero ver el precio total antes de confirmar la reserva, para saber cuánto voy a pagar.

**Criterios de aceptación (Given/When/Then):**

- Dado un vehículo y dos fechas, cuando solicito cotización, entonces el sistema calcula precio total por cantidad de días.
- Dado que cambio las fechas, cuando recalculo, entonces el total se actualiza.

## Priorización sugerida para el mini sprint

1. HU-01 (P1)
2. HU-02 (P1)
3. Task técnica: plantilla de PR y convenciones de ramas (P2)

## Resultado esperado

- 1 épica + 2 historias correctamente creadas.
- Tarjetas visibles y priorizadas en tablero.

## Si falla, revisar

- Historias demasiado grandes o ambiguas.
- Falta de criterios de aceptación verificables.
- No usar formato de historia estándar.
