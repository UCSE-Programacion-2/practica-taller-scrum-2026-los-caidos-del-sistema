# Product Brief: Plataforma de alquiler de vehículos

## 1. Nombre del producto (práctica)

**Rent&Go** (nombre ficticio para el taller; el equipo puede renombrarlo).

## 2. Visión

Ofrecer una plataforma web que permita a los clientes buscar, reservar y pagar el alquiler de vehículos por un período definido en distintas sucursales, reduciendo fricción operativa y errores de disponibilidad.

## 3. Problema que resuelve

- Reservas y disponibilidad desalineadas entre sucursales.
- Tiempo perdido en consultas manuales de stock y precios.
- Dificultad para gestionar cancelaciones y reasignación de flota.

## 4. Usuarios objetivo

- **Cliente:** busca vehículo por fechas, sucursal y tipo; reserva y paga.
- **Empleado de la empresa de alquiler:** carga y mantiene vehículos, tarifas, estado de flota y ve reservas activas.
- **Administrador del sistema:** gestiona usuarios, sucursales y reportes básicos.

## 5. Épicas / funcionalidades clave

1. Gestión de usuarios (registro, login, roles).
2. Catálogo de vehículos y sucursales.
3. Búsqueda y filtros (ciudad, fechas de retiro/devolución, tipo, precio).
4. Reservas y disponibilidad por fechas.
5. Pagos (integración con sistema externo, a nivel conceptual en la práctica).
6. Gestión de flota (disponible, mantenimiento, fuera de servicio).
7. Administración y reportes (uso, ingresos, cancelaciones).

## 6. Analogía con ecommerce (útil para backlog)

| Ecommerce | Alquiler |
|-----------|----------|
| Producto | Vehículo |
| Stock | Disponibilidad por fecha |
| Precio | Tarifa por día |
| Carrito | Reserva |
| Checkout | Confirmación + pago |

## 7. Reglas de negocio (refinamiento)

- Un vehículo **no** puede tener dos reservas superpuestas.
- El precio se calcula por **cantidad de días** entre retiro y devolución.
- Cancelaciones dentro de las 24 h pueden tener penalidad (definir en documentación).
- Vehículos en mantenimiento **no** aparecen en búsquedas.

## 8. Fuera del MVP (para acotar el mini taller)

- Telemetría del vehículo en tiempo real.
- Programas de fidelidad complejos.
- Multimoneda y impuestos internacionales (salvo mención documental breve).

## 9. Fuente del caso

Documento ampliado del equipo docente / material de práctica: [docs/material-practica/caso-de-uso-alquiler-vehiculos.md](material-practica/caso-de-uso-alquiler-vehiculos.md).
