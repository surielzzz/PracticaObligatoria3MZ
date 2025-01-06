# PrácticaObligatoria3MZ
## Programa de simulación de una librería - "FERNANSHOP"
### Índice:

- 0.0. Instalación.
- 0.1. Descarga.
- 0.2. Título.
- 0.3. Menú principal.
- 0.4. Funcionamiento.
- **1. Registro de un nuevo cliente y opciones.**
    - 1.1. Formulario de registro.
    - 1.2. Menú de opciones del cliente.
    - 1.3. Consultar catálogo.
    - 1.4. Realizar un pedido.
    - 1.5. Ver mis pedidos realizados.
    - 1.6. Ver mis datos personales.
    - 1.7. Modificar mis datos personales.
    - 1.8. Cerrar sesión.
- **2. Inicio de sesión y opciones.**
    - 2.1. Inicio de sesión del cliente.
    - 2.2. Inicio de sesión del trabajador.
          - - 2.2.1. Usuario trabajador creado por defecto.
          - - 2.2.2. Menú de opciones
                - - - 2.2.2.1. Consultar los pedidos asignados.
                - - - 2.2.2.2. Modificar el estado de un pedido.
                - - - 2.2.2.3. Consultar el catálogo de productos.
                - - - 2.2.2.4. Modificar un producto del catálogo.
                - - - 2.2.2.5. Ver mi perfil.
                - - - 2.2.2.6. Modificar mis datos personales.
                - - - 2.2.2.7. Cerrar sesión.
    - 2.3. Inicio de sesión del administrador.
          - - 2.3.1. Usuario administrador creado por defecto.
          - - 2.3.2. Menú de opciones
                - - - 2.3.2.1. Asignar un pedido a un trabajador.
                - - - 2.3.2.2. Modificar el estado de un pedido.
                - - - 2.3.2.3. Dar de alta a un trabajador.
                - - - 2.3.2.4. Ver todos los pedidos.
                - - - 2.3.2.5. Ver todos los clientes.
                - - - 2.3.2.6. Ver todos los trabajadores.
                - - - 2.3.2.7. Cerrar sesión.
- **3. Apagar el software.**

