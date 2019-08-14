---
title: Aduanas UPS - parte 1
---

Este es un pequeño tutorial sobre cómo realizar la autogestión de aduanas con UPS. En este primer artículo se introduce qué opciones tienes para realizar los tramites con aduanas, así como qué tienes que hacer antes de que llegue tu paquete a España.
<!--more-->
UPS es una compañía americana de paquetería que como cualquier compañía privada, tiende a cobrar hasta por respirar.

En caso de que la tienda estadounidense en la que quieras comprar envíe por UPS sí o sí, no sólo te van a cobrar bastante más de lo que te cobrarían enviado por USPS (el equivalente al Correos español), sino que te cobrarán un recargo de aproximadamente 18€ más IVA porque realicen ellos los trámites aduaneros.

Así que en pos de mejorar un poco el mundo, voy a explicar aquí cómo realizar tú mismo los trámites y pagar exclusivamente IVA y aranceles.

Lo primero que debes saber es que **estos trámites los puedes realizar de forma absoluta y totalmente teleḿatica**. No vas a tener que presentarte en las aduanas españolas en Barajas – todo se puede hacer desde tu ordenador.

## Paso 0 - activar Cl@ve o DNI-e

Para poder realizar todas estas gestiones de forma telemática, y teniendo en cuenta que se pueden demorar algunos días, **es importante tener funcionando el acceso a las webs necesarias antes de hacer ningún pedido**.

Una de las opciones si tenéis lector de tarjetas smart card en vuestro ordenador es ir a [una oficina de expedición del DNI](https://www.dnielectronico.es/PortalDNIe/PRF1_Cons02.action?pag=REF_1030), sin pedir cita previa, y usar una de las máquinas para activaros el DNI-e (DNI electrónico).

El problema del DNI-e es que tienes que tener un lector de smart card, y además los certificados tienen que ser renovados cada dos años.

La otra opción es utilizar [Cl@ve](http://clave.gob.es/), que se trata de una aplicación para móviles que genera claves temporales ([One Time Passwords](https://en.wikipedia.org/wiki/One-time_password)), y que a diferencia del DNI electrónico, no caduca.

Para obtenerlo, podéis hacerlo usando el propio DNI-e (a partir del cual puedes dejar que caduquen los certificados, porque da igual), mediante correo postal o personalmente. Tienes más información [en la sección de registro de Cl@ve](http://clave.gob.es/clave_Home/registro.html).

Simplificado, estas son las opciones que tenéis:

![Diagrama de opciones.](/assets/aduanasups/diagrama_aeat.png)

## Paso 1 - avisar a UPS

El primer paso es avisar a UPS de que vamos a tramitarnos nosotros mismos el papeleo aduanero. Esto se conoce en el mundillo como autogestión.

Estoy es muy importante realizarlo lo más rápido posible en cuanto se sepamos el código de seguimiento, ya que UPS suele comenzar a realizar los trámites en cuanto llega a España.

Una vez el paquete haya sido asignado un número de seguimiento, debemos enviar **un email a la dirección [brokeragees@ups.com](mailto:brokeragees@ups.com)** (este correo es sólo para España), con un texto similar a este:

> **Título: Autogestión [seguimiento]**
> 
> Hola buenos días,
> 
> Soy [nombre y apellidos], con DNI [dni], y les informo que deseo realizar yo mismo la gestión de los trámites aduaneros de importación para el paquete con seguimiento [seguimiento].
> 
> Un saludo,
> [nombre]

Una vez lo hayan recibido, podremos ver en el seguimiento cómo aparecen estas dos líneas:

![Seguimiento de UPS mostrando que se ha requerido la gestión por un agente externo, en este caso, nosotros.](/assets/aduanasups/ups_aduanas.png)

## Paso 2 - esperar la llegada a España

A continuación tenemos que esperar a que entre en las aduanas españolas. Cuando ello ocurra, en la web de UPS aparecerá “Clearance in progress”.

![Se muestra "Clearance in progress" en el resumen del estado.](/assets/aduanasups/clearance.png)

## Paso 3 - solicitar a UPS los documentos asociados

Debemos de enviar otro email a [brokeragees@ups.com](mailto:brokeragees@ups.com), solicitando la información asociada al envío, como la dirección de origen, el peso o el precio declarado.

**En caso de que tengas una factura emitida por la tienda donde aparezcan los datos del remitente, este paso no es necesario.**

Aquí tienes una plantilla que puedes utilizar:
> Hola buenos días, 
> 
> Soy [nombre y apellidos], con DNI [dni]. Les envío este email para 
> solicitarles la documentación asociada al envío [código de seguimiento] para 
> realizar los trámites de autogestión. 
> 
> Un saludo&nbsp;

Cuando nos respondan, nos enviarán tres ficheros:

*   ReportBarcelona.pdf

*   Barcode Report Barcelona.pdf

*   InvoiceXXXXXXXX.pdf

**Nos interesa el tercero** (InvoiceXXXXXXXX.pdf), **que es donde está la factura&nbsp;**y contiene todos los datos necesarios para realizar el DUA de aduanas.

Tiene un aspecto similar a esto:

![Factura](/assets/aduanasups/invoice.png)
