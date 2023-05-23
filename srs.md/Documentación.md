# Tabla de Contenido

**1.Introducción.4**
**1.1 Propósito 4**
**1.2 Alcance 4**
**1.3 Definiciones, Acrónimos, y Abreviaturas 4**
**1.4 Referencias 5**
**1.5 Apreciación Global 5**
**2.Descripción.5**
**2.1. del Producto.5**
**2.2.Funciones del Producto.6**
**2.3.Características de Usuario.6**
**2.4.Restricciones.6**
**2.5.Atención y Dependencias.6**
**3.Requerimientos Específicos.7**
**3.1.Requerimientos Funcionales.7**
**3.2.Requerimientos No Funcionales.11**
**3.3.Requerimientos de interfaz de usuario.14**
**4.Determinación de las tecnologías de hardware, software y servicios requerido.16**
**4.1.Software.16**
**4.2.Hosting.17**
**4.3.Computador.18**
**4.4.Escáner Lector Código de Barras Automático USB Soporte Base.19**
**4.5.Router (Router Inalámbrico/Repetidor WiFi N300Mbps, Tp-Link TL-WR840N).20**
**4.6.Presupuesto.21**

## Especificación de Requerimientos

***1.Introducción***
 La siguiente Especificación de Requerimientos de Software (SRS) del sistema a construir, surge con la finalidad de proveer toda la información de lo que quiere el cliente que contenga el software. Tales requerimientos son la base a la hora de comenzar el desarrollo del Software. En este caso el software a desarrollar es la optimización de materiales puede ser abordada de diferentes maneras, dependiendo del tipo de sistema que se esté desarrollando y los objetivos de optimización que se quieran lograr.

***1.1.Propósito***
 El propósito de este documento es describir lo acordado con el cliente y desarrollar el paso a paso para crear el software que servirá para dar control y llevar un registro de los objetos y optomizar sus ventas que ingresan y salen de su negocio. Sistematizar estos procesos dará mejor rendimiento al área de seguridad, y elaborancion de materiales generando informes o reportes respectivos de las actividades de manera semanal, mensual y anual. Además tales informes 
pueden ser ajustados por el usuario.

***1.2 Alcance***
 El sistema será una aplicación web que permitirá llevar una optimizacion  en el registro de los materiales y objetos que ingresan del negocio, además de otras funciones que se encuentran detalladas en la sesión de requisitos. Este sistema dará apoyo a los siguientes procesos:
 ●	Control y organización de registros.
 ●	Administración de los espacios disponibles.
 ●	Generar Reportes.
 ●	Optimizacion de su negocio.

***1.3 Definiciones, Acrónimos, y Abreviaturas***
●	Backup: Las copias de seguridad en un sistema informático tienen por objetivo el mantener la información de recuperación de la información ante posibles pérdidas. 

●	Interfaz: Medio que permite la comunicación entre el usuario y el sistema.

●	BD: Base de Datos  es un conjunto de datos pertenecientes a un mismo contexto y almacenados sistemáticamente  para su posterior uso.

●	Requerimientos funcionales (RF): describen las capacidades o funciones que el sistema será capaz de realizar.

●	Requerimientos no funcionales (RNF): restricciones o características que de delimitan el sistema, como por ejemplo, rendimiento, interfaces de usuario, fiabilidad, seguridad, portabilidad, normas, entre otros.

●	Requerimientos de interfaz de usuario (RIU): describen lo que el usuario vera finalmente. 

●	Sistema Web: también conocido como “aplicación Web” son aquellos que están creados e instalados no sobre una plataforma o sistemas operativos  (Windows, Linux). Sino que se aloja en un servidor en Internet o sobre una intranet (red local).

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

