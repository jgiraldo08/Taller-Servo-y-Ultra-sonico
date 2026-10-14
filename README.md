# Taller-Servo-y-Ultrasónico
Este taller fue realizado por los integrantes pertenecientes a la facultad de Ingenieria, programa de Ingenieria de Sistemas de la Corporacion Universitaria Americana:
**Juan Esteban Giraldo Suarez**
**Jhonn Andres Colina Ricardo**
**Aldimar Saltarin Arteta**
**Wainer Ascencio Torres**
**Samuel Rodriguez Sanchez**

Este taller demuestra cómo un sistema embebido puede percibir su entorno, tomar una decisión y actuar sobre él de forma automática. El HY-SRF05 (en nuestro caso, por falta del sensor HC-SR04) mide la distancia de un objeto calculando el tiempo que tarda el eco ultrasónico en regresar. El Arduino interpreta esa medida y, si el objeto está a menos de 15 cm, ordena al servomotor moverse a 90° para abrir la puerta. Si está más lejos, la devuelve a 0°.

La práctica refleja el ciclo básico de la automatización: detectar, procesar y actuar. También permite ver la diferencia entre una entrada (el sensor) y una salida (el servo), y cómo la biblioteca Servo.h simplifica el control por pulsos PWM, que en un servo definen una posición y no una potencia.

En conjunto, el proyecto integra conceptos de electrónica, programación y depuración, y muestra una aplicación real similar a las puertas automáticas de comercios y edificios
