# 2_7ActividadBrokenCode
TEMA1 UD 2 ACTIVIDAD 2.7

Ejercicio 1 

La variable result no coincide con lo que se quiere mostrar por pantalla en el console.log 
result(la variable que se ha creado antes)!=reslt(la variable que se quiere mostrar en el console .log)

Ejercicio 2

En el if los simbolos para comparar la variable no están usados correctamente ya que primero pone el "=" y luego el ">" haciendo que la máquina interprete que ahora la variable edad sea una funcion en un if que se ejecuta ya que el if está por defecto en true y por eso siempre imprime la primera parte del bucle (nunca ejecutara el else).

Ejercicio 3

El fallo en este ejercicio es que la funcion a la que esta llamando la variable total no retorna nada entonces la variable total no tiene ningún valor por eso como vemos en la foto nos devuelde undefined, por lo demás la función funciona correctamente y hace lo que tiene que hacer, se solucionaba simplemente poniendo un return con el resultado.

Ejercicio 4

Lo que ocurre es que como en el ejercicio 1 la variable no coincide con el parametro que usa la función, la función usa el parámetro nombre y el usuario cuando la llama lo pone correctamente saludar("Ana), el problema es que dentro de la funcion se usa una variable que no esta siquiera definida en lugar de usar el nombre que te han pasado como parámetro, se arregla cambiando name por nombre en la función.

Ejercicio 5

El problema en este ejercicio es el bucle for. Si nos fijamos en la imagen de la actividad 5 vemos que la variable i que se usa para recorrer el array de números y que va tomando el valor de cada posicion del array en la última iteración del bucle toma el valor de 4 y si nos fijamos en nuestro array solo hay 3 posiciones ocurriendo asi un problema en la suma de los números y devolviendo la suma un NaN.
Se soluciona saliendo del bucle cuando i toma ese valor y eso lo conseguimos quitando el = en la sentencia del bucle for

Ejercicio 6

El problema que daba es que el if no esta comparando correctamente los valores el = se utiliza para asignar un valor a una variable , para comparar deberia usar el == o el === dependiendo de la comparacion que quiera hacer, en este caso yo usaria el === para solucionar el problema.

Ejercicio 7

Ejercicio 8

Ejercicio 9
