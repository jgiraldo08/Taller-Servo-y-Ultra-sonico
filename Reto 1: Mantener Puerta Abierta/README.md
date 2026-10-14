Para este primer reto, trataba de lograr que cuando el sensor detectara un objeto a una distancia menor o igual a 15 centimetros,
la puerta se mantuviera abierta unos 3 segundos a 90º. una vez finalizado ese tiempo, tendria que volver a cerrarse la puerta en 0º

Respondiendo a la pregunta: 
¿Qué problema podría producir utilizar delay(3000)?
Mientras se realizaba esta prueba, se pudo evidenciar que al establecer el delay en 3000, tanto el tiempo de deteccion como el tiempo de espera iban a durar 3 
segundos, lo que hubiera quedado en un mal procedimiento pues lo que se busca es que al detectar un objeto, reaccione esponaneamente el servomotor, y despues
espere 3 segundos a cerrarse de nuevo.
