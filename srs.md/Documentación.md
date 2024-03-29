# Tabla de Contenido
### Nombre del programa:
# PAVP (Programa de administracion y venta de productos)

## Especificación de Requerimientos

***1.Introducción***
 La siguiente Especificación de Requerimientos de Software (SRS) del sistema a construir, surge con la finalidad de proveer toda la información de lo que quiere el cliente que contenga el software. Tales requerimientos son la base a la hora de comenzar el desarrollo del Software. En este caso el software a desarrollar es la optimización de productos puede ser abordada de diferentes maneras, dependiendo del tipo de sistema que se esté desarrollando y los objetivos de optimización que se quieran lograr.

***1.1.Propósito***
 El propósito de este documento es describir lo acordado con el cliente y desarrollar el paso a paso para crear el software que servirá para dar control y llevar un registro de los productos y optimizar sus ventas que ingresan y salen de su negocio. Sistematizar estos procesos dará mejor rendimiento de productos generando informes o reportes respectivos de las actividades de manera semanal, mensual y anual. Además tales informes 
pueden ser ajustados por el usuario.

***1.2 Alcance***
 El sistema será una aplicación web que permitirá llevar una optimizacion  en el registro de productos que ingresan del negocio, además de otras funciones que se encuentran detalladas en la sesión de requisitos. Este sistema dará apoyo a los siguientes procesos:
 
 ●	Control y organización de registros.
 
 ●	Administración de los espacios disponibles.
 
 ● Generar Reportes.
 
 ●	Optimizacion de su negocio.
 
 ● Capacitacion

***1.3 Definiciones, Acrónimos, y Abreviaturas***
●	Backup: Las copias de seguridad en un sistema informático tienen por objetivo el mantener la información de recuperación de la información ante posibles pérdidas. 

●	Interfaz: Medio que permite la comunicación entre el usuario y el sistema.

●	BD: Base de Datos  es un conjunto de datos pertenecientes a un mismo contexto y almacenados sistemáticamente  para su posterior uso.

●	Requerimientos funcionales (RF): describen las capacidades o funciones que el sistema será capaz de realizar.

●	Requerimientos no funcionales (RNF): restricciones o características que de delimitan el sistema, como por ejemplo, rendimiento, interfaces de usuario, fiabilidad, seguridad, portabilidad, normas, entre otros.

●	Requerimientos de interfaz de usuario (RIU): describen lo que el usuario vera finalmente. 

● Sistema Web: también conocido como “aplicación Web” son aquellos que están creados e instalados no sobre una plataforma o sistemas operativos  (Windows, Linux). Sino que se aloja en un servidor en Internet o sobre una intranet (red local).

***1.4 Referencias***
 Titulos, fechas, codigos.

***1.5 Apreciación Global***
En la primera parte de este documento, se ha presentado una corta introducción.
En el siguiente capítulo observara la perspectiva del proyecto, con sus funciones, especificaciones y características del proyecto mismo y de sus futuros usuarios. 
En el ítem 3 se presenta una especificación detallada de requerimientos que son necesarios para el análisis, diseño, desarrollo e implementación del sistema. 

***2. Descripción General***

***2.1 Perspectivas del Producto***
Con este sistema se espera una mejora en la forma de cómo se maneja parte del negocio,dicho sistema será la mejor arma ante inconvenientes de la administradora, además la mayoría de lugares públicos como privados manejan sistemas similares a este, es por eso que el negocio  contará con el suyo gracias al esfuerzo de quienes trabajaran en él. 


***2.2 Funciones del Producto***
Este software cumplirá con las siguientes funciones:

●	Gestion de  productos 

●   Gestion de solicitudes

●	Realizar consultas en una interfaz con filtros exclusiva para esto.

●	Generar reportes de las actividades (ingresos/salidas) que hubieron en el negocio.


***2.3 Características de Usuario***
La usurua  que interactuara con este sistema es la personas encargada de velar por la seguridad y bienestar del negocio,  quienes han trabajado con un “sistema” que es ineficiente para su labor (optomizar sus materiales y ventas de ello  ), sus expectativas son altas con este sistema (OSGC).


