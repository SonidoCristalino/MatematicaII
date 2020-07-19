# Clase nº 17 : 11/02/2020


# Ejercicio nº 8:
	## D:
	* La integral doble también sirven para calcular regiones planas, y no solo volumen. Para ello la Integral debería de ser
	  la constante 1.
	[No sé qué dijo]

	Límites son la curva y = log x, y = 0, x = e. [Imagen]

	- X = e, es una recta vertical, e es la base exponencial.
	- Y = logX, se sabe que tiene que ser x = positivos, cuando x = 1, entonces y = 0. Puntos interesantes en Log, sería 1, 2,
	  E (que será y = 1)
	La región señalada en la imagen es la que hay que calcular. Hay que calcular el área, para esto se va a poder hacer,
	mediante la siguiente función: SS 1 da

	IMPORTANTE: Habría que ver al ser área ver el posible resultado de la área, teniendo la escala, y los puntos, podría
	aproximarse a ojo lo que nos pueda quedar para cuando obtengamos el resultado que no sea cualquier cosa. Por lo que se
	hace es hacer un triángulo en esa área, para que al calcularla, poder decir que nos da APROXIMADO al triángulo. A >
	(E-1)/2 > aprox 0,8.

	Para ello se debe definir R (que son los límites de integración):
		- 1 <= x <= e
		- 0 <= y <= logX
	¿Es la única manera? ¿o es posible hacerlo con y entre constantes?
		- 0 <= y <= 1
		- e^y <= y <= e
		Y = si se recorre de izquierda a derecha, se entra por un punto en una curva de y = logx, y del otro lado, se sale por la
		recta de E, es decir X= e^y

	Si utilizamos la primera Región, entonces quedaría:
		S entre 1 y e,S entre 0 a logX d dydx

		El problema es que la integración entre 1 y e de logx hay que hacer por partes, para llegar a la primitiva. Se
		puede hacer, pero es MEJOR AVERIGUAR si queda mejor realizarla con la otra R.
		Es decir:
			- 0 <= y <= 1
			- e^y <= y <= e
		S entre 0 y 1,S entre e^x a e 1 dxdy: [Imagen]

		Queda más fácil, porque no se hace por partes, por lo que es útil describir de las dos maneras, es más fácil cómo
		poder calcular al área.

	## C:
	y = 2x,x = 2y, y = 2/x (primer cuadrante) [Imagen]

	Cuando X se va acercando a X, la Y se va a haciendo infinito. Cuando X es más grande, entonces Y se vuelve más chico
	(inversamente proporcional). Los puntos se pueden dar los mismo que las otras dos rectas.
	Con esos tres puntos, se puede dar el área. El tema es cómo describir la región. R:
		- 0 <= x <= 1
		- X/2 <= y <= 2X
		U
		- 1 <= x <= 2
		- X/2 <= y <= 2/x

		El problema, es que no se mantiene el mismo techo, por un lado es una recta y a veces es la hipérbola, y eso es
		un problema, por lo que la región hay que hacerla por separado, es hacerla por sub-regiones. Si se evalúa por X
		(se hace de abajo hacia arriba), no se mantiene el techo.
		Y el mismo problema da cuando se hace de un Y (de izquierda a derecha) se mantiene la pared izquierda, pero no la
		derecha.

		El corte se describirá como una unión en dos regiones, cortada por X = 1.

	Lo que se van a tener que hacer dos doble integrales.
	[Ver imagen la solución del área]

	Lo que se hace es obtener un aproximada del área del triángulo.

	Luego no es difícil hacer la solución.

# Dos videos para ver:
	- Sobre integral triple: es largo y lo que se hizo es tomar el sólido que se hizo en Geogebra, de 5 superficies. Calcular
	  el volumen de una integral doble, y que también el triple se puede hacer.
	  El tema es que se proyecta sobre otros planos, no sólo sobre XY.

