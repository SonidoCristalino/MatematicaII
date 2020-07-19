# Clase nº 16 : 08/06

Hay como un corte en la materia. Así que veremos cómo va.

Se van a calcular superficies de sólidos cualquiera. Va a estar limitado originalmente en el espacio por el plano del piso Z=0,
paredes verticales X=a, x=b, z=a y b, z = yx (un plano). Lo que se puede hacer es cortarlo en pocos pedacitos.

Superficie Verde = z = xy.
Para calcular su superficie, lo que vamos a hacer es incursionar muchos prismas, hacemos un límite de cantidad de prismas por
lo que la superficie se va a acercar a ser la superficie original.

No olvidar de escribir los diferenciales, el orden en lo que están, no son lo mismo. Están en un orden por algo, cuando se
resuelva, se tiene que resolver primero la de más adentro y luego la de más afuera. Importante que aparezcan escrito los
diferenciales, para saber respecto aa qué variables hay que integrar.

En este caso es muy importante tener en cuenta los diferenciales porque se tiene que saber con respecto a qué variable integrar.
Ver el Teorema de Fubini: Ver que hay que poner lo límites de integración y que SEAN coherentes  con los diferenciales que se ponen.

Cómo se lee:
	- El diferencial de más adentro corresponden a los integrales de más adentro
	- El diferencial de más afuera corresponden a los integrales de más afuera

Cómo construir en Geogebra estos sólidos junto con los cortes (se basa en el ejemplo del libro) [muchas imágenes]
	- Empezamos con posicionar los vértices del rectángulo.
	- Se traza eligiendo la opción "polígono" y uniendo los puntos
	- El rectángulo que se genera es la sombra sobre XY.
	- El techo es el plano de ecuación.
	- Para que hace acote sobre la porción sobre el plano, lo que se hace es:
		* Ir a buscar cada vértice y ver qué punto en Z vale en la función. Dónde hace los cortes. Se evalúa Y e Y = 0 y
		  nos devuelve Z.
		* Vamos poniendo los puntos evaluados en la función.
		* Ver de evaluar los puntos de los cuatro vértices (no es que es siempre X e Y = 0).
		* Aparece una porción del plano que se vuelve a unir con Polígono.
		* Lo que falta es trazar las aristas que faltan y eso se hace con la opción Segmento

	(Conviene si estamos graficando sobre un rectángulo, es decir, que los límites desde dónde y hasta son enteros, verificar
	sobre cada vértice sobre el techo que se traza)
	Para pintar las paredes del sólido se puede construir una porción del plano, se colorea automáticamente. En realidad, lo que
	se puede hacer es volverlo más oscuro. Eso se hace mediante la herramienta "Polígono" (siempre que sea una superficie
	plana). El color está para ponerlo más opaco.

	Otra opción:
	Parametrizando la superficie, pero eso es otra cosa que se ve más adelante.
	Se requieren dos parámetros para parametrizar la superficie [Ver las imágenes]
		- Se escribe "Superficie" y agarrar la más larga y se escribe lo que está en las imágenes.
		- El problema es cuando los límites, se tienen que volver entre funciones, ahí se complica un poco más.


A partir de acá se puede hacer la integral doble.
	- Se comienza a resolver la integral de más adentro.
		* Lo que se hace es buscar respecto a X, es decir,buscar una función que derivada me dé la original. La primitiva
		  que se obtiene se tiene que evaluar entre los límites que se tienen. En el ejemplo de la página 3 se hace entre
		  0 y 1.
		* Luego se hace lo mismo con la integral de y.

	El número que se obtiene, en medida de volumen. Son 4 metros cúbicos. Si se altera el orden de las derivadas, tiene que
	terminar dando lo mismo (se explica sobre el final de 3).

# El ejercicios nº 1

	Siempre se integra entre un cuadrado (porque son entre números, no hay complicación mayor).
	Si la función que hace un techo, da entre valores negativos y positivas, entonces es que se está calculando el área
	diferencial, positivo - negativo.

# El ejercicios nº 2:
	La función tiene que hacerlo uno.
	Ver que la superficie que da un techo es un cilindro parabólico, es fácil según la profesora, hay que trazar en el plano
	zy la porción de parábola y luego se estira ene l sentido del eje x, la porción que se obtiene de eso es el techo.

Lo que es más importante es representar sólidos acotados por superficies, plantear integrales y NO SIEMPRE la representación del
sólido será sobre un rectángulo, será una región cualquiera. No será descripto entre números enteros, sino mediante funciones.


# Ejemplo página nº 4:

Recta x = 1, y= 0, y =x.
Ver que NO está entre constantes, sino que está dependiendo de funciones. Ver el final de la página nº 4. Primero lo que habría
que hacer es el graficar la región, elijo alguna de las variables y evaluar entre lo que se puede mover X (en el ejemplo) y mover
de abajo hacia arriba (en y) para poder saber a partir desde dónde puedo salir (que es saliendo por la recta y = x).

El orden de integración no puede ser cualquiera, sino que tiene que tener un orden. Según cómo se haya descripto.
Los límites que no son constantes, van ADENTRO de las integrales, y los que son constantes, AFUERA.

