**🚗** Caso de Uso Scrum

## **Plataforma de Alquiler de Vehículos**

Idea general

Una **plataforma web/app** que permite a usuarios **buscar, reservar y pagar el alquiler de vehículos** (autos, motos, camionetas) por un período determinado, en distintas sucursales.

Funcionalmente es **muy similar a un ecommerce**, pero:

* Los “productos” se alquilan  
* Hay **disponibilidad por fechas**  
* El precio depende del **tiempo de uso**

Ideal para discutir **alcance, reglas de negocio y priorización**.

---

Objetivo del sistema

Facilitar el proceso de **alquiler de vehículos** conectando:

* Clientes  
* Empresas de alquiler  
* Administración del sistema

Permitiendo:

* Reservas por fechas  
* Gestión de disponibilidad  
* Cobros y cancelaciones

---

Actores

* **Cliente**  
* **Empleado de la empresa de alquiler**  
* **Administrador del sistema**  
* **Sistema de pagos externo**

---

 

 

Alcance funcional **(equivalente a ecommerce)**

**✅** Funcionalidades para Clientes

* Registro e inicio de sesión  
* Búsqueda de vehículos por:  
  * Ciudad / sucursal  
  * Fechas (retiro y devolución)  
  * Tipo de vehículo  
  * Precio  
* Ver detalle del vehículo  
* Ver disponibilidad por fechas  
* Calcular precio total del alquiler  
* Reservar vehículo  
* Pagar la reserva  
* Ver historial de alquileres  
* Cancelar una reserva (según política)

---

**✅** Funcionalidades para Empleados

* Alta y edición de vehículos  
* Asignar vehículos a sucursales  
* Definir tarifas por día  
* Marcar vehículos como:  
  * Disponible  
  * En mantenimiento  
  * Fuera de servicio  
* Ver reservas activas

 

---

**✅** Funcionalidades para Administradores

* Gestión de usuarios y empleados  
* Gestión de sucursales  
* Reportes básicos:  
  * Vehículos más alquilados  
  * Ingresos por período  
  * Reservas canceladas

---

Analogía directa con Ecommerce **(muy útil en Scrum)**

| Ecommerce clásico | Alquiler de vehículos |
| :---- | :---- |
| Producto | Vehículo |
| Stock | Disponibilidad por fecha |
| Precio | Tarifa por día |
| Carrito | Reserva |
| Checkout | Confirmación \+ pago |
| Envío | Fecha de retiro |
| Devolución | Fecha de devolución |

---

Épicas sugeridas

1. Gestión de usuarios  
2. Catálogo de vehículos  
3. Búsqueda y filtros  
4. Reservas  
5. Pagos  
6. Gestión de flota  
7. Administración y reportes

---

 

Ejemplos de Historias de Usuario

**🧑‍💼** Cliente

**Como cliente**, quiero **buscar vehículos disponibles entre dos fechas**, para **alquilar uno durante mi viaje**.

**Criterios de aceptación**

* Solo se muestran vehículos disponibles  
* El precio se calcula automáticamente según fechas

---

**Como cliente**, quiero **ver el precio total antes de confirmar**, para **saber cuánto voy a pagar**.

---

**Como cliente**, quiero **cancelar una reserva**, para **modificar mis planes**.

---

**👨‍🔧** Empleado

**Como empleado**, quiero **registrar vehículos nuevos**, para **ampliar la flota disponible**.

---

**Como empleado**, quiero **marcar un vehículo como en mantenimiento**, para **evitar que sea alquilado**.

---

**🛠️** Administrador

**Como administrador**, quiero **ver un reporte de ingresos mensuales**, para **evaluar el rendimiento del negocio**.

---

 

Backlog inicial **(ideal para Sprint 1\)**

1. Registro de cliente  
2. Login  
3. Alta de vehículos (básica)  
4. Listado de vehículos disponibles  
5. Búsqueda por fechas  
6. Reserva sin pago  
7. Cálculo de precio básico

👉 Con esto podés trabajar:

* Priorización  
* Estimación  
* Sprint Planning  
* Definición de MVP

---

Reglas de negocio **(excelentes para refinamiento)**

* Un vehículo **no puede tener dos reservas superpuestas**  
* El precio se calcula por **cantidad de días**  
* Cancelaciones dentro de las 24 h pueden tener penalidad  
* Vehículos en mantenimiento no aparecen en búsquedas

---

Variantes para agregar complejidad **(si el taller lo requiere)**

* Seguro opcional  
* Multa por devolución tardía  
* Descuentos por alquiler largo  
* Diferente tarifa por sucursal  
* Extras (GPS, silla infantil)

 

