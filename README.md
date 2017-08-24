TK102-2 Tracker GPS
=========

## Descripción

<p align="center">
	<img src="https://github.com/ginppian/TK102/blob/master/imgs/img1.jpeg" width="320" height="426">
	<img src="https://github.com/ginppian/TK102/blob/master/imgs/img2.jpeg" width="320" height="426">
	<img src="https://github.com/ginppian/TK102/blob/master/imgs/img3.jpeg" width="320" height="426">
</p>

<p align="justify">
	El presente es una implementación de la plataforma <a href="https://www.traccar.org/">Traccar</a> con un dispositivo GPS. Previamente configuramos nuestra plataforma. <i>Para ver más </i><a href="https://github.com/ginppian/Traccar2.0">aquí</a>.
</p>

## Técnico

<table width="80%" cellspacing="0" cellpadding="1" border="0" class="style3">
  <tbody><tr><td><b>Modelo</b></td><td align="right">XEXUN TK102-2</td></tr>
  <tr><td><b>Red</b></td><td align="right">GSM/GPRS</td></tr>
  <tr><td><b>Banda</b></td><td align="right">850/900/1800/1900Mhz</td></tr>
  <tr><td><b>Chip GPS</b></td><td align="right">SIRF3</td></tr>
   <tr><td><b>Modulo GSM/GPRS</b></td><td align="right">Simcom SIM900</td></tr>
  <tr><td><b>GPS sensitivity</b></td><td align="right">-159dBm</td></tr>
  <tr><td><b>GPS accuracy</b></td><td align="right">5m</td></tr>
  <tr><td><b>Time to first fix</b></td><td align="right">cold 45s, warm 35s, hot 1s</td></tr>
  <tr><td><b>Battery</b></td><td align="right">Recargable 3.7V 1000mAh Li-ion</td></tr>
  <tr><td><b>Autonomia</b></td><td align="right">Standby 80 horas</td></tr>
  <tr><td><b>Operation temperature</b></td><td align="right">-20ºC a 55ºC</td></tr>
  <tr><td><b>Operation humidity</b></td><td align="right">5%--95%</td></tr>
  <tr><td><b>Dimensiones</b></td><td align="right">64x46x17mm</td></tr>
  <tr><td><b>Peso</b></td><td align="right">50gr</td></tr>
  <tr><td><b> </b></td><td align="right"> </td></tr>
  </tbody></table>       </td></tr>
      </tbody></table>
     </td>

<p align="justify">
	Se debe contar con un chip con crédito, se debe verificar que el chip no tenga el crédito congelado y la ranura del chip es del tamaño de un SIM convencional si el chip es nano o micro, se recomienda usar un adaptador.
</p>

## Obtener

<p align="justify">
	El dispositivo se compro en esta tienda:
</p>

<p align="justify">
	<a href="https://localizadorgpstracker.com.mx/localizador-gps-tracker-puebla">Localizador GPS en Puebla.</a>
</p>

<p>
	Pero se puede comprar online desde plataformas como:
</p>

<ul>
<li>
	<p align="justify">
		<a href="https://articulo.mercadolibre.com.mx/MLM-585446943-localizador-gps-tracker-tk102-rastreador-personal-_JM?source=gps">Mercadolibre</a>
	</p>
</li>
<li>
	<p align="justify">
	<a href="https://spanish.alibaba.com/trade/search?SearchText=tk102&selectedTab=products">Alibaba</a>
</p>
</li>
<li>
	<p align="justify">
	<a href="https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2050601.m570.l1313.TR11.TRC1.A0.H0.Xtk102-2.TRS0&_nkw=tk102-2&_sacat=0">Ebay</a>
</p>
</li>
<li>
	<p align="justify">
	<a href="https://www.amazon.es/Localizador-port%C3%A1til-Xexun-TK-102-2-MicroSD/dp/B00S9Y83OE">Amazon</a>
</p>
</li>
</ul>

