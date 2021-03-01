---
title: Conceptos y Términos
add_breadcrumbs: 1
show_sidebar: 0

metatags:
 description: Antes de comenzar la implementación, familiaricémonos con la terminología que se utiliza y algunos conceptos básicos en ERPNext.
 keywords: frappe, nuevas características erpnext, erp, erp de código abierto, erp gratuito, seguridad, documentación
---

# Conceptos y Términos

Antes de comenzar la implementación, familiaricémonos con la terminología que se utiliza y algunos conceptos básicos en ERPNext.

* * *

### Conceptos básicos

#### Compañía

Esto representa los registros de la empresa para los que está configurado ERPNext. Con esta misma
configuración, puede crear varios registros de la empresa, cada uno de los cuales representa un
entidad legal. La contabilidad de cada Compañía será diferente, pero compartirán los registros de Cliente, Proveedor y Artículo.

> Configuración > Compañía

#### Cliente

Representa a un cliente. Un cliente puede ser un individuo o una organización.
Puede crear varios contactos y direcciones para cada cliente.

> Ventas > Cliente

#### Proveedor

Representa a un proveedor de bienes o servicios. Su compañía telefónica es un Proveedor, también lo es su Proveedor de materias primas. Una vez más, un Proveedor puede ser un individuo o una organización y tiene múltiples contactos y direcciones.

> Compras > Proveedor

#### Producto

Un producto, subproducto o servicio que se compra, vende o fabrica y se identifica de forma única.

> Almacén > Producto

#### Cuentas

Una cuenta es un encabezado bajo el cual las transacciones financieras y comerciales se llevan a cabo. Por ejemplo, "Gastos de viaje" es una cuenta, "Cliente Zoe", "Proveedor Mae" son cuentas. ERPNext crea cuentas para Clientes y
Proveedores de forma automática.

> Contabilidad > Plan Contable

#### Dirección

Una dirección representa los detalles de la ubicación de un Cliente o Proveedor. Estos pueden ser de diferentes ubicaciones como la oficina central, la fábrica, el almacén, la tienda, etc.

> Ventas > Dirección

#### Contacto

Un contacto individual pertenece a un cliente o proveedor o es simplemente un autónomo. Un contacto tiene un nombre y detalles de contacto como correo electrónico y número de teléfono.

> Ventas > Contacto

#### Comunicación

Una lista de todas las comunicaciones con un contacto o cliente potencial. Todos los correos electrónicos enviados desde el sistema se añaden a la tabla de comunicación.

> Soporte > Comunicación

#### Lista de Precios

Una lista de precios es un lugar donde se pueden almacenar diferentes planes de tarifas. Es un nombre que se da a un conjunto de precios de artículos almacenados en una lista en particular.

> Ventas > Lista de precios

> Compras > Lista de precios

* * *

### Contabilidad

#### Año Fiscal

Representa un año financiero o un año contable. Puede operar varios años fiscales al mismo tiempo. Cada año fiscal tiene una fecha de inicio y una fecha final y las transacciones sólo pueden registrarse en este período. Cuando "cierras" un año fiscal, sus saldos se transfieren como saldos "de apertura" para el próximo año fiscal.

> Configuración > Compañía > Año fiscal

#### Centro de coste

Un centro de costos es como una cuenta, pero la única diferencia es que su estructura representa su negocio más de cerca que las cuentas.
Por ejemplo, en su plan de cuentas, puede separar sus gastos por su tipo (es decir, viajes, marketing, etc.). En su Gráfico de centros de coste, puede separarlos por línea de producto o grupo empresarial (por ejemplo, ventas en línea, ventas minoristas, etc.).

> Contabilidad > Centros de costos

#### Entrada de diario

Un documento que contiene entradas del Libro mayor (GL) y la suma del Debe y del Haber de esas entradas son los mismas. En ERPNext puede actualizar Pagos,
Devoluciones, etc., utilizando asientos de contables.

> Contabilidad > Asiento de contable

#### Factura de venta

Una factura enviada al Cliente por la entrega de Artículos (bienes o servicios).

> Contabilidad > Factura de venta

#### Factura de compra

Una factura enviada por un Proveedor por la entrega de Artículos (bienes o servicios).

