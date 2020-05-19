# Clase 9 : 11/05/2020

Está más relacionado a Matemática I.
Funciones de más una varaible, se van a tener varias variables dependientes y siempre una sola será la dependiente.
Funciónd e varias variables, lo que hace es tomar un valor que es el dependiente y devuelve UN solo número, no muchos ni tampoco
vectores, etc.

Lo que hace es devolverme un número, podría ser una función que calcula el volumen de un cilindro. Para eso se necesitan tres
valores: radio y altura. La función devuelve un número: que es una constante, que es el volumen.

Función de dos varaibles, lo que se obtiene un conjunto de R2. Como en el ejemplo de la página 52. Si es una función de 3
variables, entonces es de R3. Se buscan condiciones que se aplican a X y a Y, no sólo a x. Lo que aparecen son condiciones que
RELACIONAN a X e Y.

Curvas de nivel sirve para graficar: cuando son de dos variables, aparecen 3 variables, x y z. z es el resultado de evaluar la
función en x e y. Por eso aparece z.

Ejercicio 34a.
-------------
	Condicinoes que se debe pedir:
		- Denominador que no sea cero (porque no se puede dividir por cero), es decir que ln(y) != 0.
			Logaritmo 1 = 0. y != 1.
		- x - y > a 0. ya que no peude ser raíz de negativo. => x - y ; x = y.
		- Logaritmo sólo y > 0 (el argumento debe ser mayor a cero).

		Dominio de f(x,y): Se le ponen todas las condiciones escritas anteriormente en la definición del dominio
			dom(f) = {(x,y) E R2, y>0, y != 1, x >= y}

		[Imagen en Geogebra] : ver que lo que está doblemente pintado es el dominio de la función.

		Se delimita las bordes del domino. Muchas veces aparecen las curvas cónicas (porque por ejemplo en el ejercicio
		donde se presentan el dominio dentro de la curva parábola).
		NO dar como respuesta a intervalos numéricos, porque las respuestas se tienen que dar basados en las variables x e
		y.


Ejercicio 34c.
-------------
	Tiene condicionado a 3 dominios. Hay que evaluar qué dominio (dando 3 valores) es el que corresponde a la función.

Ejercicio 35:
-------------
	a) es un plano con superficies de nivel todas rectas paralelas, la superficie que contiene todas las rectas es la
	superficie z = -2y
	Gráfica al estar elevada todos a la uno, va a ser plano. z = f(x,y) por lo que se lee:
		z = 6 -x -2y => 6 = -z -x -2y.

	d) superficie no va a ser una cuádrica.
		dominio x2 + y2 != -1 (suma de positivos por lo que nunca será -1). El dominio será todo R2, es decir que se puede
		evaluar en cualquier punto.

		Curvas de nivel:
			func{6}{\sqrt{x²+y²+1}} = k ¿Cómo tiene que ser K? k>0

				Se acomoda la función para que saber la superficie cónica que se encontrará como curva de nivel
				(que será un círculo) El radio va cambiando cuando k cambia.
				K tendrá que ser >= 6 porque se condiciona el radio.
				[Imagen]

			Las curvas de nivel se deben hacer en el plano, sin z.


Ejercicio 36:
------------
	Superficie de nivel: es la superfice que aparece luego de igualar una función de 3 variables igualadas a una
	constante. No se podría hacer el gráfico porque debería de ser en R4.
	Igual la K a los valores que dice el libro.


## Segunda parte

Definición de continuidad es lo mismo que para una variable. Se dice que un punto a,b hay continuidad cuando:
	- Se puede evaluar,
	- Cuando existe el límite
	- Cuando los dos valores coinciden.

Continuas en su dominio.

Evaluar el límite es ver lo que sucede con la función al acercarse al punto y NO lo que sucede EN EL punto.
Cuando hay indeterminación, hay que tratar de salvarla.

La más difícil es acercarse por "Caminos":

	- Es cuando no se puede salvar la indeterminación.
	- En el plano, se acercaba por dos lados, por izquierda y por derecha. Ahora no se puede, ya que son infinitos los puntos,
	  infinitos caminos, se pueden acercar cualquier curva que pase por el punto. La dificultad estriba en que no se pueden
	  abarcar todas las posibilidades existentes. ¿Qué se hace?
	  	* Una opción es proponer un camino particular (que pase por el punto que se quiera) que pase, y ver qué pasa con
		  esa curva por ese punto. Si puede escribir la curva evaluado en el punto, entonces se puede utilizar esta
		  función mediante la curva.

En el ejemplo se ve que se modifica la Y por X, se trata de ver de lo que se trata cuando se acerca por ese camino, por la recta
Y=X. Cuando se acerca, tiende a 2. Ahora lo que se hace es buscar por otro camino, si NO se acerca a 2, entonces se puede decir
que no existe. Acá si es concluyente, dos caminos son distintos entonces listo, TERMINO.

El problema es que si se eligen varias curvas que cumplen con el mismo resultado, eso NO significa que sea concluyente (está en el
manual). En estos casos lo que se hace es establecer un radio al rededor del punto, y acercarse por TODOS Los puntos disminuyendo
el radio [Se denomina COORDENADAS POLARES], lo que da con polares, ya es CONCLUYENTE.
¿Por qué no se arranca con polares? Se deja para el final porque si el límite no existe, es más fácil encontrarlo mediante por
curvas (por caminos).
	En este caso la continuidad es IMPOSIBLE de salvar.

Cuando se hace Polares, la idea es acercarse a un punto cuyo centro del circulo TIENE QUE SER el centro el punto anterior.
	Si el punto al que se quiere acercar NO es 0,0 hay que sumar estas coordenadas, a la parametrización
		x = r.cos(o) + [coordenadaX]
		y = r.sen(o) + [coordenadaY]

	Si el punto por el que se quiere pasar es: 1,2 entonces:
		x = r.cos(o) + [1]
		y = r.sen(o) + [2]


1) Se tiene que hacer caminos
2) Luego utilizar polares.

# Tarea:
	- Terminar con límites (hasta ejercicio 38).