●	Registrar materiales con el precio..
●	Registrar  los materiales  que ingresarán al negocio.
●	Registrar los materiales (ajenos y pertenecientes del negocio)
●	Registrar Solicitudes que los propietarios/poseedores tengan.

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
|--------------------------------------|
|**Nombre**	         | MODULO DE LOGIN |
|**Fecha**	         | 13/04/23        | 
|**Grado Necesidad** | ALTO            |
|**Descripción**  	 |Al sistema pueden ingresar todos los usuarios que deseen y se registraran dependiendo su rol(Administrador, Empleado, Cliente) |
|**Proceso**         | En caso de administrador o empleado inice sesion (ya que se deberan encontrar previamente registrados). En caso de ser un cliente o un nuevo empleado debera registrarse.
|**Efecto Colateral**|Error porque se le olvido la contraseña o tiene nombre de usuario no valido, para respuesta de esto si se le olvido la contraseña enviar un correo para restablecerla, y si tiene un nombre de usuario invalido sugerirle uno valido. |

|**Código**          | RF-002                 | 
|---------------------------------------------|
|**Nombre**	         | Registro de materiales |
|**Fecha**	         | 13/04/23               | 
|**Grado Necesidad** | ALTO                   |
|**Descripción**  	 | El sistema debe permitir el registro de productos para llevar el orden de estos y saber cuando se agoten para volver a obtener los necsarios. | 
|**Entrada**         | Usuario                | 
|**Fuente**          | Propietario del negocio|
|**Salida**          | cantidad de productos  | 
|**Destino**         | usuario que ingreso    |
|**Restricciones**   | solo el personal que cuente con un usuario valido puede ingrrsar y ver la informacion planteada dependiendo su rol (Administrador, empleado, cliente)|
|**Descripción**     |	
|Proceso|
●	Recolección datos básicos materiales (de que producto es, cuánto vendió de ese producto,  cuánto gasto y vendió en la semana)
●	Registro satisfactorio del usuario.
Solo los usuarios que tengan el Rol de Administrador podrán hacer el registro de los materiales que tendrán el rol de UsuMat.|
|Efecto Colateral|	Los usuarios que no tenga el rol de UsuMat no tendrán acceso a todas las funcionalidades del sistema.|


|Código|Nombre|	Fecha|	Grado Necesidad|
|------|-------|-----|-----------------|
 RF-003	|REGISTRO DE MATERIALES |13-04-2023|  ALTO
|Descripción| El sistema debe permitir registrar materiales que ingresarán del negocio..
Entradas	Fuente	Salida	Destino	Restricciones
Características del material.	Formulario de registro para los materiales 	Material 
registrado	Base de datos	N/A|
|Proceso|	El usuario del sistema deberá registrar la siguiente información del producto.: 
De Tipo,  Marca.|
|Efecto Colateral|Se relaciona la información del registro de materiales para saber que compañía compro su producto.|


|Código	|Nombre|Fecha|Grado Necesidad|
|------|-------|-----|-----------------|
 RF-004|REGISTRO DE SOLICITUDES |13-04-2023 | ALTO
|Descripción	La administradora  podrán indicar las  peticiones y quejas referentes a cualquier inconveniente que se presente con alguno de los productos o materiales que tenga en su negocio.
Entradas	Fuente	Salida	Destino	Restricciones
Descripción de Anotación o queja. 	Formulario para el registro de las solicitudes	Registro de la solicitud.	 Base de datos	NINGUNA |
|Proceso	|
●	La administradora  debe acercare de forma personal a la persona en turno para que este pueda atenderlo de forma eficaz.
●	Exponer su Solicitud o reclamo y anotar.|
|Efecto Colateral|NINGUNO|

|Código|	Nombre|	Fecha|	Grado Necesidad|
|------|-------|-----|-----------------|
 RF-005	| REPORTES|	13-04-2023| 	MEDIO 
|Descripción|Generar informes respectivos de las actividades de ingreso-salida
Entradas	Fuente	Salida	Destino	Restricciones
 Registros diarios, semanales, mensuales etc.	 Registros de la base de dato	Reporte	 Base de datos.
