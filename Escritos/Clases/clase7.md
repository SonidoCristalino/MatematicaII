# Clase nº 7 : 04/05/2020

!!!Este tipo de ejercicios NO son de parcial!!!

	Eje de simetría el eje Y
	Hay que especificar el centro (ver la forma de la ecuación como para saber más o menos cómo es).
		[Imagenes]
		Diámetro 42 es la parte más chica
		La base es de 70 m
		Altura 55.

		Eje de simetría en Z.
		La circunferencia debe variar entre 42 y 70.
		Centro el hiperboloide: 0,0,55 (55 por la altura). (z-55)^2
		Ecuación canonica nos obliga a saber a^2, b^2, c^2.
		Trazas cortando con z = k dan circunferencias.
		a = b, porque las trazas dan circunferencias ¿?
		[Imagenes de la fórmula]

		Trazas horizontales a y b son lo mismo por lo que b = a y queda a y c como incógnitas.
		z = 0 para la traza
		a = radio = 21.

		¿de qué diámetro queda la parte superior? Traza = 85, es decir z=85
		Ecuación de elipse, a y b son los semiejes.
		Diametro es el doble de 25,96 = 52m

		Lo importante son las intersecciones entre los planos que se generan las trazas.

# Fuciones vectoriales:

Lo importante es ver cómo se relacionan entre ambas funciones, no verlas por separado.
No se puede saber si es una parábola, unir los puntos no es tan definitorio. No alcanza con tener puntitos sueltos, por lo que se
hace es desaparecer el parámetro. Se relacionan las funciones acomodándolas.
Se desparametrizan las funciones.
Se despeja de t de la segunda (como está en el libro) y se vuelve a relacionar con la primera. Y ahí si queda una parábola cuando
se termina despejando.

El hecho que aparece t² en alguna de las expresiones NO quiere decir que sea una parábola desde el comienzo, la idea es ver cómo
queda luego del despeje. Ver bien dónde está el vertice según viendo la ecuación.

Aparece una curva con un sentido recorrido, y eso lo da sabiendo cómo aparecen los números a medida que aumenta t, los puntos se
van desplazando cada vez más arriba. T-1 es una función creciente, cuanto más auemte t, más aumenta i.

## Movimiento en el espacio

Función cuyo variable independiente es el parámtro t y lo que devuelve es un vector cuyas componentes son las coordendas de las
funciones. Sirven para estudiar el movimiento de un móvil, partícula, etc. t podría ser una variable que simbolice el tiempo.

Lo que se hace es hacerle a la función vectorial aplicarle la derivada. Para calcular la velocidad, se plantea la derivada.

### Ejemplo

t = 0, punto 1, -1.
El sentido es hacia arriba, a partir de t = 0, se tiene un pedazo de parábola, (el tiempo no puede ser negativo).
Notación de vectores se hace con < >, NO se usan paréntesis, porque se indican puntos así.

Lo que interesa es cómo calcular la velocidad, se hace con la derivada: <2t + 2, 1>
t = 1, la velocidad porque indica dirección, sentido. Si se agrega el vector <4,0> entonces es tangente a la curva en dicho punto.
Si se hubiera hecho en otro punto, se hace tambien tangente a la curva, pero en ese punto calculado.

Si se tiene una función posición, se deriva se obtiene la velocidad. Para distintas posiciones, se obtienen distintas velocidades.

### Otro ejemplo
Se tiene que saber qué herramienta aplicar. Ver que se hace arcosen(t) para poder despejar cos(t)
	Identidad fundamental: sen²(t)+cos²(t) = 1 siempre se cumple

	Ecuación tiene una forma de circunferencia x²+(y-1)² = 1
	La mejor opción en este caso, es aprovechar siempre la identidad fundamental, en vez de sacar el parámetro.

	t = comienza en 0 y finaliza en 2pi (entonces da toda una vuelta).
	Para saber el sentido, se puede calcular la velocidad cuando es pi. El sentido de recorrido se puede saber calculcando su
	velocidad en un punto de posición.

	A partir del punto (0,0) se mueve <-1,0>. Este vector como apunta a la izquierda, es lógico que el sentido de recorrido
	sea el sentido horario. Si el vector hubiese aparecido hacia la derecha, entonces el sentido sería inverso.