***2.4 Restricciones***
Para este sistema las posibles restricciones son el tiempo que tomará el desarrollo de este, recursos donde se implantara el sistema, el nivel del lenguaje programación para los desarrolladores.

***2.5 Atención y Dependencias***
El sistema será un apoyo para los procesos de ingresos y salida de objetos y optimización del negocio. Con ciertos elementos y herramientas de ayuda para dicho fin. 

***3. Requerimientos Específicos***

***3.1 Requerimientos Funcionales***


|**Código**          | RF-001          | 
|--------------------|-----------------|
|**Nombre**	         | MODULO DE LOGIN |
|**Fecha**	         | 13/04/23        | 
|**Grado Necesidad** | ALTO            |
|**Entrada**         | correo o telefono, contraseña |
|**Fuente**          | formulario de ingreso|
|**Salida**          | mensaje de "Bienvenido(a)"|
|**Destino**         | menu principal|
|**Restricciones**   |unicamente pueden ingresar los usuarios registrados|
|**Descripción**   	 |Al sistema podran ingresar todos los usuarios registrados previamente con su rol(empleado, administrador o cliente.) |
|**Proceso**         | Digitar los datos correspondientes del formulario de ingreso (correo o telefono y la contraseña) por consiguiente entraran a la pagina principal.|
|**Efecto Colateral**|Error porque digito un correo, telefono o contraseña invalido, lo que les impide el ingreso. |

|**Código**          | RF-002          | 
|--------------------|-------------------|
|**Nombre**	         | GESTION DE USUARIO |
|**Fecha**	         | 10/05/23        | 
|**Grado Necesidad** | ALTO            |
|**Entrada**         | nombre, apellidos, edad, id , ciudad, telefono, direccion, correo.   |
|**Fuente**          | formulario de registro|
|**Salida**          | mensaje de "registro exitoso"|
|**Destino**         | menu principal|
|**Restricciones**   |unicamente seran registrados mayores de 18 años en adelante.|
|**Descripción**   	 | Esta gestion les permitira llevar los datos a la base de datos donde quedaran guardados, para ingresar cuando deseen al sistema utilizando solo el correo o telefono y la contraseña. |
|**Proceso**         | digitar datos pedidos para el registro|
|**Efecto Colateral**| Ninguno. |

|**Código**          | RF-003                 | 
|--------------------|------------------------|
|**Nombre**	         | GESTION DE PRODUCTOS  |
|**Fecha**	         | 13/04/23               | 
|**Grado Necesidad** | ALTO                   |
|**Descripción**   	 | El sistema debe permitir el registro de productos para llevar el orden de estos y saber cuando se agoten para volver a obtener los necesarios. | 
|**Entrada**         | coreo o telefono, contraseña                | 
|**Fuente**          | SISTEMA        |
|**Salida**          | mensaje *datos guardados*  | 
|**Destino**         | administrador  |
|**Restricciones**   | solo el personal que cuente con un usuario valido puede ingresar y ver la informacion planteada dependiendo su rol (Administrador)|
|**Proceso**         | RECOLECCION DEDATOS BASICOS DEL PRODUCTO ( registrar, que cantidad hay en el inventario,  que productos se agotaron, registro de venta cuanto se vendio(semanal, mensaul) y de cuanto fue la inversion) y datos basicos del proveedor de dicho producto( nombre, ciudad) | 
|**Efecto Colateral**| Error al ingresar      | 

