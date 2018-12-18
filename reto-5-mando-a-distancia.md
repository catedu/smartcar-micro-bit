#Rento 5 Mando a distancia
Esta vez **vamos a utilizar dos micro:BITs** 

{% youtube %}https://youtu.be/oxumk9GYoVU{% endyoutube %}

##Descripción del programa
###Microbit que hace de mando
Este microBIT hay que alimentarlo con pilas o utilizando una batería típica de móvil. 

El mando se inicia en un grupo (en este caso el 222) y simplemente realiza lo siguiente:
* Si se pulsa A manda un 1 y lo visualizo
* Si se pulsa B manda un 2 y lo visualizo
* Si se pulsa A+B manda un 3 y lo visualizo

![](/assets/1ebdfdd1-ed27-48fc-ad8c-cf02f38da19e.jpg)

El programa te lo puedes descargar [aquí](https://makecode.microbit.org/_cWz6s9aeTPXr):

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_cWz6s9aeTPXr" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>

###Microbit que está en SmartCar

Al iniciar el programa asigna este microbit al mismo grupo de radio que el mando y además asigna una nueva variable con valor 0

![](/assets/6597676b-466a-4019-bb3e-f87e5d8504d8.jpg)

Al recibir un número lo asigna a esa variable y además lo muestra:

![](/assets/a703a39c-4c72-444d-ba21-2842faa5594c.jpg)

Y establecemos un bucle por siempre que :

* Si no ha recibido nada, es por lo tanto dato=0 luego que siga hacia delante
* Si recibe 1 que gire hacia la derecha y hacia atrás
* Si recibe 2 igualmente pero al otro lado
* Si recibe 3 que pare
* En los tres casos anteriores damos un tiempo para que ejecute la instrucción con una pausa y luego reseteamos dato para que siga el robot su camino

![](/assets/ab7ed7d2-35ce-4692-b050-a7c4f26937f1.jpg)

El proyecto te lo puedes descargar [aquí](https://makecode.microbit.org/_ftuFv8AReFYq) :

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_ftuFv8AReFYq" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>



*Nota:*
>Intenté también hacer un mando a distancia que funcionase con la brújula interna de microbit, es decir:
* Si pulsaba A entonces se ponía en marcha
* Si giraba el mando a distancia, el robot giraba en el mismo sentido
* Si pulsaba B entonces se paraba

>**No conseguí que funcionase fino**, por lo que he dedicido quitarlo del curso, pero si alguien lo quiere probar, [aquí ](https://makecode.microbit.org/_em59Y08D2J9E)está el programa del mando y [aquí ](https://makecode.microbit.org/_irv9TsEE3fwh)el del coche.
