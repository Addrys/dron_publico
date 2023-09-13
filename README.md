# dron_publico
Imágenes e información del proyecto privado "ProyectoDron"

Toca crear el entorno para programar la raspberry pi pico, con el SDK C/C++ de arduino e instalar la toolchain y todas las herramientas necesarias para poder programar con ella, y aprender a usar mediante I2C el sensor acelerometro giroscopio que usaré.
![Raspberry pi pico](https://github.com/Addrys/dron_publico/assets/93978561/6f95b5e1-4fb6-4f17-a852-f4a95a912661)

Arduino Mega para flashear los ESC
![cb254a12-79e0-4cd9-b6b3-9d73794b90a1](https://github.com/Addrys/dron_publico/assets/93978561/56dcdd5a-0f22-4a0b-86ad-46766fad3264)

Pruebas de motor para aprender a controlar uno de los motores

![motor](https://github.com/Addrys/dron_publico/assets/93978561/a973e121-f143-45c9-b5fc-c88794ee314c)

Ahora que ya sé controlar el motor con la raspberry toca montar el sistema completo

Partes a soldar ( 4x Electronic speed controllers [ESC] y Battery Eliminator circuit [BEC] )

![premontaje](https://github.com/Addrys/dron_publico/assets/93978561/a7ac014c-7125-44b0-a0c9-ce5568680ad2)

Soldadura mala pero suficiente debido a que el soldador no calienta lo suficiente (culpa de aliexpress) y el estaño se endurece al enfriarse pasivamente con la placa de cobre que forma el BEC

![soldadura esc](https://github.com/Addrys/dron_publico/assets/93978561/9b82b737-493a-4a7c-bc69-8378ae20c548)

Motor a conectar en el ESC

![motor_imagen](https://github.com/Addrys/dron_publico/assets/93978561/0708a198-a0ba-4d2e-9ad8-11b91850358f)

Parte del montaje
![montaje](https://github.com/Addrys/dron_publico/assets/93978561/f7662c48-a73d-49ca-9c8a-f1813e17651a)
montado, toca probar el sistema con los 4 motores uno a uno, antes hay que flashear cada ESC y configurarlo
![montado](https://github.com/Addrys/dron_publico/assets/93978561/4966e92a-b048-4d7e-9ba6-284854005f0d)

Tras unas pruebas se ha roto el ESC del motor3, por suerte tengo uno de repuesto así que toca sustituirlo
![Reparacion_M3](https://github.com/Addrys/dron_publico/assets/93978561/fef03abc-d376-4c22-81bc-149a60c8b0c5)

Ya con el sistema funcionando al conjunto y tras pruebas y configuraciones para que los 4 motores vayan a la par con el mismo nivel de "acelerador" toca montar la raspberry en el dron
![integracion raspberry en drone](https://github.com/Addrys/dron_publico/assets/93978561/5132eb2c-ace2-4c78-8263-0f7ed4054633)

En este video se puede ver una de las primeras pruebas del dron volando con un PID que intenta estabilizarlo, mientras yo le mando con un potenciometro el valor base de "acelerador"

https://github.com/Addrys/dron_publico/assets/93978561/464934d8-f83c-471c-8719-104de9d967ad

Nuevo microcontrolador Rp2040 para poder depurar la raspberry principal
![rp-zero](https://github.com/Addrys/dron_publico/assets/93978561/573daf1f-a5f6-4cd5-8f2c-02dc02534476)

Capacitores para desacoplar los ESC y estabilizar la entrada de corriente por la batería
![capacitores](https://github.com/Addrys/dron_publico/assets/93978561/80364634-99db-4ee4-bf20-43623265e413)

Sensor de presion para añadir control de altitud
![sensor-presion](https://github.com/Addrys/dron_publico/assets/93978561/b382ca0a-fc95-48e1-bf2f-0dc06a6e3a96)

Placa soldada
![image](https://github.com/Addrys/dron_publico/assets/93978561/54ac5073-fbf9-4c94-911f-ed3821de510d)



Nuevo giroscopio con magnetómetro
![giroscopio-magnetometro](https://github.com/Addrys/dron_publico/assets/93978561/e448a584-bf3b-4225-b789-0c1e25facd23)

