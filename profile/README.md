## Meshtastic Argentina Community

Grupo dedicado a la investigación y ayuda cooperativa sobre la red Meshtastic https://meshtastic.org/ en Argentina y redes afines tipo malla por LoRa.

---
A group dedicated to provide information and cooperative assistance about the topic of the Meshtastic network https://meshtastic.org/ in Argentina.
---
### Nuestra web https://mesharg.com.ar/
### Unite a nuestro grupo de Telegram en https://t.me/meshtastic_argentina
### Facebook https://www.facebook.com/groups/1174679143561270/
### O podés ingresar a nuestro Discord https://discord.gg/ytYsNpZC6
### XMPP en https://xmpp.link/#mesharg%40conference.conversations.im%3Fjoin - xmpp:mesharg@conference.conversations.im
### Mándanos un mail a contacto(en)mesharg.com.ar
---
Breve listado de mapas online, conviene ir revisando todos periódicamente y cada uno tiene su configuración particular:

https://meshtastic.liamcottle.net/ -> Depende de configuración MQTT (Global)

https://meshmap.net/ -> Depende de configuración MQTT (Global)

https://meshsense.affirmatech.com/ -> Depende de reporte de usuarios habilitado en la malla (Global)

https://carlosvaccaro.com.ar/mapa/ -> Depende de configuración MQTT (Neunquén)

https://meshseer.nemexix.com (este deja ver los últimos mensajes recibidos) -> 100% por LoRa (AMBA - MediumFast)

Atención: hay mucha cantidad de nodos que no eligen compartir ubicación, así que no desanimarse si no aparece ninguno cerca.

---
### Canales activos (secundarios) en Meshtastic Argentina
| Canal | PSK | Región | Modo |
|--------|-----------|--------|--------|
| BairesMesh | aB3K7ZIciBKq49nxn5gVmPQEtbTUVZOHKxuCaCKaHtA= | CABA & AMBA | MediumFast 
| RosarioMesh | kss+4MMhc9unauU8i6bix0Lt/pkjWMv1PIFr0fH8g58= | Rosario | LongFast
| NQNmesh | B7jYDJLWy9TSnajWI/yAJETLBcjN2RNXUU4jS4eRyJo= | Neuquén | LongFast
| CordobaMesh |  CoRd0B4lHaBoN6OWT0u2EvNX9Jci7gsIiIJtD30BCCw= | Córdoba | LongFast
| ERMesh | w9nTAUTYp2eFo7KyCfo5a42YSM4ewfrV/PSoxcjrAPI= | Entre Ríos | LongFast
| MendozaMesh | yVyN1359YQb0S1LW2cslgMrXHbTkHnR1TSHYDa7VCCs= | Mendoza | LongFast

---
## Equipamiento mínimo para armar un nodo portátil Meshtastic

Opciones de placas recomendadas:

**HelTec T114 (v2)**  👉 [Tienda Starware](https://tienda.starware.com.ar/producto/placa-desarrollo-lora-bt-gps-heltec-mesh-node-t114-nrf52840sx1262-v20-pantalla/) Viene con Bluetooth y pantalla. Ideal para empezar.

**HelTec T114 (v2) kit con GPS**
  👉 [Tienda Starware](https://tienda.starware.com.ar/producto/kit-desarrollo-lora-bt-gps-heltec-antena-mesh-node-t114-nrf52840sx1262-v2/)
  Viene con Bluetooth, GPS y pantalla. Ideal para empezar.

**HELTEC LORA32 V3 (kit con gabinete)**
  👉 [Tienda Starware](https://tienda.starware.com.ar/producto/placa-desarrollo-iot-lora-heltec-lora32-v3-node-sx1262-esp32-s3-868-928mhz/)
  Viene con Bluetooth y WiFi. Simple y clásico. Consume bastante energía más energía que el T114 y ya no es recomendable para nodos portátiles a batería.

⚠️ **Importante:** Si comprás en otro lado, asegurate de que la frecuencia sea **915 MHz** o cercano y cuidado con la versión de HelTec: buscá que sea **v3** o **T114 v2** ⚠️
---
Software y configuración: (Antes de enchufar o programar tu placa, asegurate que la antena esté conectada)

- **Flasheo del firmware:**  
  👉 [https://flasher.meshtastic.org/](https://flasher.meshtastic.org/)

- **App oficial para Android:**  
  👉 [Google Play](https://play.google.com/store/apps/details?id=com.geeksville.mesh&hl=es&pli=1)

- **Región de radio:**  
  Configurá la región como **ANZ** y el preset LoRa que corresponda a la región en donde te encuentres. Esto asegura compatibilidad con la red local. Desde ahí podés elegir tu nombre de usuario.
  Con esta configuración básica, si hay en las cercanías otros nodos, van a ir apareciendo en el listado de la app. Si no ves ninguno, puede ser que no haya nadie cerca. Como todo equipo de radio, depende de la altura, el despeje y la distancia con el resto de los integrantes de la malla. Y hay que tener en cuenta que Meshtstic es un sistema de radio que permite el intercambio de mensajes, no un sistema de chat, así que puede darse el caso de que veas otros nodos, recibas mensajes, pero ellos no te "escuchen": en ese caso, buscar otra posición con más altura y despeje. ALTURA MATA ANTENA, es decir, que por más equipo y antena que tengas, si estás muy bajo o muy cubierto, puede ser que no funcione.

  📎 ANZ es la región adoptada oficialmente en Argentina para operar en frecuencias libres:  
  👉 [Resolución ENACOM 581/2018 – AU915-928](https://www.enacom.gob.ar/multimedia/normativas/2018/res581MM.pdf)

- **Zona horaria para Argentina:**  
  Al configurar el equipo, en el menú Device, ingresá **ART3** en la POSIX Timezone para que salga la hora correcta en pantalla.

---
Meshtastic® is a registered trademark of Meshtastic LLC. Meshtastic software components are released under various licenses, see GitHub for details. No warranty is provided - use at your own risk.

Mallas amigas:
Bahía Blanca y alrededores: https://github.com/sudoestemesh
