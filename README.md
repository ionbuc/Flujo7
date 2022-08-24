# Flujo7
# Flujo para representar la temperatura y la humedad publicada por el ESP32CAM tomadas con el sensor DHT11
# Mostradas con gráficas
Introducción.
Los datos atmosféricos se deben obtener en tiempo real para ser utilizados correctamente, de ahí su importancia de transmitirlos en el momento que se están obteniendo, en este ejercicio se obtienen la temperatura y la humedad de forma local mediante un sensor y son enviados mediante interfaz Wifi, con el fin de visualizarlos gráficamente en una página web en cualquier parte del mundo.

El envío de los datos se realiza mediante el protocolo MQTT, el cual es ampliamente utilizado en el internet de la cosas (IoT), el broker MQTT es el encargado de enlazar los datos entre los dispositivos que publican datos y los dispositivos que quieren recibirlos.

La parte hardware del ejercicio está formada por el sensor DHT111 que capta la temperatura y la humedad del lugar donde se encuentra y la información es recibida por el microcontrolador ESP32CAM, para enviarla a la red de internet, para que el microcontrolador realice este proceso se programó mediante el IDE  de Arduino, ambiente de desarrollo muy conocido y el cual apoya con muchas bibliotecas de la comunidad que ahorran mucho tiempo de desarrollo.

En la parte de la representación gráfica se utilizó el ambiente de desarrollo "Node red" el cual nos permite programar flujos visuales y conectar el servidor con el broket MQTT.


Material necesario.
Hardware:
	• Sensor DHT 111
	• ESP32CAM
	•  Convertidor FTDI TTL-USB FT32RL
	
Software:
	• NodeRed
	• MQTT
	• IDE Arduino

Material de referencia:
	- Introducción al ESP32CAM
	- Configuración del IDE para ESP32CAM
	- Conexión del ESP32CAM a Wifi
	- Enviar y recibir mensajes MQTT con el ESP32CAM
	- Introducción a MQTT (broket Mosquitto)
	- Instalación de mosquitto en Ubuntu 20.04
	- Introducción a NodeRed.
	- Instalación de NodeRed en Ubuntu 20.04
	
Instrucciones.
