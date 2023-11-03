Creador Listas IPTV Libre
=========================
Este es un creador de listas m3u8 con canales libres. 

Esta es una lista de reproducción M3U para canales de televisión gratuitos en español y algunos del mundo.

Ya sea gratis localmente (por aire)

<img src="https://hatscripts.github.io/circle-flags/flags/ar.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/br.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/ca.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/co.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/cr.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/do.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/ec.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/um.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/fr.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/de.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/it.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/mx.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/py.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/pe.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/es.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/ve.svg" width="24"> <img src="https://hatscripts.github.io/circle-flags/flags/ve.svg" width="24"> 

Para usarlo, use en su reproductor de IPTV, la lista: https://raw.githubusercontent.com/luisflow/iptvcreator/main/tvlibre.m3u8

Filosofia
==========

Los principales objetivos de esta lista de reproducción se enumeran a continuación.

**Solo canales gratuitos**

Si un canal normalmente sólo está disponible mediante suscripciones comerciales, no tiene nada que ver en esta lista de reproducción. Si, por otro lado, se proporciona de forma gratuita para todos en un país en particular, entonces debería estar en esta lista de reproducción.

- Sin canales pagos
- Sólo canales que se ofrecen oficialmente de forma gratuita (a través de DVB-S, DVB-T, analógico, etc.)

**Solo canales convencionales**

Esta es una lista de reproducción para todos.

- No hay canales para adultos.
- No hay canales dedicados a ninguna religión en particular.
- No hay canales dedicados a ningún partido político en particular.
- No hay canales creados para un país y financiados por un país diferente.

Fuentes de alimentación
============

Puede resultar bastante difícil encontrar URL actualizadas; aquí hay una lista de fuentes:

- https://github.com/iptv-org/iptv/tree/master/streams
- Youtube: Siempre que el canal esté en directo y su URL no cambie (consulta la antigüedad del stream, el número de espectadores...)
- Dailymotion: Mismo criterio que para youtube

Formato
=======

La lista de reproducción m3u8 se genera mediante `crear_playlist.py`, utilizando los archivos `.md` ubicados en la carpeta `listas`.

Cada archivo `.md` representa un grupo. La línea `<h1>` se utiliza como título del grupo.

Solo los canales cuya columna URL comienza con `[>]` se incluyen en la lista de reproducción.

Los canales que no están en HD están marcados con un `Ⓢ`.

Los canales que utilizan bloqueo GeoIP están marcados con un `Ⓖ`.

Los canales que son canales de Youtube en vivo están marcados con un `Ⓨ`.


Asuntos
=======

Solo cree bugs para errores y solicitudes de funciones.

No cree bugs para agregar/editar o eliminar canales. Si desea agregar/editar/eliminar canales, cree una solicitud de incorporación directamente.

Solicitudes de incorporación
============================

**Solo modifica archivos .md**

Si su solicita incorporar o modifica canales, modifique solo archivos `.md`. No modifique los archivos m3u8 en su solicitud de incorporación.

**Agregar un nuevo canal**

Para agregar un nuevo canal, realice una solicitud de incorporación.

- En tu solicitud de incorporación debes proporcionar información para demostrar que el canal es gratuito.
- Utilice imgur.com para alojar el logotipo del canal y señalarlo.
- Si tienes una secuencia válida, agrégala y pon `[>]` delante de ella.
- Si no tienes una transmisión para el canal, agrega `[x]()` en la columna URL y coloca tu canal en la categoría No válido.
- Si tienes un stream pero no funciona bien, pon el canal en la categoría No válido y pon `[x]` delante de la URL.
- Si agrega URL geobloqueadas, especifíquelo en su PR y especifique en qué país están trabajando. El PR solo se fusionará si estas URL se pueden probar.

**Eliminar un canal**

Para eliminar un canal, realice una solicitud de extracción.

En su solicitud de extracción, debe proporcionar información para mostrar que el canal solo está disponible a través de una suscripción privada paga.

Nota: Los impuestos públicos (ya sean nacionales o autonómicos, se llamen Licencia de TV o no) no constituyen una suscripción privada de pago.

Si una transmisión no funciona, simplemente mueva el canal a la categoría no válida y reemplace `[>]` con `[x]` en la columna de URL.


**Derechos y responsabilidades**

La funcion especifica de este codigo es la generacion de listas iptv pero sin romper las normas o ley alguna.

Los canales agregados son y deben ser libres, especificamente canales gratuitos, locales y de trasmision aerea libre.
Si se presentase algun canal que alguien incorpore y este no cumpla las reglas legales debe ser retirado inmediantamente.

Este codigo es basado en su codigo original y ha sido traducido y adaptado a nuevas modificaciones o mejoras
Codigo original y atribuidos a https://github.com/Free-TV/IPTV 
