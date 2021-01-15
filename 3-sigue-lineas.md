#Sigue líneas
El sigue-lineas son dos sensores que están colocados debajo del robot

![](https://i.imgur.com/BOpsVvF.jpg)

Por unificar criterios, los conectaremos en P3 y P4

![](https://i.imgur.com/kzPngGo.jpg)

Cada sensor tiene dos leds, uno emisor y otro receptor. El receptor recoge la luz reflejada, si hay debajo algo que no refleja la luz (por ejemlo una línea negra) entonces manda OFF en caso contrario ON

![](https://i.imgur.com/UdHpeaS.jpg)

OJO VA AL REVÉS es decir 
 * cuando hay linea negra es OFF
 * cuando no hay linea es ON 

por lo tanto queremos:

* Que cuando sea OFF sea un 1 lógico (línea)
* Que cuando sea ON sea un 0 lógico (no hay línea)

Esto se llama **CONFIGURACIÓN PULL-UP** (pincha [aquí](https://catedu.github.io/programa-arduino-mediante-codigo/resistencias_pullup_y_pulldown.html) para saber más) luego lo primero que tenemos que hacer es configurar estos sensores como PULL-UP con estas instrucciones (han traducido **UP** como *subir*):

![](/assets/97c1e8aa-a59f-415a-b0a4-1690cd2f09cf.jpg)

Están un poco escondidas:

![](/assets/dc1c5e64-9cab-4c26-acd1-22b783e25b05.jpg)

Y luego crear unas variables por ejemplo **izquierda** y **derecha** dentro del bucle que lean esos sensores. El resto del código sólo utilizaremos estas variables:

![](/assets/025621f1-6127-4cc4-9c8f-55881e2049b0.jpg)