# Clase nº 14 : 01/05/2020

Ejercicio 50 j:

Se tiene que x e y se deben pedir que no sean cero. No sólo 00 sino también 01 o 10. POr lo que se tienen que quitar todo x y todo
y.

Puntos críticos: Hay que hacer derivadas parciales.
	fx = -1/x² + y
	fy = x -1/y²

Los puntos criticos aparecen cuando se iguala a cero. Entonces:
	fx = -1/x² + y	= 0
	fy = x -1/y² 	= 0

	Se despeja de la primera y se encuentra que y=1/x² y se reemplaza en la psegunda:
	fx = -1/x² + y	=> 1 / x²
	fy = x -1/(1/x²)² = 0
	[imagen]

	x(1-x³) = 0
	Las opciones que quedan en 0
	x = 0 (Esta opción hay que descartarla porque queda fuera del dominio, por lo que se dijo al comienzo)
	x = 1 => 1 = 1/1² (se reemplaza en el despeje) por lo que queda x=1 e y=1 [imagen]

	Entonces queda sólo un punto crítico.
	Ahora se hace la derivada segunda en ese punto y luego se le aplica las opciones.

	Calculamos el gesiano (derivadas segundas).
	fx = -1/x² + y
	fy = x -1/y²

	fxx = 2/x³, fxy = 1
	fyy = 2/x³, Fyx = 1

	Gesiano de x,y Queda = 2/x³*2/y³ - 1²

	Evaluamos con los conceptos para evaluar los puntos obtenidos. Los clasificamos.
	Si nos queda positivos hay que ver el signo del primeroel fxx,

	Fxx(1,1) = 2 > 0 entonces se tiene un mínimo local
	[Imagen]

	Geogebra : Ver que sobre los ejes verdes y azules no se grafica la función. Porque no está definido.


Ejercicio 50 g:

	Definir primero el dominio de la función.

	X tienq eue ser > 0, y como y también, entonces queda al primer cuadrante el dominio.

		Fx = 2/x - 4
		Fy = 1/y -1

	Igualamos a cero:

		Fx = 2/x - 4 = 0
		Fy = 1/y -1 = 0

	Despejamos:

		Fx = 2/x - 4 = 0 => x = 1/2
		Fy = 1/y -1  = 0 => y = 1


	El problema acá es que si NO pertenecía al dominio termina acá. En este caso si está dentro del dominio.

	Calculamos el Gesiano:
	fxx = [derivada de x con resecto de nuevo a x]: -2/x²; fxy = 0
	fyy = -1/y²; fyx = 0

	H(1/2,1) = -2/(1/2)² * -1/1² - 0² = 8

	fxx(1/2,1) = 8, por lo que fxx es negativo y el punto es un máximo local.

	Geogebra [imagen] : se ve que en la gráfica de la función hay una punto máximo.
	Puede ser que no haya puntos críticos ( como en los planos, porque todos los punts tangentes son horizontales), por lo que
	hay que siempre obtener el dominio y ver si los puntos obtendios pertenecen al dominio.

# Extremos absolutos

Para definir extremos absolutos, se cambia el concepto de compaar los puntos cerquitas, sino en cualquier punto, en cierta
región. Siempre tiene que estar claro la región en la que se está considerando.
La manera de encontrar extremos absolutos. Hay que analizar los bordes.
Se tiene en cuenta el teroema que nos asegura bajo ciertas condiciones que siempre tienen máximos uy mínimos aboslutos.
	* F = tiene que ser continua
	* Región de la que se liminta: región plana, cerrada y acotada tiene sio o si puntos absolutos. Por ejemplo un disco es
	  una región acotada, pero por ejemplo el primer cuadrante NO ES UN pedazo, es infinito (región no actoada).  Región
	  cerrada: Que incluye los puntos del borde, que incluye los puntos de la fronte.

	Si se cumplen estos puntos, necesariamente f tiene dos puntos máximos absolutos y mínimos absolutos PARA LA REGION.
	Si la función tiene máx y min absoluto, necesariamente lo tiene alcanzarlo dentro del borde o interrior de la región.


# Ejemplo del libro

D: es acotada porque se puede poner en "una caja" y cerrada porque se incluyen dentro los puntos del borde.

Puntos críticos = derivadas. Se iguala a cero y se obtiene el punto crítico. El punto es interior al disco, porque está dentro de
la circunferencia, es candidato a extremo absoluto. NO hay que calcular el gesiano, porque no sirve si es extremo local.
El borde del círculo es cuando es = 9.

Se despeja en x2 y se reemplaza en la función temperatura para poder tener todo en una misma variable. Hay que definir bien el
Dominio. OJO con esto, no puede valer > 3, siempre está delimitado entre -3 y 3.
Se deriva, se iguala a acero y se encuentran los puntos críticos.

Se busca cuánto va a valer y. Y se encuentran dos valores. Esos dos puntos, se ve que cortan a los ejes.
Los valores se evalúan en las funcion temperatura, se evalúan y se ven que se alcanza la más alta en dos puntos. Y la menor en un
punto.

