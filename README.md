# pi-tor-router
Create a TOR Router with a Raspberry Pi (via ethernet).

Mientras hacía un proyecto totalmente similar a este, se me ocurrió una 
manera distinta de enrutar el tráfico de TOR.

El proyecto se basaba principalmente en este, pero con la integración de 
un portal cautivo, que permite al público mostrar un mensaje con unas 
condiciones antes de acceder a la red.
Para el portal cautivo estaba usando NoDogSplash, pero no hubo medio de 
redirigir el tráfico TOR desde la misma raspberry via Wi-Fi con 
NoDogSplash, ya que NoDogSplash crea sus reglas automáticamente. Puede 
que realmente se pueda hacer algo, pero yo no lo conseguí.

Mi Plan A era redirigir el tráfico a TOR desde la misma Raspberry, pero 
en caso de no fuese posible tenía que recurrir al Plan B.

El Plan B era redirigir el tráfico a TOR desde mi mismo Router ASUS 
(firmware Merlin), que permite esa opción.

Pero pensé que en caso de no tener un router con esta capacidad se tenía 
que poder hacer de otra forma, así que adapté la guía en la que me 
estaba basando para redirigir el tráfico via Ethernet, con un dongle USB 
Ethernet, y como funcionó, lo quiero compartir.

