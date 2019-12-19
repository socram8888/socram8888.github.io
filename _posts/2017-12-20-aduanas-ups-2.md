---
title: Aduanas UPS - parte 2
---

En éste artículo trataremos sobre cómo debemos rellenar los formularios de aduanas para Hacienda, y de dónde hay que sacar la información que nos solicitan.
<!--more-->
## Paso 4 - partida sumaria

Para poder realizar el documento 
simplificado de importación, nos hace falta saber el número de partida. 
Es decir, el código asignado por Aduanas a nuestro paquete.

Para ello, vamos a:

1. [Página web de la Agencia Tributaria AEAT](http://www.agenciatributaria.es)
2. Sede Electrónica de la AEAT (arriba a la derecha)
3. Aduanas (columna de la izquierda, en Todos los trámites)
4. Presentación de declaraciones sumarias y manifiestos de carga
5. Declaración sumaria de descarga (**[enlace directo](https://www.agenciatributaria.gob.es/AEAT.sede/procedimientoini/DA01.shtml)**).

Seleccionamos la opción de **Consulta de conocimientos aéreos**, e iniciamos sesión con Cl@ve o con el DNI electrónico.

![Lista de opciones, entre la que se incluye "Consulta de concimientos aéreos"](/assets/aduanasups/sumaria_descarga.png)

Aquí nos aparecerá un formulario digno de Frontpage 2000 en que podemos introducir el código de seguimiento de UPS, en la casilla de "Número de conocimiento".

![Resultado de la búsqueda, donde se muestra la declaración sumaria y partida](/assets/aduanasups/aduanas_encontrado.png)

**Debemos tomar nota de la Declaración sumaria, y del número de partida.**

## Paso 5 - declaración de importación

El siguiente paso consiste en realizar el trámite de importación propiamente dicho.

Para ello, ahora debemos ir a:

1. [Página web de la Agencia Tributaria AEAT](http://www.agenciatributaria.es/)
2. Sede Electrónica de la AEAT (arriba a la derecha)
3. Aduanas (columna de la izquierda, en Todos los trámites)
4. Presentación y despacho de declaraciones
5. Importación (**[enlace directo](https://www.agenciatributaria.gob.es/AEAT.sede/procedimientoini/DB01.shtml)**)

Aquí seleccionamos "**Formulario simplificado**" dentro de "Presentaciones":

![Lista mostrando la opción de "Formulario simplificado"](/assets/aduanasups/aduanas_form.png)

A continuación se nos mostrará un formulario donde poner datos básicos sobre nosotros, el remitente y el paquete.

![Vista del formulario sin rellenar](/assets/aduanasups/form1.png)

**En "País" hay que introducir el código ISO 3166 del país. Para Estados Unidos, éste es "US".** Si no lo sabéis, pulsad el enlace con el símbolo de interrogante, marcado en la imagen superior.

**En el recuadro de "Número de Referencia", pondremos el número de Declaración Sumaria y la Partida, todo junto, sin guiones ni espacios.**

Si por ejemplo vuestra Declaración Sumaria es 0801-7-044963, y la partida es 00357, en este campo pondremos 0801704496300357.

En "Código de la mercancía" aconsejo dejarlo al valor por defecto (9990000300). Éste código es un código TARIC (código internacional que se emplea para identificar el tipo de mercancía) que se utiliza en España para hacer referencias a declaraciones de particulares. Si lo cambiáis al que aparece en la factura, muy probablemente os avise de que no es posible hacerlo telemáticamente.

Otro dato importante es el **"Valor de factura/envío"**. Os aconsejo de momento **poner el coste original en la divisa original del pedido, incluyendo gastos de envío**. Para dólares, en "Divisa" ponéis "USD".

Los "Gastos de envío" pues los dejamos a cero. En el caso de España los gastos de envío también se utilizan para computar el IVA, con lo que no nos ahorraremos nada y perderemos tiempo calculando a mano cuántos euros son.

![Formulario rellenado](/assets/aduanasups/form1_rellenado.png)

**Pulsamos siguiente** y nos pedirá únicamente el número de la factura. **En caso de que no tengamos ninguno, podéis especificar aquí el ID de transacción de PayPal.**

**Volvemos a pulsar siguiente**, y se nos mostrará cuánto Montoro quiere llevarse:

![Captura donde se ve cuánto es el total de impuestos a pagar](/assets/aduanasups/importe.png)

En mi caso, el banco había aplicado una conversión de 468,75$ a 396,00€, mientras que aquí AEAT ha calculado que la conversión es 398,97€. Esto se debe a que la AEAT no pide el cambio que nos fue aplicado sino que aplica el que haya vigente el día que se rellena el formulario.

Depende de cómo haya fluctuado el cambio, puede ser favorable para nosotros (la AEAT calcula que los euros equivalentes es menor, con lo que pagamos menos) o desfavorable (el cambio es mayor, con lo que sale más caro).

**Como vemos que la conversión aplicada es desfavorable**, vamos a hacer el truco del almendruco: **volvemos atrás y cambiar de dólares a euros**, con el cambio que se nos aplicó a nosotros.

Abajo hay un botón que pone "Corregir declaración". Lo pulsamos y editamos: **donde antes pusimos el precio en dólares, lo ponemos en euros, y en "Divisa" ponemos "EUR".**

![Se ha cambiado de dólares a euros](/assets/aduanasups/form1_editado.png)

Si machacamos siguiente otra vez, veremos que ahora el importe total a pagar es casi un euro menor:

![Precio actualizado al cambiar de dólares a euros](/assets/aduanasups/importe_2.png)

Una vez está todo correcto, **subimos la documentación que tengamos demostrando el valor del artículo**. En mi caso, he subido la factura que me ha remitido UPS, y una captura del recibo del banco.

![Recibos subidos](/assets/aduanasups/recibos.png)

Pulsamos siguiente y podremos ver todos los campos de la declaración. **Revisadlo y comprobad que esté bien**.

Cuando lo hayáis hecho, **vais abajo del todo y pulsáis en "Firmar y Enviar". Os saldrá un popup, marcáis "Conforme" y lo enviáis.**

![Popup donde se debe pulsar en "Enviar y firmar"](/assets/aduanasups/firmar.png)

La página se recargará, y veremos que **ya hemos terminado de hacer la declaración**.

![Captura donde se ve el circuito verde](/assets/aduanasups/circuito.png)

Aquí tenemos un dato muy, muy importante: el circuito. En mi caso, siempre ha sido verde.

* Circuito verde: el paquete está libre de sospechas, en cuanto paguemos, saldrá de aduanas.
* Circuito amarillo: el paquete será revisado a mano por un agente de aduanas, y luego será puesto en circuito verde, o en el peor de los casos, el rojo.
* Circuito rojo: el paquete contiene algún tipo de producto ilegal, y no puede ser importado. Tendrás que ponerte en contacto con aduanas y hacer alegaciones.

**[Ir al paso 3](2017-12-20-aduanas-ups-3.md)**
