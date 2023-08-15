
# El riconcito del sabor

Proyecto con base a sistemas de facturacion e inventario de supermercados o servicios de comida rapido mediante interfaces graficas en Java.



## Instalacion

Descargue Apache Netbeans IDE 17

1. Descargue el archivo denominado como "RiconcitoDelSabor.zip"
2. Descomprima el arhivo.zip
3. Inicie el sistema Netbeans y abra el proyecto.


    
## Uso

El sistema se base en diferentes secciones donde abarcan desde un inicio de sesion hasta el inventario y el sistema de facturacion.

### Sistema de incio de sesion

En el sistema de incio de sesion se encuentra una interfaz con 2 espacios donde debe de escribir el nombre del empleado y su codigo de ingreso. El codigo de ingreso varia segun sea el nivel jerarquico del usuario, una vez ingresado el codigo se debe de seleccionar el botono "Siguiente" y se verifica que las credenciales coincidas con las credenciales establecidas. Los codigos son los correspondientes:

Usuario regular:
* 1254
* 1268
* 1278

Usuario Administrador:
* 1458

### Sistema de Menu o Interfaz principal

En el sistema de interfaz encontramos un menu donde se en la parte superior derecha hay un pequeño texto donde se explica como utilizar el sistema de venta de productos. Abajo de este texto se encuentra botones clasificados en refrescos y comidas. Mas abajo se encuentra las casillas del tipo de servicio y el tipo de pago. A lado derecha se encuentra el subtotal donde aparecen los productos que el cliente desea y que desea comprar. Abajo se encuentra un espacio donde se puede eliminar los productos no deseados y un espacio para escribir el codigo de descuento para aplicarle al total.'

Codigo de descuento:
* 1354

En los botones inferiores se encuentra Cerrar Sesion y el boton de Modificar Inventario. El boton den Modificar inventario solamente se activa si se ingresa al sistema con el codigo de administrador.

Cuando se desea realizar una compra se debe se seleccionar el producto y pulsar el boton correspondiente luego elegir el tipo de servicio y posteriormente el tipo de pago y seleccionar el boton "Pagar", si es efectivo el sistema lanzara una pequeña ventana con el valor final y en el caso de ser tarjeta se envia al sistema de facturacion.

### Sistema de facturacion

El sistema de facturacion unicamente se activa si el usuario ingresa la opcion de pagar por medio de tarjeta. El Sistema de facturacion consiste en un sistema donde se le muestra al usuario unas ventanas solicitandole valores necesarios para aplicar la factura y posteriormente se abre una ventana donde se imprime estos valores con el precio total.


### Sistema de inventario

El sistema de inventario unicamente puede ser visible si el usuario ingreso con el codigo de administrador. Para ingresar al sistema de inventario se debe de seleccionar el boton de Modificar Inventario y luego se despliega la ventana.

El sistema de inventario consiste en una ventana con una pequeña ventana en el centro, en esa ventana se imprime los productos actuales que se encuentran guardados en la bodega y registrados en la base de datos o en archivo.txt . El sistema consta de 3 botones inferiores, el boton "Atras" permite volver al menu principal o interfaz, el boton "Imprimir listado" permite al usuario poder imprimir en una ventana por separado todos los productos con su respectiva cantidad y finalmente el boton "Modificar" permite modificar la cantidad actual de cada producto seleccionado.


### Archivo de Texto (datos.txt)

El archivo de texto que se encuentra en la carpeta del mismo proyecto consiste en un archivo.txt que funciona como si fuera una base de datos, ahi los datos preguardados de los productos se almacenan y todos lo cambios finales con respecto a la cantidad se almacenan en el archivo. El archivo posee en su interior una estructura especifica donde se encuentra el nombre, el precio unitario y la cantidad correspondiente a cada producto. 

El formato del archivo es el siguiente:

#### NombreProducto, PrecioUnitario ,cantidad


## Authors

- [FernandoDelgadoC](https://github.com/FernandoDelgadoC)

- Pablo Sanchez
- Tomas Mora
- Sebastian Arguedas

## Feedback

If you have any feedback, please reach out to us at fdelgado9800@gmail.com


## Screenshots

![Interfaz de Inicio de Sesión](https://github.com/FernandoDelgadoC/RiconsitoDelSabor/raw/main/screenshots/Login.png)

![Interfaz de MenuPrincipal](https://github.com/FernandoDelgadoC/RiconsitoDelSabor/raw/main/screenshots/MenuInterfaz.png)

![Interfaz de Inventario](https://github.com/FernandoDelgadoC/RiconsitoDelSabor/raw/main/screenshots/Inventario.png)

![Interfaz de facturacion](https://github.com/FernandoDelgadoC/RiconsitoDelSabor/raw/main/screenshots/Facturacion.png)

