## NELSON OSNAYO
### AVANCE DE PORTAFOLIO MÓDULO 6
***
Adapte las vistas necesarias para que el sistema presente al usuario la
información requerida.

Ejemplo que el carrito de compra le permita realizar la compra de los
productos añadidos, calcule los montos, reduzca el stock del producto.

## Requerimientos por evaluar:
1. Ocupar el módulo File System para la manipulación de archivos
alojados en el servidor. (3pts).
2. Capturar los errores para condicionar el código a través del manejo
de excepciones. (1pt).
3. El botón “Comprar ahora” del carrito de compras genera una petición
POST (sin payload) esperando que el servidor registre una nueva POST
/venta en el servidor que ejecute una función asíncrona que registre
la venta en un archivo JSON (ventas.json).
El objeto correspondiente a la venta que se almacenará debe tener
un id generado con el paquete UUID. (2pts).
4. Crear una API REST que contenga las siguientes rutas:
a. GET /productos: Devuelve todos los productos almacenados en
el archivo productos.json.
b. POST /productos: Registra un producto y lo almacena en un
archivo JSON (productos.json).
c. PUT /producto: Recibe los datos del producto de la consulta y
modifica los datos almacenados del producto en el
archivo(productos.json).
d. DELETE /producto: Recibe el id de un producto registrado y lo
elimina.
e. GET /ventas: Devuelve todos los ventas almacenados en el
servidor (ventas.json.
Se debe considerar recalcular y actualizar el inventario de los
productos luego de este proceso. (3pts).
5. Devolver los códigos de estado HTTP correspondiente a cada
situación. (1pt).

### EJECUCION DEL PROYECTO
npm run dev.

NOTA: Los registros del proyecto estan en los siguiente archivos:
- productos.json
- ventas,json