## Comandos

<p align="justify">
	Estos comandos se envian via <i>SMS</i> al número del chip del celular.
</p>

<p align="justify">
	Por defecto el <i>TK102</i> viene previamente configurado, si marcamos sonara dos pitidos y se escuchará como ocupado, posterior a eso recibiremos un <i>SMS</i> con las coordenadas.
</p>


<p align="center">
	<img src="https://github.com/ginppian/TK102/blob/master/imgs/img5.jpeg" width="320" height="568">
</p>

<p align="justify">
	Para comandos más especificos podemos consultar los manuales o videos <a href="https://localizadorgpstracker.com.mx/comprar/manual-tk-102">aquí</a>.
</p>

### Asociar al servidor

* Begin123456
* Adminip123456 138.68.5.186 5001

#### Puertos

<p align="justify">
	En nuestro caso usamos el puerto <i>5001</i> pero debemos intentar con los demás puertos para los clones Chinos.
</p>

<p align="justify">
	En mi caso aun que pensé haber comprado un origial y el puerto marcado en <a href="https://www.traccar.org/devices/">Supported Devices</a> que es el <i>5006</i> no funcionó hay que considerar su documentación para <a href="https://www.traccar.org/clones/">clones chinos</a>.
</p>

<ol>
	<li>
		<a href="https://www.traccar.org/clones/">Lista Puertos</a>
	</li>
</ol>

<p align="justify">
	En nuestro caso usamos el puerto <b>5001</b> para asociarlo con <i>Traccar</i>.
</p>

<p align="justify">
	Sí el chip y es Telcel:
</p>

* Apn123456 internet.itelcel.com

* Up123456 webgprs, webgprs2002

<p align="justify">
	Sí es Movistar:
</p>

* Apn123456 internet.movistar.mx

* Up123456 webgprs,webgprs

* Gprs123456

* Tracker123456

* Time zone12345678 -7

<p align="justify">
	Para ver los parámetros
</p>

* Check123456

<p align="justify">
	Para saber el IMAEI y darlo de alta en Traccar
</p>

* Imei123456

<p align="justify">
	El la frecuencia que se enviará
</p>

* Fix060s030m***n123456

<p align="justify">
	Sino lo agarra probamos con este
</p>

* Fix060s***n123456

<p align="justify">
	Por último
</p>

* Save060s***n123456

### Uso de la Micro SD

<p align="center">
	<img src="https://github.com/ginppian/TK102/blob/master/imgs/img4.jpeg" width="360" height="640">
</p>


## Fuente

* <a href="https://localizadorgpstracker.com.mx/blog/guias/170-guia-manual-de-localizador-gps-tracker-102">Guía del Manual de Localizador GPS Tracker 102</a>

* <a href="https://localizadorgpstracker.com.mx/comprar/manual-tk-102">Manual en Video de Localizador GPS Tracker TK 102</a>

* <a href="http://www.localizadorgpstracker.com.mx/manualtk102EN-1.pdf">Manual TK102EN</a>

* <a href="https://www.youtube.com/watch?v=7PskGCE_sUc">Youtube - GPS TK-102 Live Real time Tracking 2G GRPS Setup DJI Phantom Drone</a>

* <a href="https://www.traccar.org/devices/">Supported Devices</a>

* <a href="http://www.securamente.com/como-instalar-y-configurar-un-localizador-de-gps-configuracion-basica-por-gprs/">Como instalar y configurar un localizador de GPS: Configuración básica por GPRS</a>

## Interesantes

* <a href="https://www.youtube.com/watch?v=9rQPqezkWgs">Youtube - Instalacion GPS Tk103 Instalacion Parte 1</a>

* <a href="http://www.opengts.org/">OpenGTS Project</a>

* <a href="https://articulo.mercadolibre.com.mx/MLM-560437507-gps-tracker-plataforma-web-rastreo-localizacion-licencia1mes-_JM?source=gps">Renta Mensual</a>