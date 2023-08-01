## CONFIGURACION
- Tener configurado Arduino IDE.
- Contar con el sensor DHT11.
- Tener la configuración de conexión entre la ESP32CAM y la computadora (con el sensor FTDI).

## PASOS
- Clonar el código del repositorio de GitHub para la aplicación del sensor DHT11, el link es: https://github.com/codigo-iot/esp32cam-mqtt-json-no-bloqueante/tree/main
- Colocar los datos de tu red de internet (ssid = nombre de la red; Password = contraseña de la red).
- Colocar el nombre de la ip del servidor mqtt (puede encontrarse con el comando "$ ifconfig", en la sección enp0s3.
- Cargar el código a la ESP32CAM.
- Ver el funcionamiento del sensor de temperatura y humedad.
