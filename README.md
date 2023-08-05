# woocommerce-saeweb
API conexion Woocommerce Ordenes-Pedidos e Inventarios para Sae8 y Caja5
Es una API creada para la Integración de las Ordenes-Pedidos desde la tienda Woocommerce a aspel Sae8 (desde version 5) y Caja (probado en version5 y mayores); el aspel-sae o caja pueden estarn en forma Local o Cloud en MS-SQL y Firebird.
La API se ejecuta de forma AUTOMATICA para estar integrando los nuevos inventarios que pudieran cambiar de la venta Directa (mostrador) en Sae/Caja asi como los precios; de Igual forma cuando se genera una VENTA PROCESADA (EFECTIVA en estatus Woocommerce "PROCESADA/COMPLEDADA") ambas acciones  programar nuestras API para que se ejecuten y apliquen la actualizacion directa a Sae/Caja.

