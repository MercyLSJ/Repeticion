# Repeticion
Grupo N°3 - K1051

Trabajo #3 — Repetición de Frase

Problema:
---------

Enviar una frase a la salida estándar muchas veces.

Restricciones:
--------------

Realizar dos versiones del algoritmo y una implementación para cada uno:

- Salto condicional.
- Iterativa esctructurada.

Entregables:
------------

- Sufijo de carpeta: Repetición
- readme.md con los dos algoritmos.
- Implementación: Saltos.cpp.
- Implementación: Iteración.cpp.

Entrega:
--------

- A las 13:00, Abr 27

Análisis:
-----------

Una frase predefinida tiene que ser repetida 200 veces. Para ello, se realizaron dos versiones del mismo algoritmo. 

En la primer versión del algoritmo se ha elegido realizar un bucle retornado al inicio de la función hasta que una variable tome cierto valor. Primeramente se setea un valor de inicio, luego se comprueba que ese valor sea inferior al valor deseado, imprime el texto y, finalmente, incrementa en "1" el valor de la variable. Luego retorna al prinicipio de la función y vuelve a realizar el mismo proceso hasta que la variable alcanza el valor deseado.

![alt tag](http://image.prntscr.com/image/59bea2834a03438f8f64d90835961c7c.png)

En la segunda versión del algoritmo se ha elegido realizar un bucle FOR que se ejecuta hasta que una variable tome un cierto valor; manejando su valor de inicio e incremento durante cada iteración del ciclo. De esta manera tendremos un bucle con 200 iteraciones.

![alt tag](http://image.prntscr.com/image/16e06d2ceba640a4a5d2f537f9767134.png)
 

Algoritmo:
----------

- Primera versión - Saltos.cpp

1. Establecer valor inicial de variable.
2. Comprobar: Variable < 200.
3. Imprimir frase.
4. Incrementar variable en "1".
5. Regresar al punto 2.


- Segunda version - Iteracion.cpp

1. Establecer condiciones: Valor inicial de variable, Variable < 200, Incremento de variable.
2. Imprimir frase hasta alcanzar el valor final.
