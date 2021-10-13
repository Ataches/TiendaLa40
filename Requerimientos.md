# Tienda la 40
## Mi cosecha 

##### Tabla de contenido

- [Propósito](#Propósito)  
- [Alcance del software](#alcance-del-software)  
- [Funcionalidades del producto](#Funcionalidades-del-producto)  
- [Clases y características de usuarios](#Clases-y-características-de-usuarios)  
- [Entorno operativo](#Entorno-operativo)  
- [Requerimientos funcionales](#Requerimientos-funcionales)  
- [Reglas de negocio](#Reglas-de-negocio)  
- [Requerimientos no funcionales](#Requerimientos-no-funcionales)
- [Otros requerimientos](#Otros-requerimientos)
- [Glosario](#Glosario)


## Propósito 

Sistema de gestión de ventas La 40.

La 40 es un punto de abastecimiento local cuyo objeto social es la comercialización de productos en el sector en el cual se encuentra ubicado.  Sus administradores solicitan el diseño e implementación de un sistema de información que le permita administrar la operación de venta de sus productos. 

El objetivo consiste en construir un sistema de información que permita gestionar las ventas de los productos de la organización, que abarque desde las solicitudes de pedido hasta el despacho de los productos. Para ello, se busca desarrollar una herramienta que permita el registro de las ventas, la gestión de productos, la gestión de pagos y la gestión de envíos de la mercancía, los cuales son los componentes principales que se consideran en el primer avance del sistema. 


## Alcance del software

En el sistema de información se busca desarrollar las actividades relacionadas con la gestión de las ventas de la tienda de La 40, incluyendo la gestión de pedidos, gestión de pagos y gestión de envío de productos.

Por lo anteriormente mencionado, el sistema de información no realizará operaciones de reembolsos o devoluciones de pedidos, modificaciones puntuales a las ventas, buzón quejas o reclamos y/o sugerencias respecto a los pedidos o relacionados, entre otros.

Se espera que el producto software beneficie a la tienda en su organización como punto de abastecimiento local de productos de la canasta familiar, así como en la posibilidad de la reactivación económica a través de nuevos canales digitales que se acoplen a los contenidos emergentes de las tecnologías de la información y las comunicaciones a nivel local, regional o nacional.

## Funcionalidades del producto
Lista de las funcionalidades del software que se están especificando en el documento de requerimientos. Cada funcionalidad puede estar compuesta por uno o varios requerimientos funcionales de software.

Aquí solo se incluye una lista numerada de las principales funcionalidades, la información detallada de requerimientos funcionales se documenta en la sección 7 de este documento.

| Funcionalidad                                          | Requerimiento funcional                                |
|--------------------------------------------------------|--------------------------------------------------------|
| Gestionar ventas                                       | Registrar venta (Facturación corriente)                |
| Gestionar inventario                                   | Registrar ingreso y salida de mercancía                |
| Gestionar pedidos                                      | Solicitar pedidos (Generar un pedido desde el carrito) |
|                                                        | Solicitar pedidos (Generar un pedido desde el carrito) |
|                                                        | Validar selección de productos                         | 
| Gestionar pago o transacción                           | Validar medio de pago (Efectivo y Tarjeta de crédito)  |
|                                                        | Validar productos carrito (Aplicar impuesto)           |
| Gestionar envíos                                       | Registrar envío                                        |  
|                                                        | Seguir estado del envío                                |   
|                                                        | Actualizar estado del envío                            |
| Gestionar usuarios                                     | Validar tipo de usuario (Admin- Cliente)               | 
|                                                        | Registrar usuarios                                    |
|                                                        | Iniciar sesión de usuarios                             |

## Clases y características de usuarios

En esta sección se clasifican los usuarios que utilizaran el producto. La clasificación puede ser en función a la frecuencia de uso, grupo de funcionalidades utilizadas, privilegios de seguridad, nivel de experiencia y otros parámetros.

Se puede usar una lista para enumerar los usuarios tipo que utilizarán el software, describiendo las características de cada uno.

Para cada tipo de usuario, se pueden mencionar las funcionalidades de producto (Sección 4) que le sean relevantes. Igualmente se puede hacer mención de cuales usuarios utilizan una mayor parte del sistema y con más frecuencia, para distinguirlos de usuarios ocasionales o que acceden a pocas funcionalidades.


## Entorno operativo

En esta sección se describe el entorno operativo en el que se desenvolverá el sistema, software, módulo o grupo de funcionalidades, mencionando aspectos como la plataforma de hardware, versiones de sistema operativo y otros sistemas o componentes con los que debe coexistir.

## Requerimientos funcionales

Los requerimientos funcionales de un sistema, son aquellos que describen cualquier actividad que este deba realizar, en otras palabras, el comportamiento o función particular de un sistema o software cuando se cumplen ciertas condiciones.

En esta sección de la plantilla, ilustramos como organizar los requerimientos funcionales de software por funcionalidad de producto o sistema. Aquí se listan las funcionalidades y para cada una a su vez se listan los requerimientos funcionales.

Los requerimientos funcionales también se pueden documentar en una matriz de trazabilidad de requerimientos. Sigue el siguiente enlace y te mostramos una plantilla:

> Plantilla de matriz de trazabilidad de requerimientos

A continuación se muestra como documentar cada funcionalidad:
9.1.    (Nombre de la funcionalidad 1)
En el título de la funcionalidad, se recomienda utilizar nombres lo más descriptivo posible para cada funcionalidad. No limitarse a nombrarlas “Funcionalidad 1”. Un buen ejemplo podría ser “Autorización de pedido de compra”.

Descripción: Descripción corta de la funcionalidad.

Prioridad: Nivel bajo, medio o alto de prioridad. Esta debe ser establecida por el área funcional.

Acciones iniciadoras y comportamiento esperado: Secuencia de acciones de usuario y respuestas esperadas del sistema para esta funcionalidad.

Requerimientos funcionales: Lista detallada de los requerimientos funcionales asociados a esta funcionalidad.

Para cada requerimiento funcional se establece como debe mostrarse el software y cuales comportamientos debe desempeñar para que el usuario pueda realizar la función que necesita.

Es recomendable incluir como el software debe responder a condiciones de error y entradas de datos inválidas.

Cada requerimiento debe ser identificado unívocamente, para lo cual se recomienda usar un número de secuencia, que tenga algún significado y de formato común a toda la organización. Por ejemplo:

### REQ-1:

Para el funcionamiento de la aplicación se espera que el tiempo de respuesta sea imperceptible por el usuario final. Con este propósito, la aplicación considerada debe poseer un tiempo de respuesta menor o igual a 5 segundos.

- Criterios de aceptación:


La aplicación debe tener un tiempo de respuesta como máximo de 5 segundos en todas las tareas que tenga. De lo contrario, se considera que la aplicación no tiene el tiempo de respuesta esperado.

## Reglas de negocio

Listado de reglas y principios que aplican a todo el conjunto de requerimientos de software contenidos en el documento. Un ejemplo es cuales individuos o roles pueden desempeñar cierta función bajo ciertas circunstancias.
Para hacer cumplir las reglas de negocio, podría ser necesaria la definición de requerimientos funcionales que aplican a todo el sistema, no a una funcionalidad especifica.


## Otros requerimientos
Requerimientos no cubiertos en ninguna otra sección del documento de requerimientos de software, por ejemplo: Requerimientos de bases de datos, internacionalización, legales y objetivos de reúso de componentes de software.

## Glosario
Descripción de términos y siglas necesarias para el entendimiento del documento de requerimientos de software.
