# Clase nº 8 07/05/2020

Ejercicio 31)
	b) La pregunta apunta a indicar que al momento de pasar por ese punto si el móvil está moviéndose en horizontal o vertical
	Igualamos una de las dos componentes en X = 0, porque sino no sería horizontal, ha que buscar que sea horizontal.

	Igual a cero a las dos componente, se busca cuando está detenido el móvil. Sería un punto donde se detuvo.

	r' = 3t² -12t + 9; 4t-8

	Velocidad horizontal cuando r' tiene la segunda componente igual a 0.
		4t-8 = 0 -> t = 2.
		En el instante 2 se tiene una velocidad horizontal. ¿En qué posición? Se tiene que reemplazar t=2 en la primera
		función. Si se reemplaza da <0,-1>

	Velocidad vertical cuando r' tiene la primera componente igual a 0.
		3t²-12t = 0 (hay que utilizar Baskara)
			- t = 3
			- t = 1

	Se puede ver que las posiciones dan vectores de velocidad, y eso indica cómo va pasando de un lugar a otro el móvil.


	La profesora armó en Geogebra una tabla de excel donde tiene todas las variables [imagen]

	c) Si el móvil pasó por el punto (0,5) se pone en la función a la original. Se tiene que igual uno en 0 y en la otra en 5.
	Y tratar de encontrar el t.

	t³-6t²+9t-2 = 0
	2t²-8t+7 = 5 --> se despeja de acá y da:

	Para usar Bascara se tiene que tener igualado a cero,para eso se tiene que restar el cinco (en algún lugar) [imagen]
	Todavía hay que reemplazar los valores en la primer ecuación.

	Se hace Ruffini no sé para qué, pero queda como (t-2)(t²-4t+1) = 0
	El último término anterior, está multiplicado por 2 e igualado a cero (2t²-8t+2=0)

		Pasó dos veces en el punto, en:
					- 2 + \sqrt{3}
					- 2 -\sqrt{3}
	[imagen de Geogebra hecha con el movimiento]


# Longitud de arco

	Tenemos que saber el valor de t final e inicial
	Lo que se debe hacer es calcular al módulo de r' (en el caso más general aparecerá algo que dependa de t). En el general
	toda la expresión queda dependiendo de t,por lo que la integral queda más complicado.
	Siempre va a aparecer la raíz, por lo que se va a tener que achicar lo que está dentro de la raíz, poder simplificar el
	argumento de la raíz.

	Todos los ejercicios están hechos para poder simplificar todos los argumentos de la raíz y la raíz desaparece.

	Para el ejercicio de la catenaria, está más complicado,hay que ver los videos que están subidos en el campus.

	Ejemplo que se quiere resolver es un ejercicio de parcial  [imagen]

	a) verificar que camina sobre una recta sobre una ecuación.
		Las expresiones que corresponden a la posición son cuadráticas. Ya me dicen la ecuación cartesian a de la curva.
		¿Cómo se hace para verificar?
		Evalúo con cero y se obtiene 1,8, entonces se puede ingresar en la recta y se ve que da 11 (esto no está bien
		porque se prueba que pasa por determinado punto, no significa que haya caminado por la recta de esa ecuación).

		Se reemplaza en la ecuación de la recta, la x con el primer componente y la y con la segunda componente del plano
		posición
		[varias imagen]

	b) ¿en qué momento pasa 4,-1? Se tiene que buscar que la primera ecuación de la expresión r sea = 4 y que la segunda sea
	=0. [imagen]
	Dando t = 1 y 3, pasa por el punto 4 y -1, porque los valores están dentro del intervalo de 0 y 4.

	¿Cuál es su velocidad? Hay que derivar y evaluarlo en los instantes que pide (1 y 3)[imagen]
	Los vectores son opuestos (2,-6) y (-2,6) pasó con una velocidad para un lado y luego con una velocidad contraria por la
	recta.

	c) Rapidez es el módulo de la rapidez. Si pasó dos veces por un mismo lugar Y ES UNA RECTA entonces tuvo que detenerse
	para volver sobre sus pasos. Se tiene que reemplazar en sus coordenadas de velocidad e igualarlas a ambas a cero, dando un
	t que nos dé AL MISMO TIEMPO cero.

	[Imagen en geogebra]

	Se calcula el módulo de r': \sqrt{4-2)^2+(6t-12)²}
		Lo que se quiere hacer es sacar cuadrados para poder simplificar el argumento de lo que hay dentro de la raíz.
		Queda el factor común de (t-2)²
		Recordar que la raíz de t-2 tiene que quedar positivo [imagen]

		|t-2| es una función a trozos, porque cuando t > 2 entonces es t-2, cuando es t<2 entonces será -t+2  : ya que como es
		un módulo, tiene que ser SIEMPRE positivo. Por eso en la integral tiene dos partes.
		Queremos sacar el recorrido, pero todos los puntos de la recta se pasan dos veces,por lo qe se integra una vez y
		luego se multiplica por dos.

		Distancia total recorrida \sqrt{40}*4
		También se puede hacer el recorrido de la distancia entre el punto final y del comienzo y da 12.64 (eso sólo es de
		ida y se tiene que multiplicar por 2 para toda la distancia recorrida).
		[imagen]

	Ejercicio 23)
		b) para saber desde donde hasta dónde integrar, se deben igualar las Componentes de la posición (2,1,0) dentro
		de las paramétricas en x, y, y z para que me de eso. Da t=0.
		El tema es el siguiente punto (11, -5, 18). t= 3
			Por lo tanto hay que integrar entre 0 y 3

		Dato, la integral va a quedar como algo parecido a un desarrollo de un cuadrado de un binomio.


# Trabajo práctico.
	Vector tangente en cada punto será a la curva,pero en diferentes puntos.
	No se grafica en el 0,0, sino en el punto de la curva. Veer que está graficado desde el punto 1 en el ejemplo del manual
	de Matemática.
	3cos(t) -3 sen
	-3sen	-3cos
	Vector vertical, 0 en y.
	-3,1
	0,3 es el resultado.

	Centro en 0,1, radio 3.
		t=pi, se estaría en -3, 1 (del centro 3 unidades a la izquierda).

	Para ver para dónde va la circunferencia, hay que especificar el vector de velocidad, que señala para dónde va.