|**Código**          | RF-004          | 
|--------------------|-------------------|
|**Nombre**	         | GESTION DE PEDIDOS |
|**Fecha**	         | 11/05/23        | 
|**Grado Necesidad** | ALTO          |
|**Entrada**         | correo o telefono, contraseña y confirmarcion del pedido |
|**Fuente**          | almacenado en el sistema |
|**Salida**          | mensaje * exito *|
|**Destino**         | menu principal|
|**Restricciones**   |disponibilidad del producto, cantidad minima 1|
|**Descripción**   	 |La gestión de pedidos lo que hace es tomar el pedido guardarlo en un carrito y esperar la confirmacion de que si lo compra o no,contribuye significativamente a la satisfacción del cliente y a la reputación general de la empresa.|
|**Proceso**         | ingresar al sistema por medio del boton de ayuda y esperar el pdf. |
|**Efecto Colateral**| ninguno |


   
|**Código**          | RF-005        | 
|--------------------|-----------------|
|**Nombre**	         | GESTION DE PROVEEDOR |
|**Fecha**	         | 13/04/23        | 
|**Grado Necesidad** | ALTO            |
|**Entrada**         |  correo o telefono, contraseña|
|**Fuente**          |solicitar productos a los proveedores |
|**Salida**          | mensaje de "guardado"|
|**Destino**         | menu principal|
|**Restricciones**   |ninguno|
|**Descripción**   	 | el administrador pedira una solicitud para comprar productos ya sean nuevos o los mismos de siempre y guardar informacion, aparte debe guardar el contacto del proovedor por si se quiere seguir comprando al proveedor sus productos |
|**Proceso**         | recibir sus productos, guadar informacion, para vender los productos.|
|**Efecto Colateral**|Error porque digito un correo, telefono o contraseña invalido, lo que les impide el ingreso. |

|**Código**          | RF-006   | 
|--------------------|------------------------|
|**Nombre**	         | gestion de solicitudes|
|**Fecha**	          | 13/04/23               | 
|**Grado Necesidad** | MEDIO                  |
|**Descripción**  	  | Los usuarios regstrados como clientes podran deja sus quejas o inquietudes referente a los productos que se le ofrecen en el negocio.| 
|**Entrada**         | Usuario cliente        | 
|**Fuente**          | SISTEMA          |
|**Salida**          | queja o inquietud      | 
|**Destino**         | notificacion a administrador    |
|**Restricciones**   | ninguna                |
|**Proceso**         | Se ingresa y se hace la queja o inquietud llega directamente una notificacion a la administradora y el usuario debera esperar entre un lapso de tiempo de 24h para una respuesta de solucion, si la solicitud no es respondida volver a hacer el proceso.|
|**Efecto Colateral**| Ninguno.|


|**Código**          | RF-007 | 
|--------------------|-------------------|
|**Nombre**	         | MODULO DE AYUDA |
|**Fecha**	         | 11/05/23        | 
|**Grado Necesidad** | MEDIO            |
|**Entrada**         | correo o telefono, contraseña   |
|**Fuente**          | boton de ayuda |
|**Salida**          |  pdf de ayuda|
|**Destino**         | dispositivo de usuario|
|**Restricciones**   | Ninguna|
|**Descripción**   	 | Este modulo les permitira conocer detalles del manejo adecuado del sistema, y responder posibles dudas. |
|**Proceso**         | ingresar al sistema por medio del boton de ayuda y esperar el pdf. |
|**Efecto Colateral**| Ninguno. |



***3.2.Requerimientos No funcionales***

|**Código**         | RFN-001   | 
|-------------------|-----------| 
|**Nombre**         | DESEMPEÑO | 
|**Fecha**          | 13/04/23  | 
|**Grado Necesidad**| ALTO      |
|**Descripción**    |El tiempo de respuesta y la duración de las opciones funcionales del software será lo más rápido posible. Por tanto el nivel de servicios requerido es tal que el sistema información con el tiempo no sufra una disminución en su desempeño (degradación) respecto al nivel previo al de la puesta en producción.|

|**Código**         | RFN-002   | 
|-------------------|-----------| 
|**Nombre**         | SEGURIDAD | 
|**Fecha**          | 13/04/23  | 
|**Grado Necesidad**| ALTO      |
|**Descripción**    |El tiempo de respuesta y la duración de las opciones funcionales del software será lo más rápido posible. Por tanto el nivel de servicios requerido es tal que el sistema información con el tiempo no sufra una disminución en su desempeño (degradación) respecto al nivel previo al de la puesta en producción.Este requerimiento es de suma importancia como todo los demás, sin embargo la seguridad prima en cualquier sistema es por esto que para aplicar esta se hará uso de una contraseña y usuario único con un rol, lo cual permite controlar el acceso a la información alojada.|

