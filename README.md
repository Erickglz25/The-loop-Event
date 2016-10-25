The loop Event
===================
----------

##¿Qué es el evento loop?
-------------
###Programacíon Síncrona vs Asíncrona
Quizas como el presentador expone, no es facil,  al encontrarnos con este tipo de programacion por primera vez, ver los beneficios de la asincronia en un servidor  y mas dificil es aun entender el funcionamiento interno que esta representa.

Comenzando con un aspecto importante, se nos  muestra la gran ventaja que representa la asincronia, "**mantener un flujo natural en el navegador**". No permitir bloqueos inecesarios  de codigo (eventos lentos) y peor aun, acumulativos, en lugar de actuar de manera asincrona pero en muchos casos mas rapida. 

Particularmente la presentacion aborda una cuestion interesante, el reto de entender la asincronia surge al preguntarnos ¿Como es que javascript maneja la asincronia por si solo?, realmente no lo hace.

El evento loop como ya lo menciona el titulo del video, es una manera de manejar las respuestas de la asincronia, si nuestro stack se ecuentra vacio las funciones asincronas pueden ser procesadas por Javascript en orden desde el task queue, y no necesariamente de manera sincrona, dejando el stack libre para procesar codigo sincrono pero listo y delegando funciones a webapis, Aumentando asi el flujo del navegador al no bloquear respuestas por esperar por algun bloque de codigo 

____________________

[1]: https://www.youtube.com/watch?v=8aGhZQkoFbQ"Loop_Event"