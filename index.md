### M5StickC

Bienvenido al Internet de las Cosas.

Para comenzar a utilizar tu M5StickC y encontrar toda la información técnica, te recomendamos consultar siguiente información:

* Encender por primera vez. Al llegar de fábrica la batería estará descargada y por cuestiones de diseño, el M5StickC no arrancará hasta que sigas el siguiente procedimiento: 
1. Conectar G0 a 3V3. 
2. Conecter el cable usb. 
3. Cargar el dispositivo al menos 2 horas. Después de esto, desconecta G0 a 3.3V y podrás programar normalmente con la IDE de Arduino.
4. Te recomendamos que no dejes que la batería se descargue totalmente, puesto que tendrás que repetir este procedimiento.  El tiempo en standby  de la batería es de aproximadamente 10 horas. Corriendo un sketch es muy variable. Lo que más consume es WiFi/BLE y el display.

![m5stick](m5stickc_05.jpg)  

* TL;DR  Arduino IDE
1. Agrega el dispositivo con Board Manager (es el mismo que ESP32):
     https://dl.espressif.com/dl/package_esp32_index.json
2. Instala la librería desde Manage Libraries. El nombre de la librería es: 
        M5StickC
3. Selecciona la tarjeta M5StickC y el baudrate 115200.
4. Programa el ejemplo que encontrarás en el IDE de Arduino examples/ExamplesFromCustomLibraries/M5StickC/Games/FlappyBird   
-PROTIP: Para cargar el sketch deja desconectado cualquier cable de los GPIOs y presiona el botón de power mientras se está subiendo el sketch.  

* Programación con Arduino IDE (versión larga)
[M5StickC Quick Start - Arduino Win](https://docs.m5stack.com/#/en/quick_start/m5stickc/m5stickc_quick_start_with_arduino_Windows?id=_2-install-esp32-boards-manager)

* Facebook.
[Grupo de Facebook en español sobre Internet de las Cosas](https://www.facebook.com/groups/724628401049648/)

* Documentación oficial del fabricante.
[M5Stack Docs | M5StickC](https://docs.m5stack.com/#/en/core/m5stickc)

* Videos
[Tutorial para programar con Arduino IDE](https://www.youtube.com/watch?v=ppXkl0046dc)

* Foro oficial del fabricante.
[Foro oficial de M5Stack, fabricante de M5StickC](http://community.m5stack.com/)

* Código en Github relacionado con el M5StickC:
[M5StickC en Github](https://github.com/search?q=m5stickc)

* Información detallada sobre el chip que maneja la carga de la batería dentro del M5StickC (en japonés, pero Google translate lo traduce automáticamente en Chrome). 
[Examine the battery management AXP 192 of M5StickC](https://lang-ship.com/blog/?p=523#GetWarningLeve_006)

* Información general del ESP32
[ESP32 docs en Cosismo](https://cosismo.github.io/esp32-devkit/)



¡Suerte!  
  Equipo Cosismo
