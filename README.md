# Práctica Obligatoria T3:
## Programa de simulación de una librería - "FERNANSHOP"
### Índice:

- **0. Introducción.**
    - [0.0. Instalación](#00-instalación)
    - [0.1. Descarga](#01-descarga)
    - [0.2. Título](#02-título)
    - [0.3. Menú principal](#03-menú-principal)
- **1. Registro de un nuevo cliente y opciones.**
    - [1.1. Formulario de registro](#11-formulario-de-registro)
    - [1.2. Menú de opciones del cliente](#12-menú-de-opciones-del-cliente)
    - [1.3. Consultar catálogo](#13-consultar-catálogo)
    - [1.4. Realizar un pedido](#14-realizar-un-pedido)
    - [1.5. Ver mis pedidos realizados](#15-ver-mis-pedidos-realizados)
    - [1.6. Ver mis datos personales](#16-ver-mis-datos-personales)
    - [1.7. Modificar mis datos personales](#17-modificar-mis-datos-personales)
    - [1.8. Cerrar sesión](#18-cerrar-sesión)
- **2. Inicio de sesión y opciones.**  
    - [2.1. Inicio de sesión del cliente](#21-inicio-de-sesión-del-cliente)  
    - [2.2. Inicio de sesión del trabajador](#22-inicio-de-sesión-del-trabajador)
        - [2.2.1. Usuario trabajador creado por defecto](#221-usuario-trabajador-creado-por-defecto)
        - [2.2.2. Menú de opciones](#222-menú-de-opciones)
            - [2.2.2.1. Consultar los pedidos asignados](#2221-consultar-los-pedidos-asignados)
            - [2.2.2.2. Modificar el estado de un pedido](#2222-modificar-el-estado-de-un-pedido)
            - [2.2.2.3. Consultar el catálogo de productos](#2223-consultar-el-catálogo-de-productos)
            - [2.2.2.4. Modificar un producto del catálogo](#2224-modificar-un-producto-del-catálogo)
            - [2.2.2.5. Ver mi perfil](#2225-ver-mi-perfil)
            - [2.2.2.6. Modificar mis datos personales](#2226-modificar-mis-datos-personales)
            - [2.2.2.7. Cerrar sesión](#2227-cerrar-sesión)  
    - [2.3. Inicio de sesión del administrador](#23-inicio-de-sesión-del-administrador)
        - [2.3.1. Usuario administrador creado por defecto](#231-usuario-administrador-creado-por-defecto)
        - [2.3.2. Menú de opciones](#232-menú-de-opciones)
            - [2.3.2.1. Asignar un pedido a un trabajador](#2321-asignar-un-pedido-a-un-trabajador)
            - [2.3.2.2. Modificar el estado de un pedido](#2322-modificar-el-estado-de-un-pedido)
            - [2.3.2.3. Dar de alta a un trabajador](#2323-dar-de-alta-a-un-trabajador)
            - [2.3.2.4. Ver todos los pedidos](#2324-ver-todos-los-pedidos)
            - [2.3.2.5. Ver todos los clientes](#2325-ver-todos-los-clientes)
            - [2.3.2.6. Ver todos los trabajadores](#2326-ver-todos-los-trabajadores)
            - [2.3.2.7. Cerrar sesión](#2327-cerrar-sesión)
- **3. Apagar el software.**

---

# 0. Introducción.

## 0.0. Instalación.
Para poder ejecutar el programa debemos instalar el [JDK 23.0.1](http://https://download.oracle.com/java/23/latest/jdk-23_windows-x64_bin.exe "JDK 23.0.1"), cuando le des clic, se te instalará (debemos de verificar que esté en **C:\Program Files\Java**).

Después iremos al buscador de Windows, buscaremos "Editar las variables de entorno del sistema".


![](https://media.discordapp.net/attachments/1285298181797576846/1325954156166381680/1.webp?ex=677daa89&is=677c5909&hm=749aa8b8e8ace0e5f3b83f267d4046d1c9f7ed5ea406a3bad527001f3a234799&=&format=webp)


Pulsaremos donde dice "variables de entorno", dentro, nos digiramos a "variables del sistema", seleccionamos "Path" y le damos a editar.

![](https://media.discordapp.net/attachments/1285298181797576846/1325954409103884339/2.webp?ex=677daac6&is=677c5946&hm=c127a213d1f4bf5124bb56cab5d577ccb0b45872c13214a2fa44371bc5f0ac7d&=&format=webp)

Se abrirá la siguiente ventana, clicáremos en la variable de Java e introducimos la siguiente la ruta (**C:\Program Files\Java\jdk-18.0.2.1\bin**), le damos a enter para confirmar y aceptar.

Descargamos del enlace a GitHub el archivo .zip, creamos una carpeta en C con el nombre que queramos e introducimos el archivo .zip que hemos descargado, lo descomprimimos y abrimos la carpeta resultante, nos metemos en src y clicamos en el ejecutable y el programa comenzará a funcionar.


## 0.1. Descarga.
Para poder utilizar este programa, deberemos de darle al botón verde en GitHub que dice "code", en este seleccionaremos la opción en la parte inferior que dice "Download zip".

![](https://media.discordapp.net/attachments/1285298181797576846/1325954955269640233/image.png?ex=677dab48&is=677c59c8&hm=a6a591b00cf0a4e80b3c2db71763630e6c3096b1128665ba61f494057fa08801&=&format=webp&quality=lossless)

Cuando pulsemos, se nos descargará una carpeta comprimida (extensión .zip), la descomprimiremos y dentro le daremos doble clic derecho al archivo de extensión .bat. Este será el ejecutable que nos servirá para usar el programa.

![](https://media.discordapp.net/attachments/1285298181797576846/1325955377648504954/image.png?ex=677dabad&is=677c5a2d&hm=f7a8183b4bf9b7b27dfc3f3778ad63f3936a8883a5e10e053cf0f6dad5dbe853&=&format=webp&quality=lossless)


## 0.2. Título.
![](https://media.discordapp.net/attachments/1285298181797576846/1325955676542992415/image.png?ex=677dabf4&is=677c5a74&hm=4ccbcb1c71855b6401dbdf4cf30b5aea2e6c4554189cf4ea82ac0a9a9d0d989c&=&format=webp&quality=lossless)

Título del Software.

## 0.3. Menú principal.
![](https://media.discordapp.net/attachments/1285298181797576846/1325955845430968450/image.png?ex=677dac1c&is=677c5a9c&hm=8de5a10706cbb6c2d78e8107a168309c7e49222d705789cc2e081278e6e1df72&=&format=webp&quality=lossless)

En este caso, hemos decidido incluir una opción "Salir" al programa para poder finalizar la prueba del software.

---

# FUNCIONAMIENTO:

# 1. Registro de un nuevo cliente y opciones.

## 1.1. Formulario de registro.
![](https://media.discordapp.net/attachments/1285298181797576846/1325956332645384254/image.png?ex=677dac90&is=677c5b10&hm=e98745ce6d5924a77dca5f73cc20c30077c1b3a00aeab1b950aacbd1c19f6cc5&=&format=webp&quality=lossless)

En primer lugar, para registrar un nuevo cliente se le pedirá rellenar un formulario con los datos necesarios para continuar.

## 1.2. Menú de opciones del cliente.
![](https://media.discordapp.net/attachments/1285298181797576846/1325956643334262846/image.png?ex=677dacda&is=677c5b5a&hm=464ccd530e9599305fcdce6462b259752de22ab2706eaaab869e382aadce342a&=&format=webp&quality=lossless)

Este es el menú de opciones principal del cliente.

## 1.3. Consultar catálogo.
![](https://media.discordapp.net/attachments/1285298181797576846/1325956831167778816/image.png?ex=677dad07&is=677c5b87&hm=5713f4d723122194f75fa1fd250929c355afa93775a0ad43f714653ba853488b&=&format=webp&quality=lossless)

Para consultar el catálogo hemos decidido poner a la venta 8 productos con distintos precios pero mismo stock, como se puede ver en la imagen.

## 1.4. Realizar un pedido.
![](https://media.discordapp.net/attachments/1285298181797576846/1325957092292558849/image.png?ex=677dad45&is=677c5bc5&hm=4d0aeeedcd0edd71dc1e9c1a67ceab81ced3fa9c8d19c57c179dc93841791853&=&format=webp&quality=lossless&width=742&height=671)

Para realizar un pedido primero se le mostrará al cliente el catálogo y a continuación se le pedirá ingresar el número del producto que quiere comprar (001-008), tras ingresar el número, se le pedirá la cantidad de unidades que quiere comprar de ese producto. Una vez hecho esto, se preguntará otra vez al usuario por si quiere añadir algún producto más a ese pedido. En caso contrario bastará con poner un "no" y volveremos al menú principal del cliente.

## 1.5. Ver mis pedidos realizados.
![](https://media.discordapp.net/attachments/1285298181797576846/1325957280868470854/image.png?ex=677dad72&is=677c5bf2&hm=ebecab026f6c3ba00c9b5984b2347471738772d4b0ee72036e3192560aeae277&=&format=webp&quality=lossless)

En esta opción podemos ver todos los pedidos realizados por el cliente. Aquí se puede consultar el estado de los mismos y toda su información.

## 1.6. Ver mis datos personales.
![](https://media.discordapp.net/attachments/1285298181797576846/1325957498888523896/image.png?ex=677dada6&is=677c5c26&hm=577e5952947165c4d989378a754481e790f590d2d4bd7e92d8f9cd34ea71a5c8&=&format=webp&quality=lossless)

En esta opción podemos ver nuestra ficha de cliente con todos nuestros datos.

## 1.7. Modificar mis datos personales.
![](https://media.discordapp.net/attachments/1285298181797576846/1325958258468589709/image.png?ex=677dae5b&is=677c5cdb&hm=6968ebc3ecf89036afcbbe3766b3da306730da9fdeb876b40abea64d6c6654e1&=&format=webp&quality=lossless)

Para modificar alguno de nuestros datos se nos mostrará un menú en el cual podremos elegir el dato a modificar. Después se nos pedirá ingresar el valor al cual queremos cambiar el dato a modificar.

![](https://media.discordapp.net/attachments/1285298181797576846/1325958461313515560/image.png?ex=677dae8c&is=677c5d0c&hm=34450472c4b50d0c0b23936e10c145060c1ac18cb2b4716641ee5f8b5873776b&=&format=webp&quality=lossless)

Aquí podemos ver que el nombre del cliente se ha modificado con éxito de "Zm" a "Zamira".

## 1.8. Cerrar sesión.
![](https://media.discordapp.net/attachments/1285298181797576846/1325958651667546152/image.png?ex=677daeb9&is=677c5d39&hm=c9b754eeeb7bddd855fcb2cf6fcacd8ddb87a5cc51ce87d12febd2bb6caeb2ff&=&format=webp&quality=lossless)

---

# 2. Inicio de sesión y opciones.

## 2.1. Inicio de sesión del cliente.
![](https://media.discordapp.net/attachments/1285298181797576846/1325958912637272085/image.png?ex=677daef7&is=677c5d77&hm=86dc73d6156b0c512444384c9d0bfb4ea7e52fdaee6ef1734f056f4b7bc23090&=&format=webp&quality=lossless)

Inicio de sesión del cliente creado. Después se nos mostrará el menú principal del cliente con todas las opciones vistas anteriormente.

## 2.2. Inicio de sesión del trabajador.

#### 2.2.1. Usuario trabajador creado por defecto.
![](https://media.discordapp.net/attachments/1285298181797576846/1325959210844028989/image.png?ex=677daf3e&is=677c5dbe&hm=d54d12f9598b7519e30638bf7ee3e25e08867b2775038334cb33df91c0577a14&=&format=webp&quality=lossless)

En este caso, hemos decidido crear un trabajador por defecto para facilitar las pruebas del software y poder enseñar las funciones más fácilmente.
El trabajador por defecto será "zeus@gmail.com" con contraseña "5678".

#### 2.2.2. Menú de opciones.
![](https://media.discordapp.net/attachments/1285298181797576846/1325959210844028989/image.png?ex=677daf3e&is=677c5dbe&hm=d54d12f9598b7519e30638bf7ee3e25e08867b2775038334cb33df91c0577a14&=&format=webp&quality=lossless)

Menú principal del trabajador.

#### 2.2.2.1. Consultar los pedidos asignados.
![](https://media.discordapp.net/attachments/1285298181797576846/1326057118994006127/image1.png?ex=677e0a6e&is=677cb8ee&hm=6bce0dba396cdaf2e22b55a7638fa6142c078371cf6825121c228bdd24bab53c&=&format=webp&quality=lossless)

En esta opción se nos mostrará un resumen de todos los pedidos que tiene un trabajador asignados. Si no existe ninguno, se mostrará vacío con un texto de "NO HAY PEDIDOS ASIGNADOS".

#### 2.2.2.2. Modificar el estado de un pedido.
![](https://media.discordapp.net/attachments/1285298181797576846/1325961141637087272/image.png?ex=677db10b&is=677c5f8b&hm=c57a5778d7fee0b92735f928da8fbf336c220a6381ea04e849c7a43d503f6873&=&format=webp&quality=lossless)

Para modificar el estado de un pedido debemos ingresar el id del pedido que queremos modificar. A continuación se nos mostrará un menú con las opciones de estado de un pedido. 

Después de esto, se nos preguntará si queremos añadir un comentario y si queremos modificar la fecha estimada del pedido. (Ambas opciones podemos rechazarlas si queremos)

#### 2.2.2.3. Consultar el catálogo de productos.
![](https://media.discordapp.net/attachments/1285298181797576846/1325961369312432241/image.png?ex=677db141&is=677c5fc1&hm=2103df5d60d60d57a9636549456b5bbdd4492b5d4c019dcd58363012357843f5&=&format=webp&quality=lossless)

Aquí se muestra el catálogo de productos.

#### 2.2.2.4. Modificar un producto del catálogo.
![](https://media.discordapp.net/attachments/1285298181797576846/1325961890547109979/image.png?ex=677db1bd&is=677c603d&hm=f9e04f3d52e8be38e58c7c4a7e3c477786bf2c84319f6a0fd255b262fb0a1ac7&=&format=webp&quality=lossless)

Para modificar un producto del catálogo debemos ingresar el número del producto. Se nos mostrará a continuación un menú con las opciones de los datos que podemos modificar. Tras escoger una podremos cambiar el valor al deseado. Finalmente se vuelve a mostrar el catálogo actualizado con los datos cambiados.

![](https://media.discordapp.net/attachments/1285298181797576846/1325963498420965469/image.png?ex=677db33d&is=677c61bd&hm=04cd69b3c85d21f89583cecdf38f7abee543cfa54d9a41f2b5a37cb615a82f5a&=&format=webp&quality=lossless)

#### 2.2.2.5. Ver mi perfil.
![](https://media.discordapp.net/attachments/1285298181797576846/1325963605363134555/image.png?ex=677db356&is=677c61d6&hm=025285a33e7a7bc00fabed2fc54b3e6150d3af8f3a97295a62889eced0946e9b&=&format=webp&quality=lossless)

En esta opción podemos ver la ficha del trabajador con sus datos.

#### 2.2.2.6. Modificar mis datos personales.
![](https://media.discordapp.net/attachments/1285298181797576846/1325963947152769075/image.png?ex=677db3a8&is=677c6228&hm=a5bc96d7a0109c3650822548228141e97215e69f6f757b306cd9a2eceb03fa66&=&format=webp&quality=lossless)

Para modificar un dato del trabajador se nos muestra otro menú con las opciones disponibles para modificar. Elegiremos la que deseamos cambiar e introduciremos el valor del campo modificado.

![](https://media.discordapp.net/attachments/1285298181797576846/1325964149506838569/image.png?ex=677db3d8&is=677c6258&hm=ad88f3e9a02a65834f38349305a0eeb7eeddb4032eb053eb63e86381e59ed989&=&format=webp&quality=lossless)

#### 2.2.2.7. Cerrar sesión.
![](https://media.discordapp.net/attachments/1285298181797576846/1325964405170503750/image.png?ex=677db415&is=677c6295&hm=1d84eb43cb718af3e9d2f44656b2377943201a9fde8bd0494c9b2ec7f1b8f9d7&=&format=webp&quality=lossless)

## 2.3. Inicio de sesión del administrador.

#### 2.3.1. Usuario administrador creado por defecto.
![](https://media.discordapp.net/attachments/1285298181797576846/1325964631960715274/image.png?ex=677db44b&is=677c62cb&hm=c7c22981b821b357e06e2448732a584c29ff6e6fe09423bf0cd3afda35731b9a&=&format=webp&quality=lossless)

El administrador por defecto será "carlos@gmail.com" con contraseña "0000".

#### 2.3.2. Menú de opciones.
![](https://media.discordapp.net/attachments/1285298181797576846/1325964631960715274/image.png?ex=677db44b&is=677c62cb&hm=c7c22981b821b357e06e2448732a584c29ff6e6fe09423bf0cd3afda35731b9a&=&format=webp&quality=lossless)

Menú de opciones principal del administrador.

#### 2.3.2.1. Asignar un pedido a un trabajador.
![](https://media.discordapp.net/attachments/1285298181797576846/1325965032709947502/image.png?ex=677db4ab&is=677c632b&hm=deee515795d29a83359c709c80bc6ce2452bffaa3177bc89b18034157643b410&=&format=webp&quality=lossless)

A la hora de asignar los pedidos a los trabajadores se le muestran al administrador una lista con todos los pedidos realizados por los clientes, de estos, el administrador elegirá uno y lo asignará a un trabajador.

Este software contiene errores como la carencia de asignación automática de los pedidos al trabajador que menos pedidos tenga y la intervención del administrador en caso de empate. En este caso, todos los pedidos los deberá asignar el administrador y se le mostrarán siempre todos los pedidos para poderlos asignar a los trabjadores que desee. Estos errores se corregirán en la próxima entrega del proyecto.

#### 2.3.2.2. Modificar el estado de un pedido.
![](https://media.discordapp.net/attachments/1285298181797576846/1325965692633223282/image.png?ex=677db548&is=677c63c8&hm=4e487aa5a59503abd8f08b115f9c54a88f17f1d5ce83a274f01a175d83653b0b&=&format=webp&quality=lossless)

Para modificar el estado de un pedido desde el administrador se hará de la misma forma que con los trabajadores.
Se nos pedirá el id del pedido que queremos modificar y nos pedirá elegir el estado con un menú de opciones. 
Finalmente, se nos preguntará sobre la opción de añadir un comentario personalizado y cambiar la fecha estimada del pedido.

#### 2.3.2.3. Dar de alta a un trabajador.
![](https://media.discordapp.net/attachments/1285298181797576846/1325966007876980857/image.png?ex=677db593&is=677c6413&hm=88ad62428e36d113c80927e2508fbca23c24d22b3c12ca913b42c6c728c2d37d&=&format=webp&quality=lossless)

Para dar de alta a un nuevo trabjador tendremos que rellenar un nuevo formulario en el que se nos pedirán los datos básicos de este para continuar.

#### 2.3.2.4. Ver todos los pedidos.
![](https://media.discordapp.net/attachments/1285298181797576846/1325966315424448532/image.png?ex=677db5dc&is=677c645c&hm=17674de29c820baebbb5689d6a6aef030aa04325f8bed6a4f666d24b68f8f79e&=&format=webp&quality=lossless)

Aquí podremos ver todos los pedidos que hay creados en el software.

#### 2.3.2.5. Ver todos los clientes.
![](https://media.discordapp.net/attachments/1285298181797576846/1325966461214396549/image.png?ex=677db5ff&is=677c647f&hm=bac3f9001c390e2a113860dc6071d1d732e3a5cff77d8fea6ee496c41735947f&=&format=webp&quality=lossless)

En esta opción podemos ver todos los clientes registrados en nuestro software.

#### 2.3.2.6. Ver todos los trabajadores.
![](https://media.discordapp.net/attachments/1285298181797576846/1325966688616845334/image.png?ex=677db635&is=677c64b5&hm=38bfd493c6705d0d6798226a131f57de82d414e83e70585ff51e9131ffd8f891&=&format=webp&quality=lossless)

Por último, en esta opción podemos ver todos los trabajadores que hay dados de alta.

#### 2.3.2.7. Cerrar sesión.
![](https://media.discordapp.net/attachments/1285298181797576846/1325966842606653511/image.png?ex=677db65a&is=677c64da&hm=b1d24d0babece53ccfbd086f18092d7f49f99dde8caf4fa5d80b1fe650de8260&=&format=webp&quality=lossless)

---

# 3 Apagar el software.

![](https://media.discordapp.net/attachments/1285298181797576846/1325967061741998161/image.png?ex=677db68e&is=677c650e&hm=9a58c20810d9828d1b66f9956c08f6f53f4f96aa1343a237deff5603c1b6815a&=&format=webp&quality=lossless)

Hasta aquí nuestro software, gracias por leer y esperamos mejorar en futuras versiones. :)