Interfaz de reportes	Solo los administradores pueden acceder a este módulo. |
|Proceso|
Para generar el respectivo reporte debe seleccionar de una lista de chequeo la información que desea que aparezca en el reporte
●	Seleccionar opciones de lista de chequeo
●	Adaptar las fechas (Desde-Hasta) o simplemente la fecha actual.
●	Clic sobre el botón “generar”
●	Visualizar reporte.
El reporte se puede descargar o imprimir directamente.|
|Efecto Colateral|	NINGUNO|

|Código|	Nombre|	Fecha|	Grado Necesidad|
|------|-------|-----|-----------------|
 RF-006	|AYUDAv13-04-2023 ||ALTO 
|Descripción|	El sistema tendrá una botón que permitirá que re direccionara a un archivo PDF donde se hallará información de ayuda
Entradas	Fuente	Salida	Destino	Restricciones
Duda, pregunta del usuario	Archivo PDF	Nueva pestaña con el PDF	Nueva pestaña con el pdf|
|Proceso|	El usuario del sistema podrá realizar consultar dudas en un manual de ayuda para saber cómo ejecutar una funcionalidad del sistema.|
|Efecto Colateral|	NINGUNO|

***3.2.Requerimientos No funcionales***

|Código|Nombre|Fecha|Grado Necesidad|
|------|-------|-----|-----------------|
|RFN-001|DESEMPEÑO|13-04-2023|ALTO|
|Descripción |El tiempo de respuesta y la duración de las opciones funcionales del software será lo más rápido posible. Por tanto el nivel de servicios requerido es tal que el sistema información con el tiempo no sufra una disminución en su desempeño (degradación) respecto al nivel previo al de la puesta en producción.|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RFN-002|SEGURIDAD|13-04-2023|ALTO|
|Descripción| Este requerimiento es de suma importancia como todo los demás, sin embargo la seguridad prima en cualquier sistema es por esto que para aplicar esta se hará uso de una contraseña y usuario único con un rol, lo cual permite controlar el acceso a la información alojada.|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|---------------|
|RFN-003|USABILIDAD|13-04-2023|ALTO|
|Descripción |El software deberá ser lo suficientemente fácil de manejar por el usuario, es decir este último podrá hacer todas las operaciones del sistema sin ningún problema, sin embargo, cualquier duda que surja podrá ser consultada en la “Ayuda”.|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RFN-004|DISPONIBILIDAD|13-04-2023|ALTO|
|Descripción |La disponibilidad del sistema del sistema le corresponde al negocio, que el servidor donde se alojara el sistema esté en funcionamiento en los horarios de atención.|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RFN-006|FIABILIDAD|13-04-2023|ALTO|
|Descripción |La definimos como la probabilidad de que este producto funcione sin fallos durante un lapso estimado de un (1 año) sin recibir un mantenimiento correctivo.|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RFN-007|MANTENIBILIDAD|13-04-2023|ALTO|
|Descripción |El sistema deberá tener la capacidad de recuperarse en lo posible frente a los posibles fallos que puedan presentarse. Asegurar que no se pierda los datos de la base de datos. En casos de falla del servidor la responsable es la compañía de alquiler de hosting. Por otra parte, se debe realizar mantenimiento preventivo ya que es de gran importancia para verificar el buen desarrollo de las actividades o procesos del sistema.|

|Código|Nombre|Fecha|Grado Necesidad|
|------|------|-----|----------------|
|RFN-008|PORTABILIDAD|13-04-2023|ALTO|
|Descripción| En cuanto a este requerimiento, podemos asegurar que el sistema será totalmente portable en cuanto a sistemas operativos, ya que este sistema funcionará desde un navegador, bien sea Google Chrome o Mozilla Firefox deberá de funcionar adecuadamente. Sin embargo se recomienda el uso del navegador Google Chrome.|

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
