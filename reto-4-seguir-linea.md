#Reto 4 Seguir la línea

Otro reto que pide a gritos este sensor:

{% youtube %}https://www.youtube.com/watch?v=cY6nqgHxXio{% endyoutube %}

>Consejo: en clase, antes de atacar con este reto, aconsejamos otro más sencillo como que el robot se mueva y si encuentra línea que se pare, este reto lo puedes ver [aquí](https://www.elecfreaks.com/learn-en/motor_bit_smart_car_case_01/)

#Descripción del programa

Al empezar configuraremos los sensores en PULL-UP tal y [como hemos explicado](/sigue-lineas.md):

![](/assets/dec05d16-8707-4016-9c14-3091cd1f5af8.jpg)
Luego entramos en el bucle donde simplemente dice:

* Sigue hacia **delante**
* Lee los sigue-líneas
* Si te desvías hacia la **derecha **gira a la **izquierda**
* Si te desvías hacia la **izquierda **gira a la **derecha**

![](/assets/a208fdf2-0792-4af6-b75a-bb8ec681aa19.jpg)
El programa tiene la pega que si aumentamos la velocidad, pierde la línea.

Evidentemente hay muchas versiones y mejoras, por ejemplo [aquí](https://www.elecfreaks.com/learn-en/motor_bit_smart_car_case_03/)
 pero ésta https://makecode.microbit.org/_U3VP8JhVTXaJ es desde luego la versión más sencilla.
 
 <div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_U3VP8JhVTXaJ" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>
