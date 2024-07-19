# Proyecto de Caja Porta Mazos de TCGs
En este repositorio se encuentran los diseños e instrucciones para una caja portadora de mazos de juegos de cartas, en especifico para *Magic The Gathering* en formato *commander* con sus accesorios.

Esta caja fue diseñada para ser impresa en 3D por medio de maquinas FDM con PLA.

# MTG BOX

<img src="img/open1.png" alt="Principal" width="500">
<img src="img/close.png" alt="Secondary" width="500">

Estan disponibles los archivos de fabricacion y de objeto 3D en las carpetas `printing` y `model` respectivamente. Dentro de la carpeta `img` se encuentran las imagenes del proyecto.

### Objeto 3D:
* Fusion 360 f3d
* STEP

### Fabricacion:
* STL

# Diseño del objeto

<img src="img/parts.png" alt="parts" width="500">

El objeto fue diseñado en Fusion 360 para ser impreso en 3D por FDM con filamento PLA. Esta compuesto por 4 piezas que se numeran del 1 al 4.

Las dimensiones de los compartimientos consideran un maso de formato commander de 100 con protectores estandar de plastico Dragon Shield.

* 1 **Tray**: Compartimiento para almacenar las cartas
* 2 **Cover**: Cubierta del **tray**
* 3 **Dices_tray**: Caja de accesorios
* 4 **Dices_cover**: Tapa de la caja de accesorios

Los modelos 3D estan disponibles en extension STEP y Fusion 360 f3d

# Fabricacion

Para fabricar el objeto hay que procesar los archivos de mallas con Ultimaker Cura con las siguientes orientaciones para cada pieza para una impresion optima.

<img src="img/tray.png" alt="bandeja" width="500">

El **Tray** se puede cortar sin ninguna modificación ni correccin de posicion adicional, pero se deben utilizar soportes para la correcta impresion del mecanismo de cierre.

<img src="img/cover.png" alt="covertura" width="500">

**Cover** se debe rotar en 90 grados tal que la cara plana opuesta a la apertura quede tocando la cama de la impresora para no utilizar soportes exesivamente, se recomienda utilizar sujeciones del tipo "Brim"

<img src="img/dices.png" alt="cajadedados" width="500">

Se pueden imprimir ambas piezas de los **Dices** en la misma tanda, al importar las piezas solo se deben correr dentro de la cama para que estas no se superpongan.

### Parametros de impresion:
* Infill: 20%
* Altura de capa: 0.2 mm
* Boquilla 0.4mm (Para mejorar la velocidad de impresion se puede utilizar una boquilla de 0.8mm)
* Ancho de pared 1.6mm
* Temperatura de estrusor 210°
* Temperatura de cama 60°
* Velocidad segun capacidades de la impresora

Si la impresora es muy precisa se recomienda modificar la pretuberancia del mecanismo de sujecion en un amuento de 0.75mm. Para uso de una Ender 3 tradicional se puede mantener la pretuberancia original.

<img src="img/latch1.png" alt="cierre" width="500">

Pretuberancia de sujecion a modificar dependiendo del caso.

# Ensamblaje

Para ensamblar la caja solo es necesario introducir las cartas a guardar en los compartimientos con la cara de la carta orientada a la ranura de retiro y opcionalmente introducir los accesorios la caja de dados y colocarlo a la par con las cartas. Luego introducir el **Tray** con las cartas en el **Cover** con la manilla de retiro hacia afuera.

<img src="img/semiopen1.png" alt="ensamble1" width="500">

<img src="img/dices2.png" alt="ensamble2" width="500">

El sistema de cierre tiene una sola posicion, por lo que si al cerrar la caja no se mantiene cerrada por su propio peso rotar el cover en 180°.

Más imagenes disponibles en la carpeta `img` y el diagrama tecnico del modelo esta en el pdf `Diagrama.pdf`