> Contabilidad > Factura de compra

#### Divisa

ERPNext le permite reservar transacciones en varias monedas. Sin embargo solo habrá una moneda para su libro de cuentas. Al publicar sus facturas con
pagos en diferentes monedas, el monto se convierte a la moneda predeterminad según la tasa de conversión especificada.

> Configuración > Moneda

* * *

### Venta

#### Grupo de clientes

Una clasificación de Clientes, generalmente basada en el segmento de mercado.

> Venta> Configuración> Grupo de clientes

#### Cliente Potencial

Una persona que podría ser una futura fuente de negocios. Un cliente potencial puede generar
Oportunidades. (de: "puede conducir a una venta").

> CRM > Cliente potencial

#### Oportunidad

Una venta potencial. (de: "oportunidad para un negocio").

> CRM > Oportunidad

#### Cotización

Solicitud del cliente para fijar el precio de un artículo o servicio.

> Venta > Cotización

#### Órdenes de venta

Una nota que confirma los términos de entrega y el precio de un Artículo (producto o servicio) por parte del Cliente. Las entregas, las órdenes de trabajo y las facturas se realizan sobre la base de las órdenes de venta.

> Venta> Pedido de venta

#### Territorio

Una clasificación de área geográfica para la gestión de ventas. Puede establecer objetivos para Territorios y cada venta está vinculada a un Territorio.

> Ventas > Configuración > Territorio

#### Socio de Ventas

Un distribuidor/comerciante/afiliado/comisionista externo que vende los productos de la empresa generalmente por una comisión.

> Ventas > Configuración > Socio de ventas

#### Vendedor

Alguien que le presenta al Cliente y cierra tratos. Puede establecer objetivos para vendedores y etiquetarlos en transacciones.

> Ventas > Configuración > Vendedor

* * *

### Compras

#### Orden de compra

Un contrato otorgado a un Proveedor para entregar los Artículos especificados en el
costo, cantidad, fechas y otros términos especificados.

> Compras > Orden de compra

#### Solicitud de Materiales

Una solicitud realizada por un Usuario del sistema o generada automáticamente por ERPNext basada en el nivel de reordenamiento o cantidad proyectada en el Plan de Producción para la compra de un conjunto de artículos.

> Compra > Solicitud de materiales

* * *

### Inventario (Existencias)

#### Almacén

Un almacén lógico contra el cual se realizan las entradas de inventario.

> Almacén

#### Entrada de Inventario

Transferencia de material desde un almacén, a un almacén o de un almacén a otro.

> Almacén > Entrada de Inventario

#### Nota de entrega

Una lista de artículos con cantidades para el envío. Una nota de entrega reducirá el inventario de artículos en el almacén desde donde se envía. Una nota de entrega se hace generalmente en una orden de venta.

> Almacén > Nota de entrega

#### Recibo de Compra

Una nota que indique que se recibió un conjunto particular de artículos del proveedor, muy probablemente en una orden de compra.

> Almacén > Recibo de Compra

#### Número de serie

Un número único dado a una unidad particular de un Artículo.

> Almacén > Número de serie

#### Lote

Un número dado a un grupo de unidades de un artículo en particular que pueden ser compradas o fabricadas en un grupo.

> Almacén > Lote

#### Registro del Libro Mayor de Existencias

Una mesa unificada para todos los movimientos de materiales de un almacén a otro. Esta es la tabla que se actualiza cuando se realiza una Entrada de Inventario, Nota de Entrega, Recibo de Compra y Factura de Ventas (POS).

#### Reconciliación de Existencias

Actualice el inventario de varios artículos desde un archivo de hoja de cálculo (CSV).

> Almacén > Reconciliación de inventarios

#### Inspección de Calidad

Una nota preparada para registrar ciertos parámetros de un artículo en el momento de la Recepción
del Proveedor, o Entrega al Cliente.

> Almacén > Inspección de calidad

#### Grupo de Artículos

Una clasificación de artículo.

> Almacén > Configuración > Grupo de artículos

* * *

### Gestión de Recursos Humanos

#### Empleado

Registro de una persona que ha estado en el presente o en el pasado, en la plantilla de la empresa.

