# discurso-panaderia
v1 universo.discurso.comienzo
El universo es una panadería. De los clientes se conocen los datos habituales, también de los productos, de los empleados y de las ventas. Un producto puede ser pedido por un cliente.

universo.discurso.fin

#---------------------------------------------------

v2 universo.discurso.comienzo
cliente: se conocen los datos habituales,
producto: se conocen los datos habituales,
empleado: se conocen los datos habituales,
venta: se conocen los datos habituales, Un producto puede ser pedido por un cliente.

universo.discurso.fin

#---------------------------------------------------

v3 universo.discurso.comienzo
panadería (de productos de panadería)
cliente (nombre, apellido, dni, teléfono, dirección,...)
producto (nombre, descripción, precio, cantidad disponible, fecha de caducidad,...)
empleado (número de empleado, dni, nombre, apellido, teléfono,...)
venta (producto, cliente, empleado, importe, fecha,...)
pedido (de productos) (por cliente)

universo.discurso.fin

#---------------------------------------------------

v4 (con diseño) universo.discurso.comienzo
panadería (de productos de panadería)
cliente (nombre, apellido, dni, teléfono, dirección, preferencias,...)
producto (código de producto, nombre, descripción, precio, cantidad disponible, fecha de caducidad,...)
empleado (número de empleado, dni, nombre, apellido, teléfono, puesto,...)
venta (producto, cliente, empleado, importe, fecha de venta,...)
pedido (de productos) (por cliente)
reabastecimiento (de productos) (por empleado)

universo.discurso.fin