# Cambios de variable:
	- La idea es cuando se tienen una doble que es difícil de resolver, NO se cambian el orden de ordenación, sino lo que se
	  hace es una cosa como "la sustitución" en las derivadas.
	  Siempre es interesante el cambio por sus coordenadas polares, angulo y radio.

	Coordenadas cartesianas X e Y, son las coordenadas donde está posicionado un punto. Relacionados en la Distancia que tiene
	un punto para llegar a los ejes.
	La otra manera es coordenadas polares, también describe donde está un punto. A qué distancia está del origen y con qué
	ángulo se intersecta.

	X e Y pueden ser negativos, por lo que el coseno y el seno también pueden ser negativos. Serán entre 0 y 1.
	Si ya se saben r y tita, entonces también se pueden saber el punto de X e Y.
	Y/X = tangente(tita)

	¿Cómo se pasa de un sistema de coordenadas a otro? Bueno, con la ecuación que está sobre el final de la página 11.
	Ojo que la calculadora NO siempre pasa al angulo que estamos buscando ¿Cómo hacer entonces? Bueno, está sobre el final de
	la página 12.

	Luego se reemplaza y por sen(tita) y x por cos(tita)

	Las circunferencias que no pasan por el origen, se mantienen una relación entre r y tita. Es un poco más complicada pero
	bueno, se puede saber.

Lo que nos interesa es cómo mejorar la integración con coordenadas polares.

## Ejercitación de la profesora:
Supongamos que la región G en el plano uv  se transforma por medio de las funciones continuas... [página 14]
Hay que tener en cuenta el jacobiano de coordenadas, siempre será el mismo, es un factor que relaciona las derivadas de las
variables originales respecto de u y v. Es como la adaptación cuando se hace sustitución.

	El jacobiano es un r... ¡siempre hay que utilizarlo!

## Ejercicio 9:
	Para graficar los elementos que se deben conocer son:
		z² = x² + y²
		0 = x² + y² - z²
		Es un cono porque queda todo igualado a 0, pero es un semicono superior,es el lo de los z positivos.
		Eje Z eje de simetría.

		z = 2 - x² - y² paraboloide. Las dos aparecen restando (con el mismo signo) por lo que sea elíptico, es decir que
		va hacia abajo, el eje es z, porque no está elevado al cuadrado. El punto más alto será el 002
		Las dos superficies se cruzan en una circunferencia [imagen]

		Va a quedar como un trompo.  Volumen será un volumen.

		En Z se pone un menos para que quede lo de adentro todo positivo.
		Los valores que saca la profesora son para Z =1 o -2. ¿Sirven los dos resultados? No, porque sólo me interesan los
		positivos -2 está fuera está por fuera del volumen.
		El -2 es porque también si el cono continua para abajo, se vuelve a tocar con el paraboloide,  pero en -2.

		La sombra en XY es un circulo de radio 1 centrado en el 00. ¿Cómo se hace para volcar esto en la región?
		Si se quiere describir:
			R:
			- -1 <= x <= 1
			- <= y <=

		-1 y 1 para y no puede ser, porque sino sería un rectángulo. Entonces se debe reescribir como
			x² + y² => y = +- \sqrt{1-x²}

		Quedó una región media complicada. La diferencia es difícil integrar, la raiz es difícil para integrarla. No es
		conveniente por lo que se hace con coordenas polares (con cambio de variables)

		X se movería entre 0 y 1 y el ángulo tita se movería en 60º (el ángulo se mueve entre 0 y 2pi, se usan radianes)
		La descripción queda más fácil porque se mueve entre enteros EN RADIANES.


	r = es el jacobiano de la función:
		5/6pi = es el volumen del solido que está delimitado entre un semicono y una parábola.

# Lo que hay que hacer:
	- Queda completar la tabla de traducción
	- Cardioide: todos los puntos cumplen que si se calcula el radio, siempre sale hacer 1 - sen(angulo del centro).
		En Geogebra funciona escribiendo el jacobiano (r) como se puede ver en las capturas de pantalla.
	- Ejercicio 9 del 12. Se termina con todo integral doble.

### Sobre el TP se realiza:
	- Áreas de dos regiones, sin polares.
	- 1 integral doble.
	- 1 integral triple.
		* Quizás en alguna haya que cambiar a polares.
		* Hay que graficar en todas.

