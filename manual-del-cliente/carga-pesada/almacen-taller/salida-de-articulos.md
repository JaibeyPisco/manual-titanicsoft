# SALIDA DE ARTICULOS

#### 1. Objetivo del módulo

El módulo **Salida de Artículos** permite registrar la entrega o asignación de materiales, repuestos o herramientas desde el almacén hacia un destino específico (vehículo, personal o proveedor). Este registro **descuenta automáticamente el stock** del almacén y **deja constancia de a quién se entregaron los artículos**, con su respectivo valor, fecha y destino.

***

#### 2. Acceso al módulo

Desde el menú lateral, ingresar a:\
**Almacén / Taller → Salida de Artículos**

📌 _Ver imagen de referencia: \[Imagen 1 – Vista general del módulo]_\
(Archivo: `f270e9fd-a330-40fd-bfab-aa47602865d5.png`)

***

#### 3. Registro de nueva salida

Para registrar una salida de artículos:

1. Hacer clic en el botón **“+ Nuevo”**.
2. Se abrirá el formulario “Nueva Orden de Salida”.

**3.1. Completar la sección Encabezado:**

* **Fecha**: Día de la salida.
* **Serie y Número**: Correlativo del documento (generado automáticamente o manual según configuración).
* **Orden de Trabajo/Taller** _(opcional)_: Si aplica a un mantenimiento o intervención específica.
* **Tipo Destino**: Seleccionar entre:
  * **Vehículo** (asignación a una unidad)
  * **Personal** (asignación a un trabajador)
  * **Proveedor** (entrega a proveedor externo)
* Según el tipo destino, llenar el campo correspondiente:
  * **Vehículo**: Placa de unidad
  * **Personal Responsable**
  * **Proveedor**
* **Mes de Liquidación** _(opcional)_

📌 _Ver imágenes de referencia: \[Imagen 2 y 3 – Formulario de orden de salida]_\
(Archivos: `acb9cc31-486b-4411-b465-cafd873b9361.png`, `8e9346d1-90e0-41ac-b4aa-10df014b53f9.png`)

***

**3.2. Completar la sección Detalle:**

1. Hacer clic en **“+ Agregar Nuevo Ítem”**.
2. Ingresar los siguientes campos por cada artículo:
   * **Nombre del artículo**
   * **Cantidad**
   * **Moneda**
   * **Tipo de cambio** _(si aplica)_
   * **Fecha de vencimiento** _(si aplica)_
   * **Costo unitario**
3. Puedes agregar una **observación general** si se requiere.

📌 _Ver imagen de referencia: \[Imagen 4 – Agregado de ítems]_\
(Archivo: `9d6428d6-5d74-4c28-b0f6-73deb5062096.png`)

***

**3.3. Confirmar y guardar**

* Marcar la casilla: **“Confirmo que los datos llenados en el formulario son correctos”**.
* Presionar el botón **“Guardar”** para registrar la salida.

***

#### 4. Generación del ticket de salida

Una vez registrada la salida, el sistema genera un documento tipo **Ticket o Formato A4** para impresión y respaldo físico.

Este documento incluye:

* Fecha y número de salida
* Tipo de destino
* Vehículo o personal asignado
* Detalle de los artículos entregados
* Total valorizado de la entrega

📌 _Ver imagen de referencia: \[Imagen 5 – Formato imprimible de salida]_\
(Archivo: `95f50d4d-c530-4b25-a2d2-dcf463a8002e.png`)

***

#### 5. Consulta de salidas registradas

En la vista principal del módulo se listan todas las salidas registradas. Puedes filtrar por fechas y visualizar:

* Estado del documento (ej. **Registrado**)
* Fecha, serie, número
* Orden de trabajo/taller asociada
* Tipo de destino
* Responsable
* Vehículo (si aplica)
* Importe total

📌 _Ver imagen de referencia: \[Imagen 6 – Registro de salidas almacenadas]_\
(Archivo: `95f50d4d-c530-4b25-a2d2-dcf463a8002e.png`)

***

#### 6. Recomendaciones

* Asegúrate de seleccionar correctamente el tipo de destino antes de guardar.
* Verifica que los artículos ingresados tengan suficiente stock.
* Imprime y archiva el ticket firmado como respaldo operativo.
* Este módulo es clave para controlar el consumo de materiales en mantenimiento, operaciones y logística.
