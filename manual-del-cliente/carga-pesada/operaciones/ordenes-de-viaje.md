# ÓRDENES DE VIAJE

#### 🧾 Objetivo

Este módulo te permite gestionar todas las órdenes de viaje creadas, darles seguimiento, actualizarlas y monitorear el estado de cada transporte.

***

#### 📆 Filtros superiores

Antes de visualizar los datos puedes aplicar filtros por:

* **Fecha Desde / Hasta**
* **Orden de Viaje** (búsqueda por número o texto)
* **Tipo de Resultado de Búsqueda**: Finalizados, no finalizados, etc.

Haz clic en el botón naranja **Buscar** para aplicar los filtros.

***

#### 📋 Columnas del listado

| **Columna**    | **Descripción**                                                                     |
| -------------- | ----------------------------------------------------------------------------------- |
| **Acción**     | Permite editar o monitorear la orden.                                               |
| **G.O.**       | La rendición de gastos operativos                                                   |
| **Operación**  | Botón para iniciar, finalizar o retornar el viaje.                                  |
| **Estado**     | Estado actual del viaje (INICIADO, REGISTRADO, etc.).                               |
| **Cerrado**    | Indicador si la operación fue cerrada.                                              |
| **Monitoreo**  | Etiqueta que indica si se está monitoreando segun el control de trafico o monitoreo |
| **Fecha**      | Fecha de creación o ejecución del viaje.                                            |
| **Viaje**      | Código de la orden de viaje.                                                        |
| **Vehículo**   | Placa del vehículo asignado.                                                        |
| **Conductor**  | Nombre del conductor principal.                                                     |
| **Ruta**       | Trayecto programado.                                                                |
| **Tipo Carga** | Descripción del tipo de carga (general, sacos, diesel, etc.).                       |

> 🟢 _Estados como “INICIAR”, “FINALIZAR”, “RETORNAR” permiten acciones en tiempo real sobre el estado del viaje._\
> 🟡 _Etiquetas como “EN RUTA”, “DESCARGADO”, “INCIDENTE” indican el monitoreo del conductor y el seguimiento del transporte._

<figure><img src="../../../.gitbook/assets/image (319).png" alt=""><figcaption></figcaption></figure>

***

#### 🖨️ Funcionalidades adicionales

* **Imprimir**: Genera un resumen imprimible del listado.
* **Excel**: Exporta los datos mostrados a un archivo .xlsx.
* **Mostrar Columnas**: Personaliza qué columnas deseas visualizar.

***

### MANUAL DE USUARIO: CREACIÓN DE VIAJE Y ASIGNACIÓN DE ÓRDENES DE TRABAJO

#### Objetivo

Este manual explica paso a paso cómo registrar un nuevo viaje en el sistema TMS de Titanic Soft, incluyendo la asignación de órdenes de trabajo previamente registradas.



***

#### 1. Ingreso al módulo "Órdenes de Viaje"

Desde el menú lateral, dirigirse a: `Operaciones` > `Órdenes de Viaje` > Botón **"+Nuevo"**

Esto abrirá el formulario de **Nuevo Viaje**.

<figure><img src="../../../.gitbook/assets/image (323).png" alt=""><figcaption></figcaption></figure>

***

#### 2. Pestaña: ÓRDENES DE TRABAJO

En esta sección se asignan las órdenes de trabajo al viaje.

1. Haz clic en **"+Agregar"** para abrir la lista de órdenes disponibles.
2.  Se mostrará una ventana con las órdenes sin viaje asignado:

    * Fecha
    * Número
    * Cliente
    * Ruta
    * Cantidad
    * Guía Remitente
    * Moneda
    * Total Importe


3. Selecciona una o varias órdenes y haz clic en **"Agregar a Viaje"**..

<figure><img src="../../../.gitbook/assets/image (325).png" alt=""><figcaption></figcaption></figure>

1.  Las órdenes se agregarán a la tabla con sus valores para controlar:

    * Compartimiento
    * Cliente
    * Ruta
    * Importe, IGV, Total y Diferencia

    <figure><img src="../../../.gitbook/assets/image (326).png" alt=""><figcaption></figcaption></figure>

***

#### 3. Pestaña: ORDEN DE VIAJE

Completa los campos requeridos:

* **Fecha** del viaje
* **Serie / Número** (autogenerados)
* **Vehículo y Semirremolque**
* **Conductor y Conductor Auxiliar**
* **Ruta**, **Modalidad** y **Tipo de carga**
* **Cantidad** y **Número de contenedor** (si aplica)
* **Tipo de cambio** y **Moneda**

<figure><img src="../../../.gitbook/assets/image (327).png" alt=""><figcaption></figcaption></figure>

**Si es un viaje tercerizado:**

Nota: Un sarvicio tercerizado es cuando el vehiculo tiene el tipo de contratación tercera

* Completar: **Costo flete tercerizado**, **Total tercerizado**, **% detracción**, **IGV del tercero**
* Ingresar monto de adelanto (si aplica)
* Agregar detalles del viaje
* Agregar conceptos adicionales del servicio tercerizado desde el botón `+Agregar`

<figure><img src="../../../.gitbook/assets/image (328).png" alt=""><figcaption></figcaption></figure>

***

#### 4. Guardar el viaje

Una vez completadas todas las secciones:

* Revisa las órdenes asignadas, los importes y la ruta.
* Verifica que los campos obligatorios estén completos.
* Presiona el botón **Guardar**.

El sistema registrará el viaje con todas las órdenes asociadas.
