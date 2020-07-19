# Clase nº 23: 06/07/2020

## Novedades:
Entrega del tp que falta es el jueves 16, de la semana que viene. Desde este jueves 9/07 va a estar habilitado.
Jueves 16/07 se terminan con las entregas obligatorias.

Ese día terminaría ya terminarían todos. Los que deban algo, podrán entregar algo en las dos semanas que vienen.
	* Semana del 20 Se trabajan con los primeros 4 TP. Se tiene tiempo hasta el viernes 24.
	* Semana del 27 se trabajan los otros 4 TP.

En Julio NO hay mesa de Matemática II. La próxima mesa será en Diciembre.

## Sobre el TP nº 7:
TP nº 7 es más corto, tiene un sólo ejercicio. Estará subido el jueves (como el jueves es feriado) recién el lunes que viene se
tiene la última clase.
Va a ser una matriz de 3X3 puede tener hasta 3 autovalores. Resolver una cúbica. Arranca parecido al ejercicio nº 37.
Saber usar bien la definición.

### Ejercicio nº 37:
	Si se hace A * W = tiene que dar un resultado ES un multiplo del vector W. Terminar de diagonalizar a A.
	Si es W autovector, entonces los otros dos de A, entonces se puede bajar el número del polinomio (recordar que va a ser
	HASTA 3).

# Apunte nº 7
Hoy se ve sobre Independencia Lineal, lo que significa y etc.

Vectores linealmente independiente.
Independencia, es lo que nos interesa. Muchas propiedades, porque cuando se definen un espacio vectorial, no sólo es un conjunto,
sino que va de la mano con las operaciones de la suma, y cómo se multiplica por esa constante. Esas dos operaciones deben estar
bien definidas.
Propiedades que se enuncian, se pueden separar en dos grupos:
	- A qué cosas deben cumplir la suma (cerrada, conmutativa, opuesto, neutro, etc)
	- Cuando se multiplica un número real( distributiva, asociativa, neutro, etc)

Espacios ya vistos:
	- vectorial: R2, R3
	- Matrices: tambien es un espcaio vectorial, porque la forma que tiene la suma y la resta están definidas iguales que en
	  los espacios vectoriales.

Ver cuándo es linealemente dependiente e independiente.

	Definición: Sean 1 2 , ,..., n v v v , n elementos de un espacio vectorial V. Se dice que estos elementos son linealmente
	dependientes si existen n escalares 1 2 , ,..., n c c c  no todos nulos tales que :...

Difícil de entender, traducido:
	Se tienen 2 vectores y uno era multiplo del otro, eso es escribir a uno como el múltiplo de otro, lo que signifca es que
	son linealmente dependientes. Se puede escribir una combinación en relación al otro.

En el ejemplo de la página 45, se ve que son dependiente. NO son cero para los dos (ya que cero por otro cero, da el nulo).
El 2 y el 1 de los ejemplos efectivamente da como resultado un cero.

Cuando NO SON múltiplos, lo que hay que es un sistema de ecuaciones.
Rango de matriz y la ampliada es 2. ¿Cuál es la solución? 00. La única solución es que los coeficientes sean cero, son
INDEPENDIENTES (cuando la única solución es que los coeficientes obtenidos son los nulos, entonces significa que son
independientes) Como en el primer ejemplo de la página nº 46.

Puede pasar que haya uno de los vectores sea combinación de los otros dos, por lo que no es tan evidente. Para decidir en estos
sistemas más complicados, se arma un sistema de ecuaciones, y se traduce a una matriz ampliada. Se escalona, y se llega a un
sistema con infinitas soluciones. Lo que marca esto es que el segundo es la suma del primero mas el tercero dividido dos.
Por lo tanto estos 3 vectores están contenidos en el MISMO plano.

Lo importante es que en cada uno de estos ejemplos, para determinar si son dependiente o independiente, el método es formar un
sistema de ecuaciones, y ver qué da.

