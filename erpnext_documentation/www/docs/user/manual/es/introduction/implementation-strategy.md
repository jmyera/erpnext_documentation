---
title: Estrategia de Implementación
add_breadcrumbs: 1
show_sidebar: 0

metatags:
 description: Antes de comenzar a administrar sus Operaciones en ERPNext, primero debe familiarizarse con el sistema y los términos utilizados. Para ello recomendamos que la implementación se realice en dos fases.
 keywords: frappe, nuevas características erpnext, erp, erp de código abierto, erp gratuito, seguridad, documentación
---

# Estrategia de Implementación

Antes de comenzar a administrar sus Operaciones en ERPNext, primero debe familiarizarse con el sistema y los términos utilizados. Para ello recomendamos que la implementación se realice en dos fases.

* La **Fase de Prueba**, donde ingresa registros ficticios que representan sus transacciones diarias y la **Fase en Vivo**, donde comenzamos a introducir información real.

### Fase de Prueba

* Leer el manual
* Cree una cuenta gratuita en [https://erpnext.com](https://erpnext.com) (La forma más fácil de experimentar).
* Crea su primer Cliente, Proveedor y Producto. Añada algunos más para familiarizarse con ellos.
* Cree Grupos de Clientes, Grupos de Productos, Almacenes, Grupos de Proveedores, para que pueda clasificar sus Productos.
* Complete un ciclo estándar de ventas - Iniciativa > Oportunidad > Cotización > Orden de Venta > Nota de Entrega > Factura de Venta > Pago (Entrada de diario)
* Complete un ciclo estándar de compras - Solicitud de Materiales > Orden de Compra > Recibo de Compra > Pagos (Entrada de diario).
* Completar un ciclo de fabricación (si corresponde) - LdM > Herramienta de Planificación de Producción > Orden de Producción > Problema de material
* Replica un escenario de la vida real en el sistema.
* Cree campos personalizados, formatos de impresión, etc según sea necesario.

### Fase en Vivo

Una vez que esté familiarizado con ERPNext, ¡Comience a ingresar sus datos reales!

* Limpie la cuenta de datos de prueba o mejor, comience una nueva instalación.
* Si solo desea borrar sus transacciones y no sus datos maestros como Productos, Clientes, Proveedores, LdM, etc., puede hacer clic en eliminar las transacciones de su empresa y comenzar de nuevo. Para hacerlo, abra el Registro de la empresa a través de Contabilidad > Maestros Contables > Compañía y elimine las transacciones de su empresa haciendo clic en el botón **Eliminar transacciones de la compañía** en la parte inferior del formulario de la empresa.
* También puede configurar una nueva cuenta en [https://erpnext.com](https://erpnext.com) y utilizar la prueba gratuita de 14 días. [Descubra más formas de implementar ERPNext](Getting-started-with-erpnext)
* Configure todos los módulos con Grupos de Clientes, Grupos de Productos, Almacenes, LdMs, etc.
* Importar Clientes, Proveedores, Artículos, Contactos y Direcciones usando la herramienta de importación de datos.
* Importar Inventario inicial utilizando la Herramienta de Reconciliación de Inventarios.
* Cree asientos contables iniciales a través de Asientos de Diario y cree Facturas de Venta y Facturas de Compra pendientes.
* Si necesita ayuda, [puede comprar soporte](https://erpnext.com/pricing) o [preguntar en el foro de usuarios](https://discuss.erpnext.com).

{next}
