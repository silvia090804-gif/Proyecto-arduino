# Proyecto-arduino
LED Pong – Proyecto Arduino

Objetivo del proyecto
Crear un juego estilo Pong utilizando 5 LEDs, un Arduino UNO y dos botones.
La “pelota” recorre los LEDs de izquierda a derecha y rebota.
Al pulsar un botón justo cuando la pelota está en su extremo, la velocidad aumenta.

Integrante 1: Silvia Cornejo Bru
Diseño y Circuito
Integrante 2: Carmen Díaz Monreal
Programador y pruebas

SPRINT 1
Día 1 – 11 de noviembre
Objetivo: Primer acercamiento al circuito.
Creación del prototipo del circuito en Tinkercad.
Se define la disposición básica de los LEDs y la estructura inicial del código.

Día 2 – 13 de noviembre
Objetivo: Mejorar el prototipo y comenzar la lógica del juego.
Montamos el circuito en Tinkercad con algunos cambios respecto al día anterior.
Se añadieron más LEDs para ampliar el “campo de juego”.
Se comprobó el funcionamiento individual de cada LED.
Implementamos el movimiento del LED activo usando estructuras if.
Problema detectado: el último LED (LED 5) no respondía.
Decisión: migrar la lógica de control a un switch() para mayor claridad y facilidad de ampliación.

Día 3 – 18 de noviembre
Objetivo: Añadir interacción con el usuario y preparar el montaje real.
Implementación de interrupciones con attachInterrupt() para detectar pulsaciones de botones.
Creación del array leds[] para gestionar y almacenar la posición actual del LED activo.
Corrección de errores: los pines de los botones estaban configurados de forma incorrecta en el setup(), lo que impedía su funcionamiento adecuado.
Montaje físico del proyecto: se ensambló el circuito en protoboard.

Día 4 – 20 de noviembre
Objetivo: Pulir, optimizar y probar el juego completo.
Optimización del código: limpieza de funciones, reorganización de variables y mejora de la estructura con switch().
Ajuste de la velocidad del juego y del tiempo de rebote entre LEDs.
Pruebas completas del juego en el montaje físico para asegurar que los LEDs, botones e interrupciones funcionaran de forma estable.
Documentación del proyecto para preparar la entrega/presentación.

Estado del Proyecto:
Movimiento correcto
Rebote en ambos extremos
Interrupciones funcionales
Aumento de velocidad al pulsar botón en el borde

Tareas Pendientes:
Añadir un Buzzer 


SPRINT 2
Dia 5 - 25 noviembre
entrega sprint 1





Implementación del código final funcional.
