# SALIDA DE ARTICULOS

#### 1. Objetivo del módulo

El módulo **Salida de Artículos** permite registrar la entrega o asignación de materiales, repuestos o herramientas desde el almacén hacia un destino específico (vehículo, personal o proveedor). Este registro **descuenta automáticamente el stock** del almacén y **deja constancia de a quién se entregaron los artículos**, con su respectivo valor, fecha y destino.

***

#### 2. Acceso al módulo

Desde el menú lateral, ingresar a:\
**Almacén / Taller → Salida de Artículos**

<figure><img src="../../../.gitbook/assets/image (372).png" alt=""><figcaption></figcaption></figure>

***

#### 3. Registro de nueva salida

Para registrar una salida de artículos:

1. Hacer clic en el botón **“+ Nuevo”**.
2. Se abrirá el formulario “Nueva Orden de Salida”.

<figure><img src="../../../.gitbook/assets/image (373).png" alt=""><figcaption></figcaption></figure>

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

<figure><img src="../../../.gitbook/assets/image (376).png" alt=""><figcaption></figcaption></figure>

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

<figure><img src="../../../.gitbook/assets/image (377).png" alt=""><figcaption></figcaption></figure>

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

<figure><img src="../../../.gitbook/assets/image (378).png" alt=""><figcaption></figcaption></figure>

***

#### 6. Recomendaciones

* Asegúrate de seleccionar correctamente el tipo de destino antes de guardar.
* Verifica que los artículos ingresados tengan suficiente stock.
* Imprime y archiva el ticket firmado como respaldo operativo.
* Este módulo es clave para controlar el consumo de materiales en mantenimiento, operaciones y logística.
