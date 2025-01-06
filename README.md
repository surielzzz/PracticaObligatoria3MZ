# Práctica Obligatoria T3:
## Programa de simulación de una librería - "FERNANSHOP"
### Índice:

- **0. Introducción.**
    - [0.0. Instalación](#00-instalación)
    - [0.1. Descarga](#01-descarga)
    - [0.2. Título](#02-título)
    - [0.3. Menú principal](#03-menú-principal)
    - [0.4. Funcionamiento](#04-funcionamiento)
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


![](https://media.discordapp.net/attachments/1285298181797576846/1306357505328156672/image.png?ex=6763db7c&is=676289fc&hm=f6bb1dd15f4b0a9d11427359714364e5a63b116de1cf1f377a371346e9db203d&=&format=webp&quality=lossless)


Pulsaremos donde dice "variables de entorno", dentro, nos digiramos a "variables del sistema", seleccionamos "Path" y le damos a editar.

![](https://media.discordapp.net/attachments/1285298181797576846/1306358824403337216/image.png?ex=6763dcb6&is=67628b36&hm=be1875380497ad338db0b6ae331e8d498ffe0470d24aab87be4e997545dd76d6&=&format=webp&quality=lossless)

Se abrirá la siguiente ventana, clicáremos en la variable de Java e introducimos la siguiente la ruta (**C:\Program Files\Java\jdk-18.0.2.1\bin**), le damos a enter para confirmar y aceptar.

Descargamos del enlace a GitHub el archivo .zip, creamos una carpeta en C con el nombre que queramos e introducimos el archivo .zip que hemos descargado, lo descomprimimos y abrimos la carpeta resultante, nos metemos en src y clicamos en el ejecutable y el programa comenzará a funcionar.


## 0.1. Descarga.
Para poder utilizar este programa, deberemos de darle al botón verde en GitHub que dice "code", en este seleccionaremos la opción en la parte inferior que dice "Download zip".

![](https://media.discordapp.net/attachments/1285298181797576846/1306608106134048859/image.png?ex=67637360&is=676221e0&hm=5733dc0653ed7f321aafc5a51a47c836455e1e279e40356793b857ea1076fb24&=&format=webp&quality=lossless)

Cuando pulsemos, se nos descargará una carpeta comprimida (extensión .zip), la descomprimiremos y dentro le daremos doble clic derecho al archivo de extensión .bat. Este será el ejecutable que nos servirá para usar el programa.

![](https://media.discordapp.net/attachments/1285298181797576846/1306611922766139516/image.png?ex=676376ee&is=6762256e&hm=fef959443d3187dab156923a09d565fc0c6fcc599f64b09477364e901ecc9eef&=&format=webp&quality=lossless)


## 0.2. Título.
![](https://media.discordapp.net/attachments/1285298181797576846/1306350494154752020/image.png?ex=6763d4f4&is=67628374&hm=1279f13f15fa92f06aaef7e40bf6a5187f1da05e29b12aa5ea5c6cd53c06cd7c&=&format=webp&quality=lossless)


## 0.3. Menú principal.
![](https://media.discordapp.net/attachments/1285298181797576846/1306351360144576533/image.png?ex=6763d5c3&is=67628443&hm=9b9d8664da5373cd22218e2651dd75baa818fb0eabb817f0ab340107266c3e3a&=&format=webp&quality=lossless)


## 0.4. Funcionamiento.

---

# 1. Registro de un nuevo cliente y opciones.

## 1.1. Formulario de registro.
## 1.2. Menú de opciones del cliente.
## 1.3. Consultar catálogo.
## 1.4. Realizar un pedido.
## 1.5. Ver mis pedidos realizados.
## 1.6. Ver mis datos personales.
## 1.7. Modificar mis datos personales.
## 1.8. Cerrar sesión.

---

# 2. Inicio de sesión y opciones.

## 2.1. Inicio de sesión del cliente.

## 2.2. Inicio de sesión del trabajador.

#### 2.2.1. Usuario trabajador creado por defecto.
#### 2.2.2. Menú de opciones.
#### 2.2.2.1. Consultar los pedidos asignados.
#### 2.2.2.2. Modificar el estado de un pedido.
#### 2.2.2.3. Consultar el catálogo de productos.
#### 2.2.2.4. Modificar un producto del catálogo.
#### 2.2.2.5. Ver mi perfil.
#### 2.2.2.6. Modificar mis datos personales.
#### 2.2.2.7. Cerrar sesión.

## 2.3. Inicio de sesión del administrador.

#### 2.3.1. Usuario administrador creado por defecto.
#### 2.3.2. Menú de opciones.
#### 2.3.2.1. Asignar un pedido a un trabajador.
#### 2.3.2.2. Modificar el estado de un pedido.
#### 2.3.2.3. Dar de alta a un trabajador.
#### 2.3.2.4. Ver todos los pedidos.
#### 2.3.2.5. Ver todos los clientes.
#### 2.3.2.6. Ver todos los trabajadores.
#### 2.3.2.7. Cerrar sesión.

---

# 3 Apagar el software.

![](https://media.discordapp.net/attachments/1285298181797576846/1306356531629129849/image.png?ex=6763da94&is=67628914&hm=8bde6169da433604f9fd8a3918d73dc57ffdbf3b9af23e25a3ffce9bd49c526f&=&format=webp&quality=lossless)

![](https://media.discordapp.net/attachments/1285298181797576846/1306356601900236933/image.png?ex=6763daa4&is=67628924&hm=611c205de12bfb7794543f8105759cc66ab5cfb37c2803b975895c182a2fe3d0&=&format=webp&quality=lossless)
