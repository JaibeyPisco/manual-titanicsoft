# MANTENIMIENTOS VEHICULOS

#### 1. Objetivo del módulo

El módulo “Mantenimiento de Vehículos” permite registrar de manera ordenada y detallada **todos los mantenimientos realizados a las unidades de transporte**, sean estos de tipo **preventivo** o **correctivo**. Este registro facilita el control de costos, programación de servicios, cumplimiento normativo y seguimiento de proveedores.

***

#### 2. Acceso al módulo

Desde el menú principal, ingresar a:\
**Almacén / Taller → Mantenimiento vehículos**

<figure><img src="../../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

***

#### 3. Registro de un nuevo mantenimiento

**Pasos para agregar un mantenimiento:**

1. Hacer clic en el botón **“+ Nuevo”** (ubicado en la parte superior derecha).
2. Se abrirá la ventana **“Nuevo Mantenimiento”**.

<figure><img src="../../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

**Completar los siguientes campos obligatorios:**

* **Taller Propio**: Marcar si el servicio fue realizado por un taller interno.
* **Fecha** del servicio.
* **Vehículo**: Seleccionar la unidad a la que se le realizó el mantenimiento.
* **Tipo**: Indicar si es **Preventivo** o **Correctivo**.
* **Mantenimiento**: Descripción general del servicio realizado (ej. Cambio de aceite), para que el sistema vaya verificando los mantenimientos, es importante que los registres en vehículo/vehículo, editar pestaña mantenimientos
* **Número de Documento**: Ingresar la serie y número del comprobante (ej. F001-001234).
* **Tipo de Pago**: Contado o crédito.
* **Proveedor**: Seleccionar proveedor o taller externo.
* **Moneda**: Generalmente SOLES o DÓLARES.
* **Tipo de Cambio**: Requerido si la moneda es extranjera.
* **Importe**: Monto total del servicio.
* **Días Crédito**: Número de días para pagar (si aplica).
* **Kilometraje de Vehículo**: Indicador al momento de la intervención.
* **Descripción**: Información adicional o resumen de la intervención.

<figure><img src="../../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

***

#### 4. Registro de problemas detectados

Debajo del formulario principal se encuentra una tabla para registrar **problemas detectados y su resolución**:

* Hacer clic en **“+ Agregar”**
* Ingresar el **problema identificado**
* Marcar si el problema fue **resuelto** (Sí/No)

Nota: Esto también lo puedes llenar en configuración/inconvenientes taller, donde podrás registrar los incovenientes más comunes

{% content-ref url="../configuracion/incovenientes-taller.md" %}
[incovenientes-taller.md](../configuracion/incovenientes-taller.md)
{% endcontent-ref %}

***

#### 5. Ejemplo de registro completo

Una vez llenados todos los campos, la pantalla mostrará un resumen como:

* Vehículo: ARI-731
* Tipo: Preventivo
* Mantenimiento: Cambio de aceite
* Proveedor: GRUPO ARISTRAICO.
* Importe: 11
* Kilometraje: 11 km
* Problema: “CAMBIO DE ACEITE” → Resuelto: Si

📌 _Ver imagen_

<figure><img src="../../../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

***

#### 6. Recomendaciones

* Verifica que los datos estén correctos antes de guardar el mantenimiento.
* Registra el kilometraje exacto para que el sistema pueda predecir mantenimientos futuros.
* Mantén actualizada la información del proveedor para una correcta trazabilidad.
* Utiliza el historial de mantenimientos para validar garantías o evaluar desempeño del vehículo.
