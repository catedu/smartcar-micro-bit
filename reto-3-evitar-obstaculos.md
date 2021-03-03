#Reto 3 Evitar obstáculos

¿Cómo no? lo pide a gritos ! vamos a hacer un [roomba](https://catedu.github.io/robotica-educativa-con-mbot/evitar_obstculos.html)

{% youtube %}https://www.youtube.com/watch?v=nVwOLRhooOc{% endyoutube %}

##Descripción del proyecto
Empezamos el programa que al iniciar vaya recto:

![](/assets/482fc933-4375-4ddf-b217-3c9e85d24902.jpg)

Luego hacemos el bucle "para siempre":
* El sensor no funciona muy fino, hay veces que da *0 falsos* por lo tanto el bucle **si** ponemos una condición **si es mayor de 5 y es menor de 10** para quitarnos estos falsos positivos de obstáculos.
* si encuentra obstáculo, que pare un poco, que *recule* y que gire
 * cada instrucción anterior con una pequeña pausa, cuanto más grande sea la pausa más *reculará*, girará etc..
* si no encuentra obstáculo que siga recto

![](/assets/romba.jpg)

Aquí lo tienes en editor

<div style="position:relative;height:calc(300px + 5em);width:100%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_XwHXA21Kd4up" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

##Reto
Si te fijas sólo gira a la derecha. Modifica el anterior programa para que gira a la derecha o a la izquierda de forma aleatoria.