# La profesora resuelve:
	Paredes que delimitan:
		- x+z = 2 	(Paralelo al eje y, que es la variable que NO aparece en la función).
		- x = 0 	(Con los planos del cuadrante)
		- y= 0 		(Son los planos del cuadrante)
		- z = 0 	(Son los planos del cuadrante)
		- y = 4 - x² 	(Cilindro parabólico).

	De las cinco superficies, no son todos iguales. Hay parábolas y planos.

	El plano es infinito sobre Y (como en la imagen)

	Hay que ver la superficie que pone el techo en el solido. La intersección entre las dos superficies es una porción de
	parábola. Que es el punto (0, 4, 2) que es el punto solución a las funciones:
		- y = 4 - x² 	(Cilindro parabólico).
		- X+Z = 2 	(Paralelo al eje y, que es la variable que NO aparece en la función).

	La línea que hay es la intersección entre un cilindro y la parábola (una porción de parábola).
	Hay que borrar lo que sale por fuera, lo que importante es lo que queda delimitada por las ecuaciones y funciones.

	Una vez realizado el gráfico lo que hay que ver es la integral que calcula su volumen.
	El techo es x + z = 2, ¿por qué? Creo que porque aparece la Z y se puede despejar.
		* z = 0, es el piso
		* x + z = 2 es el techo, porque se puede evaluar para que vaya para arriba el techo.

		Techo:
			* x + z = 2 (primera función que se evalúa la integral doble).

	SS = f(x,y) dA

	Para describir la región R tenemos que describir cómo se mueve el x e y. Es como graficar la sombra en el piso XY.
	R = sería el piso.

	Descripción:
		R : 	0 <= x <= 2
			0 <= y <= 4-x²

		El planteo al revés es medio complicado porque tiene que expresar el y = 4 - x² en función de x.
		R : 	0 <= y <= 4
			0 <= x <= \sqrt{4-y}

	Las imágenes están todas en Geogebra.

	V= S entre 0 y 2 S entre 0 y 4-x^2 (2-x) dydx


	Si nos piden cambiar el orden de integración:
		- Que se pueda escribir una integral equivalente, pero que los diferenciales estén darse vuelta: dxdy.
		- Acá está escrita entre constantes y funciones.

	Graficar la región entre funciones y luego constantes.
		- Sería lo mismo que hacer de esta forma, donde quedaría:
			R : 	0 <= y <= 4
				0 <= x <= \sqrt{4-y}

		V= S entre 0 y 2 S entre 0 y \sqrt{4-y} (2-x) dydx

### Hacer hasta Ejercicio 7

# Segunda parte de la clase:

## Ejercicio 1.C:

	Como se mueven entre 0 y 1 y entre enteros, es lo mismo que intercambiar los dx y dy.

	### dx:
	Se comienza con integrar en X. Esto se ahce considerando a y como una constante. No hace falta escribir la parte de la
	sustitución, sólo hay que pensarla. Se puede pensar que sea y=2, entonces se deja fuera la x de más arriba.
	Como está en el denominador, entonces me va a aparecer algo como ln.

	y.ln(1 + xy) como la y es una constante se puede tirar para afuera. Entonces quedaría sólo ln(1+xy)

	La técnica de derivar partes sale de la regla del producto.
	(u.v) = u'.v + u.v'
	u.v = Su'.v + Su.v'

	u' = 1		porque esto integrarlo es fácil
	v  = ln(1+y) : Porque sabemos derivar esto, pero no integrarlo

	### dy:
	S ln(1+y) dy.
		- si u'=1 entonces u = y
		- si v = ln(1+y) = v' = (1/1+y)

	Entonces:
		ln(1+y) - S (y/1+y) dy

	Ver las otras fotos de la derivada.

### Ejercicio 3.a

	No es un rectángulo porque no se mueve entre constantes, ya que tiene sen(x).
	Ver que es entre pi/2 y luego desde cero y seno de x (que es pi/2) (en la foto está puesta la región entre la que está
	evaluada)

	u = senx
	du= cosx dx => que es la derivada.

	Ojo que las regiones hay que evaluar cuando se hace sustitución.

	Se hace ahora de la forma inversa:

		R:  	0 <= y <= 1
			arcseny <= x <= pi/2

		Como y = sen x => x = arcsen y

	Algunas veces el cambio de orden de integración queda muchas veces más fácil que la original. Pero no es fácil de darse
	cuenta. Depende de la función que estemos integrando. Eso no lo vamos a saber hasta no intentar hacerlo.

### Ejercicio 4.c:
	Ver que no hay que hacer nada, porque las funciones son indefinidas.

	Ver que cuando se despeja la raiz, para sacar la raíz se eleva al cuadrado todo y se obtiene la función de una
	circunferencia. Lo que se hace es tomar la parte positiva


	Los diferenciales al reves entonces, x será entre constantes. X entre 0 y 1. Y entre las funciones

	Hay que ver al cambiar el orden de integración,
		- Desde -x a +x : Ver qué hay desde la recta y sale de una circunferencia
		- Desde -y a +y : Ver qué hay desde la recta y sale de una circunferencia
		- Por estas dos cosas anteriores, es que el cambio termina siendo CASI igual.

### Ejercicio 7:
	Hay que plantear de qué sólido se trata.

	R (la región que se integra) es la sombra del piso, que
		- X es entre 0 y 1.
		- y X^2 y 1
	La función que se integra (1-y) es el techo del solido:
		z = 1 - y (es un plano paralelo al eje x porque no está en la ecuación)

	Se evalua en z para encuentrar los puntos:
		- Se evalua y = 0, x = 1
		- Se evalua y = 1 , x = 1
		- Se evalua y = 1, x = 0

	Nombramos las superficies límites:
		- Tiene 4 caras el sólido.
			* z = 0
			* x = 0
			* z = 1- y
			* y = x^2

	Resolver una integral.

### Hasta el ejercicio 8