> Recursos Humanos > Empleado

#### Solicitud de Autorización

Un registro de una solicitud de permiso aprobada o rechazada.

> Recursos humanos > Solicitud de autorización

#### Tipo de Autorización

Un tipo de autorización (por ejemplo, autorización por enfermedad, autorización por maternidad, etc.).

> Recursos humanos > Asistencia > Tipo de autorización

#### Entrada de nómina

Una herramienta que ayuda en la creación de múltiples Nóminas para Empleados.

> Recursos humanos > Entrada de nómina

#### Nómina

Un registro del salario mensual dado a un empleado.

> Recursos Humanos > Nómina

#### Estructura Salarial

Una plantilla que identifica todos los componentes del salario (ganancias) de un empleado, impuestos y otras deducciones de seguridad social.

> Recursos humanos > Salario y nómina > Estructura salarial

#### Evaluación

Un registro del desempeño de un empleado durante un período específico basado en ciertos parámetros.

> Recursos Humanos > Valoración

#### Plantilla de Evaluación

Una plantilla que registra los diferentes parámetros del desempeño de un empleado y su ponderación para un rol en particular.

> Recursos humanos > Configuración de empleado > Plantilla de evaluación

#### Asistencia

Un registro que indica la presencia o ausencia de un empleado en un día en particular.

> Recursos Humanos > Asistencia

* * *

### Fabricación

#### Lista de Materiales (LdM)

Una lista de operaciones y artículos con sus cantidades, que se requieren para producir otro artículo. Se utiliza una lista de materiales (LdM) para planificar las compras y hacer el cálculo del coste del producto.

> Fabricación > LdM

#### Estación de Trabajo

Un lugar donde tiene lugar una operación de lista de materiales. Es útil calcular el costo directo del producto.

> Fabricación > Estación de trabajo

#### Orden de trabajo

Un documento que indica la producción (fabricación) de un artículo en particular con cantidades especificadas.

> Fabricación > Orden de trabajo

#### Herramienta de planificación de producción

Una herramienta para la creación automática de órdenes de trabajo y solicitudes de compra basadas
en órdenes de venta abiertas en un período determinado.

> Fabricación> Herramienta de planificación de producción

* * *

### Sitio Web

#### Publicación de Blog

Un artículo breve que aparece en la sección "Blog" del sitio web generado desde el módulo del sitio web ERPNext. Blog es una forma corta de "Web Log".

> Sitio web > Publicación de blog

#### Página Web

Una página web con una URL (dirección web) única en el sitio web generado a partir de ERPNext.

> Sitio Web > Página Web

* * *

### Configuración/Personalización

#### Campo Personalizado

Un campo definido por el usuario en un formulario/tabla.

> Configuración > Personalizar ERPNext > Campo personalizado

#### Valores Predeterminados Globales

Esta es la sección donde se establecen los valores predeterminados para varios parámetros del sistema.

> Configuración > Datos > Valores predeterminados globales

#### Encabezado de Impresión

Un título que se puede establecer en una transacción solo para imprimir. Por ejemplo, desea imprimir una cita con un título "Propuesta" o "Factura Pro forma".

> Configuración > Marca e Impresión > Imprimir Encabezados

#### Términos y Condiciones

Texto de sus términos de contrato. En las transacciones de Compraventa, puede haber ciertos Términos y Condiciones basados ​​en los cuales el Proveedor proporciona bienes o servicios al Cliente. Puede aplicar los Términos y condiciones a las transacciones y ellos

Texto de sus términos de contrato. En las transacciones de Compra/Venta, puede haber ciertos Términos y Condiciones basados en los cuales el Proveedor proporciona bienes o servicios al Cliente. Puede aplicar los Términos y Condiciones a las transacciones y aparecerán al imprimir el documento. Para conocer los Términos y Condiciones, [haga clic aquí](/docs/user/manual/es/setting-up/print/terms-and-conditions)

> Venta > Configuración> Términos y Condiciones

#### Unidad de Medida (UdM)

Cómo se mide la cantidad de un artículo. Por ejemplo, Kg, No., Par, Paquete, etc.

> Almacén > Configuración > UdM

{next}