Y otros dos puntos que no pasó nada. ¿Qué pasa en esos dos puntos que no fueron nada, ni máximo ni mínimo?
	Se visualiza que se hacen las curvas de nivel de las gráfica. Se van obteniendo distitnos elipses.
	Cada elipse una pasa por los puntos de extremos absolutos.
	En los 4 puntos del borde, en todos esos 4 puntos se encuentra que hay tangente. Curva de restricción y la curva de
	niveles son tangencia, y eso se utiliza para el metódo de los multiplicadores de Lagrange.

Vuelve a aparecer la regla de la cadena, justificando una demostración. Hay que leerlo.

La conclusión que hay que usar para proponer el método de Lagrange:
	si tengo que buscar extremos de una función continua en dos variables y debo
	Si e un punto de la función alcanza max y min absoluto, la que restrigue y la que hace de nivel, entonces tiene nal misma
	recta tangente. Los gradientes de ambas serán perpendicualr a la curva de nivel de ambas, los gradientes serán a
	multiplos. Se resuemne a qué puntos de la curva, los gradientes que se quiere optimizar y la curva que se restringe,
	entonces se buscan los múltiplos. Esto es bastante fácil.

Se hace un sistema de ecuaciones:
	* Punto pertenezca a la curva
	* Punto cumpla que el gradiente de f y de g sean múltiplos


Ejercicio 53:
	Se debe tener en consideración que b = lamdpa.

	Se Optimiza la función que no está igualada a nada.
	Esta curva xy = 8 Es la restricción. No se busca en todo su dominio, se buscan sobre puntos de esta restricción.

Al ser polinomio entonces se cumplen siempre que hay mínimos y máximos.
	xy = 8 será una hipérbola, pero no es una la que tiene oblicuas, pero es una hipérbola.
	El punto está en el 00. No interesan los focos ni nada de eso.

	En el punto por ejemplo 24 es un punto de la restricción porque es 2*4 = 8.
	Punto 18
	Punto -2-4 (no está el primer cuadrante)
	Punto -4-2 (no está el primer cuadrante)

	[Imagen]: No es una función acotada. No se puede meter en una caja, por lo cual las hipótesis NO SE ESTAN CUMPLIENDO. Por
	lo que no se sabe si tiene máximos y minimos. Si es cerrada.
	Se plantea Lagrange igualmente.


	Se pide que el gradiente en un punto sea = multiplo del gradiente de G
	Y que el punto pertenezca a la curva (que sea xy = 8)

	Gradientes:
		Derivadas parciales:
			f = <2x,8y>

			g = <y, x>

		Sistemas de ecuaciones:
			2x = b*y
			8y = b*y
			x*y = 8 [Imagen]

		Se buscan las soluiciones de ese sistema:
		* Cuando se despeja hay que evitar que se obtenga raíces, no conviene despejar cuando aparece raíz.
		* Si despejar hayq ue dividir por alguna variable, es mejor no hacer eso. X o Y!= 0, y se pierden en algunos
		  puntos si es que ese punto puede llegar a ser un candidato. Es mejor restar y hacer factor común.
		* Si hay que dividir, mejor que sea por una constante.

		De la primera se despeja x:
			x = b*y/2
			8y= b*(bY/2)
			[imagen]
			16y= b²Y [No hay que dividir en y, por lo que estaría mal, para evitar que quizás por algo que sea cero]

			Entonces lo que se hace es restar.
			0 = b²y - 16y
			0 = y(x²-16)
			[imagen]

			* y = 0:
				x*0 = 8 (en la última de las funciones del sistema) por lo que no es posible.
				Hay un absudro, por lo que por este camino no se llega a nda.

			* b² = 16
				- b = 4:
					(2x = 4*y)
					x = 2y (x va a valer el doble que y).
					(reemplazamos en la 3ra)
					(2y)y = 8
					Y² = 4
					Y = +2 o -2

					4,2 y (-4,-2)

					En ambas puntos da 32, que es una elipse que pasa por estos dos puntos. Es simétrica a los
					ejes. Y en esos dos puntos resulta hay tangencia.
					Es una sola elipse que pasa por los mismos puntos.


				- b = -4:
					x= -2y
					-2y*y = 8
					y² = -4	[ABSURDO. POr lo que no va ninguna cosa posible]


			En los dos puntos devolvió 32, entonces ¿hay máximos o mínimos absolutos? ¿Qué hay?

	Geogebra[imagen] Ver que en el punto 42 y -4-2, es donde tocan a la función.
	Siempre es de 32 para arriba, porque no hay mínimo ni máximo por el valor 32. Hay que graficarlo, porque a partir de 32
	siempre los puntos que se intersectan siempre son más grandes a 32, por eso se dice que es un mínimo.

	La restricción por no ser acotada, pudo tener extremos locales.
	Alcanza mínmo absoluto pero NO alcanza máximo absoluto. Tiene que ver con la condición de curva acotada.

# Tarea:
	Ejercicio del 53 a 57.

	Distancia minima a una hipérbola, y no es acotada por lo que pasó en el 53.
	Distnancia en el espacio, en vez de tener 3 ecuaicones tiene 4 ecuaciones por lo que se obtienen 4 variabels.

	57: Punto más cercano, se había hecho de una forma, pero ahora se plantea CON OTRO forma. Es una esfera.
	Cuando se pase por la esfera, entonces lo que se obtienen a través de ella entonces se tienen dos puntos.

	Conviene hacer el gráfico, tanto de restricción como los graficos de nivel.