# 0.0. Instalación.
Para poder ejecutar el programa debemos instalar el [JDK 23.0.1](http://https://download.oracle.com/java/23/latest/jdk-23_windows-x64_bin.exe "JDK 23.0.1"), cuando le des clic, se te instalará (debemos de verificar que esté en **C:\Program Files\Java**).

Después iremos al buscador de Windows, buscaremos "Editar las variables de entorno del sistema".


![](https://media.discordapp.net/attachments/1285298181797576846/1306357505328156672/image.png?ex=6763db7c&is=676289fc&hm=f6bb1dd15f4b0a9d11427359714364e5a63b116de1cf1f377a371346e9db203d&=&format=webp&quality=lossless)


Pulsaremos donde dice "variables de entorno", dentro, nos digiramos a "variables del sistema", seleccionamos "Path" y le damos a editar.

![](https://media.discordapp.net/attachments/1285298181797576846/1306358824403337216/image.png?ex=6763dcb6&is=67628b36&hm=be1875380497ad338db0b6ae331e8d498ffe0470d24aab87be4e997545dd76d6&=&format=webp&quality=lossless)

Se abrirá la siguiente ventana, clicáremos en la variable de Java e introducimos la siguiente la ruta (**C:\Program Files\Java\jdk-18.0.2.1\bin**), le damos a enter para confirmar y aceptar.

Descargamos del enlace a GitHub el archivo .zip, creamos una carpeta en C con el nombre que queramos e introducimos el archivo .zip que hemos descargado, lo descomprimimos y abrimos la carpeta resultante, nos metemos en src y clicamos en el ejecutable y el programa comenzará a funcionar.


# 0.1. Descarga.
Para poder utilizar este programa, deberemos de darle al botón verde en GitHub que dice "code", en este seleccionaremos la opción en la parte inferior que dice "Download zip".

![](https://media.discordapp.net/attachments/1285298181797576846/1306608106134048859/image.png?ex=67637360&is=676221e0&hm=5733dc0653ed7f321aafc5a51a47c836455e1e279e40356793b857ea1076fb24&=&format=webp&quality=lossless)

Cuando pulsemos, se nos descargará una carpeta comprimida (extensión .zip), la descomprimiremos y dentro le daremos doble clic derecho al archivo de extensión .bat. Este será el ejecutable que nos servirá para usar el programa.

![](https://media.discordapp.net/attachments/1285298181797576846/1306611922766139516/image.png?ex=676376ee&is=6762256e&hm=fef959443d3187dab156923a09d565fc0c6fcc599f64b09477364e901ecc9eef&=&format=webp&quality=lossless)


# 0.2. Título.
![](https://media.discordapp.net/attachments/1285298181797576846/1306350494154752020/image.png?ex=6763d4f4&is=67628374&hm=1279f13f15fa92f06aaef7e40bf6a5187f1da05e29b12aa5ea5c6cd53c06cd7c&=&format=webp&quality=lossless)


# 0.3. Menú principal.
![](https://media.discordapp.net/attachments/1285298181797576846/1306351360144576533/image.png?ex=6763d5c3&is=67628443&hm=9b9d8664da5373cd22218e2651dd75baa818fb0eabb817f0ab340107266c3e3a&=&format=webp&quality=lossless)


# 0.4. Funcionamiento.

## 1. Venta de entradas para un evento.
Sección donde aparecerá toda la información de los eventos que hay disponibles.
![](https://media.discordapp.net/attachments/1285298181797576846/1306351469678825553/image.png?ex=6763d5dd&is=6762845d&hm=8f664558232bbf443c333608dbe8f7953727d955060a315144fd3992a25c78de&=&format=webp&quality=lossless)


### 1.1. Selección de tipo de entradas.
Cuando elijamos uno de los eventos deseados (A/B/C), nos saldrá otra pestaña donde seleccionaremos el tipo de entrada dependiendo del evento elegido.

![](https://media.discordapp.net/attachments/1285298181797576846/1306351596346671244/image.png?ex=6763d5fb&is=6762847b&hm=8cad96761ced13b37c03a319ff9316cc9b30cf4ce84b1faf2b503febf28b60a1&=&format=webp&quality=lossless)


### 1.2. Cantidad de entradas.
A continuación, pedirá la cantidad de entradas que desean comprar, y se mostrará en la pantalla:
![](https://media.discordapp.net/attachments/1285298181797576846/1306351737778602096/image.png?ex=6763d61d&is=6762849d&hm=f26da839ec13c8ea5c0701942e73cef75fbbcf0e268df7a999803a7e3712c559&=&format=webp&quality=lossless)


### 1.3. Recolección de datos.
Pediremos datos básicos para poder tener información personal.
![](https://media.discordapp.net/attachments/1285298181797576846/1306352078997684297/image.png?ex=6763d66e&is=676284ee&hm=4be9fac96d256334313bd9d4d516a21271f1bd8b7d5c917f82bf6e2c26e9cf61&=&format=webp&quality=lossless)


### 1.4. Mostrar las entradas.
Dependiendo el evento elegido, se mostraran las entradas con sus respectivas informaciones dentro, así también como un código único, que servirá para evitar falsificaciones.
![](https://media.discordapp.net/attachments/1285298181797576846/1306663780297478164/image.png?ex=6763a739&is=676255b9&hm=7546c5396892e818aa44d94571b9753d631715112ec5467831aba5f4f96f831c&=&format=webp&quality=lossless)


### 1.5. Mostrar la factura.
Después de enseñar todas las entradas, pasará a mostrar una pequeña factura con el monto total (aplicado o no el descuento).

![](https://media.discordapp.net/attachments/1285298181797576846/1306664137639858228/image.png?ex=6763a78f&is=6762560f&hm=fe4208093d907ee597da4c6b35893c0a6720eaa01177a5c397036a4e77119d17&=&format=webp&quality=lossless)

![](https://media.discordapp.net/attachments/1285298181797576846/1306352273886019666/image.png?ex=6763d69c&is=6762851c&hm=c89fa039e069e90b64efae62db842e0539c55106ebdc2faae19ea955f3d75288&=&format=webp&quality=lossless)


### 1.6. Pedir dinero y dar cambio.
Se te pedirá la cantidad con la que deseas pagar; esta deberá de estar en efectivo. Con el siguiente, te mostrará tu cambio.
![](https://media.discordapp.net/attachments/1285298181797576846/1306352599548825640/image.png?ex=6763d6ea&is=6762856a&hm=47312e4c39d52cb8cb9bee5063493e68cede9ee779f87d5dc70b0b3e9386f289&=&format=webp&quality=lossless)


## 2. Consultar el estado de un evento.
En algún momento vamos a querer enseñar los eventos existentes y sus respectivos estados, para esto tendremos las siguientes funcionalidades.


### 2.1. Elegir el evento a consultar.
Se te pedirá por pantalla que introduzca el evento que deseas consultar.
![](https://media.discordapp.net/attachments/1285298181797576846/1306352783737487370/image.png?ex=6763d716&is=67628596&hm=78ec78c6354bc5678864f3f6ec8f4c07dfbf8b3e69cc298f9d861b356fd9ab43&=&format=webp&quality=lossless)

![](https://media.discordapp.net/attachments/1285298181797576846/1306353355081121904/image.png?ex=6763d79e&is=6762861e&hm=10c957fd74bcdb6164880c3cfabe43ddc5c0556bfc83e224489a42f70fa5de90&=&format=webp&quality=lossless)


### 2.2. Pedir fecha.
Esto es para saber cuántos días quedan para el evento desde la fecha introducida.
![](https://media.discordapp.net/attachments/1285298181797576846/1306353428334776346/image.png?ex=6763d7b0&is=67628630&hm=e9eee434b1d8523bdffa30d35a924d7910a63dd5788d3b3e13e84ebd4d211d7b&=&format=webp&quality=lossless)


### 2.3. Enseñar los estados de los eventos.
Procede a mostrarse el estado del evento seleccionando.

![](https://media.discordapp.net/attachments/1285298181797576846/1306353515026841621/image.png?ex=6763d7c4&is=67628644&hm=ab81605bfa4d01f102375bb47daba3c2ca14d5291e1883f997a8453f3bb3e777&=&format=webp&quality=lossless)

![](https://media.discordapp.net/attachments/1285298181797576846/1306355417261015200/image.png?ex=6763d98a&is=6762880a&hm=9e02e60f003496f035c06d3b16b64cc3dd5450d1592bcf0acda48beb70677b63&=&format=webp&quality=lossless)

Si ya ha sido el evento se mostrará lo siguiente:

![](https://media.discordapp.net/attachments/1285298181797576846/1306357945994317905/image.png?ex=6763dbe5&is=67628a65&hm=246c6a73205ac54f18c5a47b6d746bf1f9b6d632f3a9a33c25ce011eca157b11&=&format=webp&quality=lossless)

## 3. Menú de administrador.

### 3.1. Registro.
Cuando seleccionamos en el menú principal la opción para ir al menú del administrador, nos pedirá que hagamos un registro para confirmar que tenemos permiso de entrar a la parte administrativa.

![](https://media.discordapp.net/attachments/1285298181797576846/1306355702578675772/image.png?ex=6763d9ce&is=6762884e&hm=8aea47d66712274c8e5826825b2415190387bb507a73d4816dc4966f1529393c&=&format=webp&quality=lossless)

Después de ingresar correctamente, se mostrará el menú del administrador.

![](https://media.discordapp.net/attachments/1285298181797576846/1306355827107434516/image.png?ex=6763d9ec&is=6762886c&hm=4e21571f40df7134c6e07ab79eb3cb07abb2a0d501c55bdce04b854d39fd9ecc&=&format=webp&quality=lossless)


#### 3.1.1. Consultar los ingresos totales por evento.
Básicamente, esta sección está hecha para consultar los ingresos totales que tiene cada evento.

![](https://media.discordapp.net/attachments/1285298181797576846/1306356169732001843/image.png?ex=6763da3d&is=676288bd&hm=85104d4718c304a5dd6c2cca11680142308abffcb1cee9b57df4baa3fde1ecb5&=&format=webp&quality=lossless)


#### 3.1.2. Consultar las monedas restantes para el cambio.

##### 3.1.2.1. Mostrar los billetes y monedas restantes.
Aquí verificaremos que estemos devolviendo el dinero para el cambio de manera correcta, en la menor cantidad posible. Para esto tendremos unas existencias fijas en cada billete y moneda.

![](https://media.discordapp.net/attachments/1285298181797576846/1306356275289788467/image.png?ex=6763da56&is=676288d6&hm=55576d35a41c0ea751c5478651b496a84df792aa2af45a50057fd999778075d7&=&format=webp&quality=lossless)


### 3.1.3. Apagar software.

![](https://media.discordapp.net/attachments/1285298181797576846/1306356531629129849/image.png?ex=6763da94&is=67628914&hm=8bde6169da433604f9fd8a3918d73dc57ffdbf3b9af23e25a3ffce9bd49c526f&=&format=webp&quality=lossless)

![](https://media.discordapp.net/attachments/1285298181797576846/1306356601900236933/image.png?ex=6763daa4&is=67628924&hm=611c205de12bfb7794543f8105759cc66ab5cfb37c2803b975895c182a2fe3d0&=&format=webp&quality=lossless)
