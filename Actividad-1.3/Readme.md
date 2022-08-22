Actividad 1.3

Una fábrica de muebles desea realizar un sistema y te han solicitado diseñar la base de datos en SQL Server. 
El negocio, actualmente dispone de unas planillas de cálculo para almacenar la información.
En esta primera etapa se solicita diseñar las tablas para poder representar los pedidos de los productos que fabrican.
El dueño de la carpintería aclaró que los pedidos son de un producto en particular, en ocasiones pueden pedir más de una unidad del mismo producto en un mismo pedido. 
Pero no ocurre que existan diversos productos en un mismo pedido.
Esto significa que en un pedido se pueden solicitar seis sillas pero no ocurrirá que pidan un ropero y una mesa.
Los pedidos deben registrar el producto, la cantidad de unidades, el cliente que solicitó el producto, la fecha de solicitud y la fecha en que el producto se encuentra 
listo para la entrega, el costo del pedido y si se encuentra abonado o no. Los pedidos son identificados por el número de pedido que debe generarse automáticamente.
Los productos, deben registrar un nombre y un código identificatorio. Todos los productos tienen un precio de venta. Algunos, además, tienen un precio de venta mayorista
y una cantidad de venta mayorista. Esto último representa la cantidad de unidades mínimas necesarias para que se considere una venta mayorista y, en consecuencia, 
el costo unitario cuando la venta tiene éstas características. El precio de venta mayorista debe ser menor al precio de venta.
Otra propiedad que registran todos los productos es la cantidad de días aproximados que lleva su construcción.
Todos los productos tienen exactamente una categoría. Por ejemplo, "Mueble de jardín", "Mueble de baño", "Mueble de cocina", etc.

Se desea llevar un registro de los clientes. Se almacenan obligatoriamente el apellido y los nombres. Opcionalmente, los clientes pueden indicar la fecha de nacimiento,
la dirección de correo electrónico, el número de teléfono de línea y el número de celular. Algunos clientes se registran a través de la web. Ese es un dato que el dueño
del negocio quiere registrar.

Por último, se desea registrar la información de los colaboradores. La información que se tiene de los colaboradores es: un legajo numérico, apellidos y nombres, 
4fecha de nacimiento, edad, año de ingreso a la fábrica y antigüedad, el sueldo actual, su modalidad de trabajo ('F' - Fulltime o 'P'- Parttime). 
El año de ingreso debe ser mayor a 1990.
