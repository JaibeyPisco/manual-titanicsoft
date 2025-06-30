---
description: >-
  Ajustes avanzados como el nombre lo dice, permite de manera rápida  realizar
  ciertas configuraciones en el sistema y modificar un poco el comportamiento.
---

# 🕵️‍♂️ AJUSTES AVANZADOS

## AJUSTES AVANZADOS

**Introducción** El módulo de **Ajustes Avanzados** en Titanic Soft está diseñado para proporcionar a los administradores la capacidad de ajustar y personalizar el comportamiento del sistema de forma rápida y eficiente. Este módulo es fundamental para optimizar la experiencia del usuario y la seguridad del sistema.

### Casilla General

<figure><img src="../../../.gitbook/assets/image (225).png" alt=""><figcaption></figcaption></figure>

**1. Restringir información por Locales Anexos**

* **Propósito**: Esta opción permite segmentar la visualización de las guías por locales, asegurando que solo el personal autorizado en cada local pueda acceder a ellas.
* **Configuración**:
  * Activa la casilla **Restringir información por Locales Anexos** para habilitar esta función.
  * Asegúrate de que los locales estén correctamente definidos en el sistema para que esta restricción funcione adecuadamente.

**2. Requerir ubicación de inicio de sesión obligatoriamente**

* **Propósito**: Mejorar la seguridad capturando la ubicación geográfica durante cada inicio de sesión.
* **Cómo Activar**:
  * Marca la casilla correspondiente.
  * Si tu dispositivo no proporciona información de ubicación automáticamente, consulta el [manual de activación de ubicación](https://manual.titanicsoft.com/manual-del-cliente/consultas-generales/el-dispositivo-no-ha-brindado-la-informacion-de-locacion) para configurar esta función manualmente.

**3. Cantidad de decimales en precio de venta**

* **Propósito**: Mantener la precisión en los cálculos de facturación.
* **Configuración**:
  * Establece la cantidad de decimales para el precio de venta en **7** para evitar errores de cálculo.
  * Es recomendable no modificar esta configuración sin consultar con un experto en facturación.

**4. Cambio de contraseña cada 90 días**

* **Propósito**: Fortalecer la seguridad del sistema mediante la renovación regular de las contraseñas de los usuarios.
* **Configuración**:
  * Activa la opción para que el sistema solicite a los usuarios cambiar sus contraseñas cada 90 días.

### Casilla facturación

<figure><img src="../../../.gitbook/assets/image (227).png" alt=""><figcaption></figcaption></figure>

**Activar Facturación Electrónica**

* **Propósito**: Asegurar que todos los comprobantes se envíen automáticamente a SUNAT.
* **Cómo Activar**:
  * Navega a **Configuración > Facturación**.
  * Activa la opción **Facturación Electrónica**.
  * Esta función debe estar habilitada antes de emitir cualquier comprobante para cumplir con los requisitos legales.

**2. Aplicar Detracciones**

* **Propósito**: Automatizar el cálculo de detracciones para facturas mayores 400 soles.
* **Cómo Configurar**:
  * Marca la casilla **Aplicar detracción a facturas mayores de 400 soles**.
  * El sistema calculará automáticamente la detracción correspondiente cuando emitas tus comprobantes.

**3. Editar Detalle de la Facturación**

* **Propósito**: Permitir la modificación de detalles en la facturación bajo circunstancias específicas.
* **Configuración**:
  * Por defecto, el sistema no permite modificaciones para mantener la integridad de la orden.
  * Si necesitas hacer cambios, marca la casilla **Editar detalle de la facturación**.
  * Ten en cuenta que cualquier modificación es bajo la responsabilidad de tu empresa y debe ser gestionada con cuidado.

**4. Personalización de la Impresión de Facturas**

* **Propósito**: Controlar la visualización de marcas de agua en facturas anuladas.
* **Cómo Configurar**:
  * Por defecto, las facturas anuladas incluyen una marca de agua como "ANULADO INTERNAMENTE" o "ANULADO CON NC: 00011".
  * Si prefieres que estas marcas no aparezcan, marca la casilla **Ocultar la marca de agua de "Anulado" en facturas anuladas**.

{% content-ref url="../../consultas-generales/configurar-series-a-utilizar-en-nubefact.md" %}
[configurar-series-a-utilizar-en-nubefact.md](../../consultas-generales/configurar-series-a-utilizar-en-nubefact.md)
{% endcontent-ref %}

{% content-ref url="../../consultas-generales/como-darse-de-alta-a-nubefact-ose.md" %}
[como-darse-de-alta-a-nubefact-ose.md](../../consultas-generales/como-darse-de-alta-a-nubefact-ose.md)
{% endcontent-ref %}

### Casilla de Operación

**1. Agregar nombre de artículo en descripción del ítem automáticamente**

* **Objetivo**: Automatizar la inclusión del nombre del artículo en la descripción de cada ítem en las órdenes de servicio y solicitar una descripción general adicional.
*   **Pasos**:



    * Activa la casilla junto a **Agregar nombre de artículo en descripción del ítem automáticamente**.

**2. Mostrar Información de tarifas y hacer los precios editables al agregar ítems**

* **Objetivo**: Permitir la visualización y edición de tarifas y precios al momento de agregar ítems a una orden.
* **Pasos**:
  * Marca la casilla **Mostrar Información de tarifas y los precios sean editables al agregar ítems a la orden**.

**3. Documento de Referencia (Obligatorio) para clientes jurídicos**

* **Objetivo**: Requerir un documento de referencia para clientes jurídicos al crear órdenes.
* **Pasos**:
  * Selecciona la opción **Documento de Referencia (Obligatorio)**.

**4. Solicitar clave de entrega al editar orden**

* **Objetivo**: Aumentar la seguridad al requerir una clave de entrega cada vez que se edita una orden.
* **Pasos**:
  * Activa la casilla **Solicitar clave de entrega al editar orden**.

**5. Tarifas de artículos por Rutas**

* **Objetivo**: Configurar tarifas específicas para artículos según la ruta de entrega.
* **Pasos**:
  * Marca la opción **Tarifas de artículos por Rutas**.

**6. Emitir GRT al generar O/S**

* **Objetivo**: Generar automáticamente un GRT (Guía de Remisión de Transportista) al crear una Orden de Servicio.
* **Pasos**:
  * Selecciona **Emitir GRT al generar O/S**.

**7. Preguntar Impresión Declaración Jurada**

* **Objetivo**: Consultar al usuario si desea imprimir una declaración jurada al completar una orden.
* **Pasos**:
  * Activa la casilla **Preguntar Impresión Declaración Jurada**.

#### Guías de Remisión

**8. Emisión Electrónica (GR-REMITENTE)**

* **Objetivo**: Habilitar la emisión electrónica de guías de remisión por parte del remitente.
* **Pasos**:
  * Marca la opción **Emisión Electrónica (GR-REMITENTE)**.

#### Guías de Transportista

**9. Al crear una nueva guía que se seleccione automáticamente el último vehículo, conductor y remolque**

* **Objetivo**: Facilitar la creación de nuevas guías seleccionando automáticamente el último vehículo, conductor y remolque utilizados.
* **Pasos**:
  * Activa la opción **Al crear una nueva guía que se seleccione automáticamente el último vehículo, conductor y remolque**.

#### Manifiesto de Carga

**10. Ocultar Importes de Dinero**

* **Objetivo**: Ocultar los importes de dinero en los manifiestos de carga para mayor privacidad.
* **Pasos**:
  * Marca la casilla **Ocultar Importes de Dinero**.

<figure><img src="../../../.gitbook/assets/image (228).png" alt=""><figcaption></figcaption></figure>

### Términos y condiciones

Puedes prefinir texto como condiciones que brindas al hacer un servicio: Ejemplo:

```
Cliente es el único responsable del embalaje de su mercadería.
El tiempo máximo de almacenaje de las encomiendas es de 6 meses, pasado este tiempo se considerará en abandono.
La empresa no revisa el contenido de mercadería.
La indemnización a favor de EL CLIENTE por una mercadería no sustentada con comprobantes de pago se regirá de acuerdo a lo estipulado en el Art.146 del D.S.032-2005- MTC, REGLAMENTO NACIONAL DE FERROCARRILES es decir que se abonara como única indemnización 10 veces el valor del servicio (FLETE) siempre y cuando guarde relación con lo enviado.
La empresa no asumirá penalidades, multas u otros que deriven de entregas efectuadas en un tiempo prudencial de acuerdo al destino.
```

<figure><img src="../../../.gitbook/assets/image (232).png" alt=""><figcaption></figcaption></figure>

### Columnas de embarque y desembarque

En esta sección podrás activar desactivar columnas que deseas mostrar en las  ordenes de servicio

<figure><img src="../../../.gitbook/assets/image (116).png" alt=""><figcaption></figcaption></figure>

Espero que este manual te sea de utilidad.
