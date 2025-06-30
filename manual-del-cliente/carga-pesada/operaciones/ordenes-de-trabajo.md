# ÓRDENES DE TRABAJO

#### 🧾 Objetivo

Este módulo permite registrar una nueva orden de transporte, visualizar sus estados (asignado, pagado) y consultar las guías de transportista emitidas.

***

#### 🗂️ Secciones principales de la orden

A continuación se describen los campos clave del formulario de registro:

**🔹 Orden de Servicio**

* **Serie / Número**: Se genera automáticamente.
* **Fecha**: Fecha del servicio de transporte.
* **Moneda** y **Tipo de cambio**: Seleccionar según el tipo de operación.

**🔹 Cliente y contacto**

* **Cliente**: Seleccionar el cliente principal del servicio.
* **Subcliente / Contacto del cliente**: Información adicional si aplica.

**🔹 Direcciones**

* **Dirección de partida** / **UBIGEO - Partida**
* **Dirección de llegada** / **UBIGEO - Llegada**

> 📌 _Estas direcciones serán utilizadas para autocompletar la guía del transportista._

<figure><img src="../../../.gitbook/assets/image (320).png" alt=""><figcaption></figcaption></figure>

***

#### 📦 Datos del servicio de transporte

* **Ruta**: Seleccionar desde el módulo `Configuración > Rutas & Tarifas > Rutas`.
* **Tarifa**: Seleccionar desde `Configuración > Rutas & Tarifas > Tarifas`.\
  El sistema llenará automáticamente la **cantidad en toneladas** y el **importe por tonelada**.
* **Monto extra**: Puedes sumar o restar un monto adicional al servicio.
* **N.º de asignación**: Código de seguimiento interno (si aplica).
* **FO N.º Parte**: Número de parte logística o de carga.
* **Descripción del producto** _(opcional)_: Indicar qué tipo de carga se transporta.

<figure><img src="../../../.gitbook/assets/image (321).png" alt=""><figcaption></figcaption></figure>

***

#### 📊 Totales y pesos

* **Total de la orden**: Se calcula automáticamente.
* **Importe a facturar**: Referencial para facturación.
* **Peso de ida / retorno (K)**: Completar si aplica.

***

#### ✅ Opciones finales

* **Crear viaje (Básico)**: Crea automáticamente la programación de viaje.
* **Agregar otros importes**: Permite registrar cargos adicionales.

***

#### 📌 Recomendaciones

* Verifica que la **ruta y tarifa estén registradas previamente** en configuración.
* Si tienes varios destinos o escalas, asegúrate de completar todos los UBIGEO.
* El sistema puede utilizar estos datos para autocompletar las **guías transportistas** posteriormente.

***

<figure><img src="../../../.gitbook/assets/imagen (33).png" alt=""><figcaption></figcaption></figure>

#### 📥 Botón "Guardar"

Una vez que toda la información esté completa y validada, presiona el botón **Guardar** para registrar la orden en el sistema.



### 📋 Listado de Órdenes Registradas

Después de **guardar la orden**, el sistema mostrará un listado general con todas las órdenes existentes. Este listado te permite **verificar el estado logístico, financiero y documental** de cada orden de transporte registrada.

#### 📑 Columnas del listado

A continuación se describen las columnas visibles en el listado:

| **Columna**                  | **Descripción**                                                   |
| ---------------------------- | ----------------------------------------------------------------- |
| **Fecha**                    | Fecha en que se registró la orden.                                |
| **Número**                   | Número de orden generado automáticamente (Serie - Número).        |
| **N.º Asignación**           | Código de asignación interna de la empresa (opcional).            |
| **Fecha Guía Transportista** | Fecha en la que se generó la guía asociada.                       |
| **Guía Transportista**       | Número o código de la guía emitida al transportista.              |
| **Orden de Viaje**           | Número de la programación de viaje asociada.                      |
| **Cliente**                  | Empresa contratante del servicio.                                 |
| **Subcliente**               | Cliente secundario (si aplica).                                   |
| **Orden Servicio Cliente**   | Código interno del servicio según el cliente.                     |
| **Ruta**                     | Ruta establecida para el traslado.                                |
| **Dirección de Llegada**     | Destino final de la carga.                                        |
| **Dirección de Partida**     | Punto de origen de la carga.                                      |
| **Referencia Carga Cliente** | Referencia interna del cliente sobre la carga.                    |
| **Moneda**                   | Moneda en la que se registró el servicio (por ejemplo: SOLES).    |
| **Total**                    | Monto total del servicio.                                         |
| **Importe**                  | Monto a facturar, considerando montos adicionales si los hay.     |
| **Tipo de Cambio**           | Tipo de cambio registrado si la moneda es diferente al sol.       |
| **Estado de Pago**           | Muestra si la orden ya fue pagada o si aún está pendiente.        |
| **Estado de Orden**          | Indica si la orden está pendiente, asignada, ejecutada o anulada. |
| **Peso de Ida (K)**          | Peso de la carga en el viaje de ida (en kilos).                   |
| **Peso de Retorno (K)**      | Peso del viaje de retorno si aplica.                              |
| **Factura**                  | Número del comprobante de facturación, si ya fue emitido.         |
| **Vehículo**                 | Placa o código del vehículo asignado a la orden.                  |

#### ✅ Funcionalidad del listado

Este listado te permite:

* Visualizar el estado general de todas las órdenes.
* Consultar rápidamente la información clave de cada servicio.
* Verificar si ya fue **asignada, ejecutada, pagada o facturada**.
* Ingresar a editar, imprimir o anular órdenes según los permisos disponibles.

***