Lo que dice el *Teorema*:
	- Cuando el rango da la misma que el número de incógnitas, entonces son linealmente independientes.
	- Si son infinitas las soluciones, (la trivial no es la única) por lo que serán las matrices son dependientes.

# Base de un espacio vectorial
Conjunto para ser base, deben ser independientes y que con ese conjunto, poder formar cualquier espacio vectorial [ejemplo en
página nº 48].  Con esos dos vectores nos alcanza para poder formar cualquier otro espacio vectorial en R2.
Con dos elementos al ser R2 me es suficiente para formar el espacio.

En R3 es más complicado. Con dos vectores sólo se puede generar el plano, si se quiere salir de este, entonces no se puede. Con
dos vectores no se puede expresar R3, sino con 3 elementos.

*Definición*: Si el espacio vectorial V tiene una base con un número finito de elementos, entonces la dimensión de V es el número de
elementos en cualquiera de sus bases, y se nota dim( ) V . Si V es el espacio nulo, su dimensión es 0

# Autovectores y autovalores (de una matriz)

## Autovalores
	Dada una matriz cuadrada, encontrar sus autovalores y autovectores para llevarla a una forma diagonal (para que quede más
	sencilla). Se usa en Mate III para diferenciales: Los autovalores y autovectores tienen aplicaciones en la resolución de
	sistemas de ecuaciones diferenciales lineales; en modelos de crecimiento poblacional; en la rotación de cónicas y
	cuádricas cuando estas tienen ejes de simetría que no son los ejes coordenados, etc

	Autovector para matrices CUADRADAS nomás y autovalor para una constante.

	Lo que se le pide al sistema es que tenga más que la solución trivial, es decir que tenga soluciones infinitas. ¿Cómo se
	asegura?  Se tiene que cumplir que el Rango de la Matriz de Coeficientes debe ser igual al Rango de la Ampliada pero MENOR
	a las incógnitas del sistema.

	Se hace el ejemplo de la página nº 53.

	Si la matriz es de 2X2 lambda aparecerá en los elementos de la matriz. Puede tener hasta dos autovalores.  Cuando es más
	grande, aparece en otros lados lambda, por lo que el determinante dará tantas soluciones como los valores de n. El grado
	del polinomio será igual al tamaño de la matriz; en una matriz de 5X5, tendrá HASTA 5 autovalores; de 3X3 HASTA 3
	autovalores, etc.

	El video que se subirá da resolución al TP.

	El autovalor PUEDE ser cero, lo que NO DEBE DAR CERO es el autovector.

## Autovector
	Qué vector de dos componentes, cumple con A*V = -1*V. El autovector NO puede ser un vector NULO.

	Para poder constatar con el resultado, lo que se hace es multiplicar la matriz original con el autovector, dando un
	MULTIPLO del autovector.

	Diagnoalizable cuando es semejante a una matriz diagonal

	Una matriz NxN es diagonalizable si y sólo si tiene n autovectores linealmente independientes. La matriz diagonal
	semejante a A tiene en su diagonal a los autovalores de A.

### Para Diagonalizar una matriz, se busca:
------------------------------------------
Lo bueno es que cada uno de los pasos se puede verificar con el siguiente. Para Diagonalizar se hacen en general, estos pasos:
	- Encontrar sus Autovalores.
	- Encontrar sus Autovectores (hay que fijarse si son independientes junto con los autovalores). Todos deben dar infinitas
	  soluciones, de forma contraria, está mal los autovalores.
	- Armar una matriz C, en las columnas deben aparecer los autovalores.
	- Se le busca la inversa a C.
	- C^-1* A * C = Se da una matriz diagonal.

# Tarea:
	- Realizar los Ejercicios nº 37, 38 y 39. Tener el apunte a mano para encontrar las definiciones.

# Archivos:
	- Ejemplo1: El tema que tiene es que las dos raíces encontradas (lambda = 2) es el mismo número (2), por lo tanto los dos
	  autovectores que se proveen pueden llegar a ser generadores [1 0] [0 1].  Pero es un ejemplo raro, además es de 2X2 por
	  lo que es bastante tonto.

