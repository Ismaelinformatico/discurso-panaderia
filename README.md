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

Explicación de la estructura:
Panadería: El sistema que gestiona los productos de panadería, empleados, ventas y pedidos.
Cliente: Contiene los datos habituales del cliente, incluyendo su nombre, contacto y preferencias.
Producto: Describe los productos de panadería disponibles (panes, bollos, pasteles, etc.), con información sobre precios, cantidades y fecha de caducidad.
Empleado: Información sobre los empleados de la panadería (pueden ser panaderos, cajeros, etc.).
Venta: Relaciona la venta de un producto a un cliente, gestionada por un empleado, con detalles como el importe y la fecha.
Pedido: Los clientes pueden hacer pedidos de productos a futuro o para recoger en un horario específico.
Reabastecimiento: Los empleados gestionan el reabastecimiento de productos en la panadería cuando los niveles de stock son bajos.
