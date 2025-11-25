# Proyecto-arduino
LED Pong – Proyecto Arduino

Objetivo del proyecto
Crear un juego estilo Pong utilizando 5 LEDs, un Arduino UNO y dos botones.
La “pelota” recorre los LEDs de izquierda a derecha y rebota.
Si un jugador pulsa su botón justo cuando la pelota está en su extremo, la velocidad aumenta.

Integrante 1: Silvia Cornejo Bru
Diseño y Circuito
Integrante 2: Carmen Díaz Monreal
Programador y pruebas

Día 1
Prototipo del circuito en Tinkercad


Día 2
Montamos el circuito en Tinkercad con algunos cambios y añadimos más LEDS.
Comprobamos funcionamiento de cada LED.
Implementamos movimiento con if.
Problema: el último LED (LED 5) no funcionaba.
Decisión: cambiar la estructura por switch().

Día 3
Se implementan interrupciones con attachInterrupt.
Se crea array leds[] para conocer la posición actual.
Solución de error en el setup de los pins de los botones, los cuales estaban cambiados y daban error.
Montaje Fisico del Proyecto.

Estado Actual del Proyecto:
Movimiento correcto
Rebote en ambos extremos
Interrupciones funcionales
Aumento de velocidad al pulsar botón en el borde

Tareas Pendientes:
Añadir un Buzzer 


Pruebas, correcciones y depuración de rebotes.

Implementación del código final funcional.