|**Código**         | RFN-003   | 
|-------------------|-----------| 
|**Nombre**         |USABILIDAD | 
|**Fecha**          | 13/04/23  | 
|**Grado Necesidad**| ALTO      |
|**Descripción**    |El software deberá ser lo suficientemente fácil de manejar por el usuario, es decir este último podrá hacer todas las operaciones del sistema sin ningún problema, sin embargo, cualquier duda que surja podrá ser consultada en la “Ayuda”.|

|**Código**         | RFN-004       | 
|-------------------|---------------| 
|**Nombre**         |DISPONIBILIDAD | 
|**Fecha**          | 13/04/23      | 
|**Grado Necesidad**| ALTO          |
|**Descripción**    |La disponibilidad del sistema del sistema le corresponde al negocio, que el servidor donde se alojara el sistema esté en funcionamiento en los horarios de atención.|

|**Código**         | RFN-005   | 
|-------------------|-----------| 
|**Nombre**         |FIABILIDAD | 
|**Fecha**          | 13/04/23  | 
|**Grado Necesidad**| ALTO      |
|**Descripción**    |La definimos como la probabilidad de que este producto funcione sin fallos durante un lapso estimado de un (1 año) sin recibir un mantenimiento correctivo.|

|**Código**         | RFN-006      | 
|-------------------|--------------| 
|**Nombre**         |MANTENIBILIDAD| 
|**Fecha**          | 13/04/23     | 
|**Grado Necesidad**| ALTO         |
|**Descripción**    |El sistema deberá tener la capacidad de recuperarse en lo posible frente a los posibles fallos que puedan presentarse. Asegurar que no se pierda los datos de la base de datos. En casos de falla del servidor la responsable es la compañía de alquiler de hosting. Por otra parte, se debe realizar mantenimiento preventivo ya que es de gran importancia para verificar el buen desarrollo de las actividades o procesos del sistema.|

|**Código**         | RFN-007    | 
|-------------------|------------| 
|**Nombre**         |PORTABILIDAD| 
|**Fecha**          | 13/04/23   | 
|**Grado Necesidad**| ALTO       |
|**Descripción**    |En cuanto a este requerimiento, podemos asegurar que el sistema será totalmente portable en cuanto a sistemas operativos, ya que este sistema funcionará desde un navegador, bien sea Google Chrome o Mozilla Firefox deberá de funcionar adecuadamente. Sin embargo se recomienda el uso del navegador Google Chrome.|

3.3 Requerimientos de interfaz de usuario

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RIU-001|LOGIN|13-04-2023|ALTO|
|Descripción| Interfaz que permitirá a los usuarios (Administrador, UsuMat) del sistema ingresar a este, para hacer uso de las funcionalidades de este.|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RIU-002|MENU PRINCIPAL|13-04-2023|MEDIO|
|Descripción| Interfaz que permitirá elegir la funcionalidad del sistema a la cual se desea acceder.|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RIU-003|REGISTRO DE USUARIO|13-04-2023|ALTO|
|Descripción| Interfaz que permitirá al Administrador registrar en la base de datos del sistema a los UsuMat.|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RIU-004|REGISTRO DE MATERIAL| 13-04-2023|ALTO|
|Descripción| Interfaz que permitirá registrar en la base de datos del sistemas de productos que ingresen por primera vez .|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RIU-005|REGISTRO|13-04-2023|ALTO|
|Descripción| Interfaz que permitirá registrar los objetos que ingresen por primera vez al negocio de formación de manera sencilla.|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RIU-006|REGISTRO DE SOLICITUDES|13-04-2023|ALTO|
|Descripción|Interfaz que permite registrar solicitudes realizadas por el administrador.|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RIU-007|INGRESO/SALIDA|13-04-2023|ALTO|
|Descripción|Interfaz que permite registrar los ingresos-salidas realizadas por el administrador de los productos o materiales.|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RIU-008|REPORTES|13-04-2023|MEDIO|
|Descripción| Interfaz que permite generar al administrador los respectivos reportes de los productos.|               |