# Ejercicios

b en el espacio

Eliminar el parámetro y graficar la curva. Indicar el sentido de recorrido, pnto inicial y ver el final y se puede ver el
recorrido.

28. b) conviene ver sobre qué superfice está apoyada, y a partir de ahí ver qué forma tiene.

29. Se tiene una función de posición. Es una función particular.

30. Se encuentra una ecuación cartesiana, y hay que armar la parametrización. Aparece una elipse, el centro en el punto -1, 2.
    Pero no es una elipse completa, de 1,2, hasta -1,3. Son 3/4 de la elipse (recorrido en sentido horario).
    En a. se tiene una expresión para x e y, si se eleva, y se despeja se llega a la ecuación.

	-1 y 2 son las coordenadas del centro.

	2 y -1 ver que se convierten en 4 de la función que está diviendo (x+1)².

	Hay que encontrar un valor que de el punto inicial y otro valor para encontrar el punto final, que sería encontrar el
	punto t.

	Cambiar el signo a cos o sen, modifica el sentido de dónde tiene que ir.
	Tienen que ser el mismo argumento de las dos fórmulas, si en una es cos(t) el otro debe ser sen(t) del mismo argumento.

31. No se pueda eliminar el parámetro, tampoco se encuentra una parábola ni elipse, ni nada estudiado. Las preguntan apuntan a
    algo. Se puede dar un buen gráfico igualmente.

# Tarea

28 al 30


Con el 28. a se tienen que tener dos funciones, porque una sola es una superficie por lo que se tiene que entender


29. Hay que utilizar la identidad. En la función, cuando se reemplaza con y, NO con y².
	Quedaría = x²+y = 1 (es una parábola).
	Cuando querramos parametrizar se utilizará cos y sen de t.
	Inicial: (1,0)
	Final: (1,0)
		Es una parábola, según los puntos parece que empizan sobre el mismo lugar.
	c) (0,0)
		derivada de sen² sería:  2xsen(t) x cos(pi)
		r' en PI se queda en 0,0, y además t = pi, cos8

	¿Qué significa toda esta mierda? Velocidad 0,0 significa que se detuvo, el recorrido será un pedazo de parabola,
	que luego va a ir recorriendo entre -1,0, se detiene y luego vuelve.
	Tiene que ver con cómo se parametrizó, esas expresiones si estan limitadas, el coseno nunca escapará de -1 y 1,
	por más que la parábola salga de ese intervalo, se limita con sen y cos, que son funciones "redundantes".
	Se detiene y vuelve.
	d) 0,1 vértice de la parábola, punto medio, es la mitad. Cuántas veces pasa por ese punto, pasa 2 veces porque va la
	primera y vuelve a pasar la segunda.
	[Imagen geogebra]



30. 	Lo que dice la profesora es que se tiene que ir tanteando,
	a) Entre 0 y 3/2 de pi.  Cuando t vale cero se obtiene el punto inicial
	b) Tiene que ser la misma elipse, entonces qué se puede poner para y, entonces debe ser como -cos(t), se tira 2-cos(t), si
	se le cambia el signo a uno solo, lo que se hace es invertir la dirección.

	se pone pi/2 y 2pi como primer intento [imagen] pero da mal.

	Lo que se hace es -1+2cos(t) e y=2+cos(t)
		pi/2 y 2pi

	Tira una idea de cómo poder encararlo  [Imagen]
	Cuadrado es distributivo con respecto la distribución (hay que tenerlo presente para la expresión ).
		sen²+cos² = 1
	entonces se pide:
		(x+1)/2 = cos(t)
			x = -1+2cos(t)
		y-2 = sen(t)
			y = 2 + sen(t)

	(-sen(t))² = sen²(t)
		Por eso es que le da

	-1 y 2 NO se pueden modificar porque son el centro de la vuelta en el gráfico.
