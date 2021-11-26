# Predicción del precio del Bitcoin usando LSTM (Long Short-Term Memory)
Predicción del precio del bitcoin 

# LSTM

* **Forget Gate**  genera un número entre 0 y 1, donde 1 muestra “mantener esto completamente”; mientras que 0 implica "ignorar esto por completo".

* **Memory Gate**  elige qué datos nuevos deben almacenarse en la celda a través de una capa sigmoidea seguida de una capa tanh. La capa sigmoidea inicial, llamada "capa de puerta de entrada" elige qué valores se modificarán. A continuación, una capa tanh crea un vector de nuevos valores candidatos que podrían agregarse al estado.

* **Output Gate**   decide qué rendimiento se obtendrá de cada celda. El valor obtenido se basará en el estado de la celda junto con los datos filtrados y recién agregados.
