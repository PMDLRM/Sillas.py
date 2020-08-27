# Sillas.py
En una tienda de sillas para oficina se venden de 3 tipos: básica, estándar y de lujo.
Además existen los clientes normales y los clientes frecuentes.

El precio de las sillas es:

Básica $700.00 c/u
Estándar $900.00 c/u
De Lujo $1,500.00 c/u
El dueño de la tienda ha decidido dar un descuento del 20% a los clientes frecuentes.

Además ha decidido aplicar la siguiente política de descuentos por mayoreo a los clientes normales:

si su compra es >= $10,000 y < $20,000 un 10% de descuento
si su compra es >= $20,000 un 15% de descuento
Escribe un programa que pregunte el tipo de silla (que es una letra mayúscula que puede ser B, E, L), el tipo de cliente (que es una letra mayúscula que puede ser F o N) y la cantidad a comprar (que es un número entero). Supón que solo se va a comprar de un tipo de silla.

El programa debe calcular y mostrar los siguientes datos (los datos son flotantes y debes mostrar uno en cada renglón):

el subtotal antes de aplicar descuento,
la cantidad de dinero que se otorga por descuento y
el total a pagar por el cliente.
Usa funciones para resolver tu programa.
1) Una función costo_silla que recibe el tipo de silla y regresa su costo
2) Una función que recibe el tipo de cliente y regresa el valor del descuento a dar.
3) Una función main que pide los datos (mostrando un menú), llama a las funciones necesarias y muestra el resultado.

Entrada
Una letra mayúscula que representa el tipo de silla 
Una letra mayúscula que representa el tipo de cliente
Un número entero que indica la cantidad de sillas a comprar.

Salida
El subtotal antes de descuento
El descuento
El total a pagar por el cliente

Ejemplo  1 de ejecucíón:
Tienda de Sillas
B)Básica
E)Estandar
L)Lujo
Opción:E
Tipo de cliente (F/N): F
Número de sillas: 5
Subtotal: 4500
Descuento:900.0
Total: 3600.0

Ejemplo 2:

Tienda de Sillas
B)Básica
E)Estandar
L)Lujo
Opción: L
Tipo de cliente (F/N): N
Número de sillas: 10
Subtotal: 15000
Descuento:1500.0
Total: 13500.0
