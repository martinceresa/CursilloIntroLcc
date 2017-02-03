# Alan Turing 1912 - 1954

En 1935 Alan Turing formuló el concepto de qué es computar en el proceso de resolver
a uno de los problemas propuestos por Hilbert.

Leibniz había soñado con que la razón humana podía reducirse
a meros cálculos y de un mecanismo los suficientemente poderos para
llevar a cabo dichos cálculos. Frege proveyó por primera vez un sistema
de reglas que podrían contar como todo el poder de razonamiento 
deductivo humano. Gödel, en su disertación doctoral de 1930, probó
que las reglas de Frege eran completas, respondiendo a una pregunta
de Hilbert. Lo que quedaba era una última pregunta de Hilbert que
se preguntaba que si siempre es posible dado una colección
de hipótesis, llegar a la conclusión, y de ser así se se podía
mecanizar el proceso. El problema se conoce como el 
Entscheinungsproblem (literalmente *problema de decisión*). 

En principio una solución a este problema habría reducido
todo el poder deductivo del ser humano a unos brutos cálculos.
Y esto habría sido el sueño de Leibniz.

## Descubriendo que es computar

Turing sabía que lo que era un algoritmo, típicamente especificado
por una lista de reglas que una persona puede seguir en una forma
totalmente mecánica, como las recetas de cocina. Pero turing
se enfocó en qué es lo que una persona realmente puede *hacer*
cuando está siguiendo las reglas. Eliminando detalles innecesarios
llegó a descubrir una máquina muy simple pero extremadamente poderosa.
Y probando que con estas máquinas no podían llevar a cabo la tarea
que Hilbert proponía era porque no existía algoritmo posible que
lo haga.

### Proceso de simplificación, depende del tiempo

following Turing's thought processes, first center in the epoch,
literally a computer was a person, in particular a woman, why perform
something on a sheet of paper. She could be observed shifting her
attention from what she had written earlier to what she is writing
now, Turing wanted to remove all unimportant details, was she drinking
coffee? Not important. was she writing with a pencil or pen?? Not
relevant. Big or small paper? In fact Turing convinced himself that
while it might be a nuisance to deal with a complicated calc along a
one-dimensional tape, there was no fundamental problem in doing so.

Ex : 1043 x23 = 3129 + 20860 = 23989

Let continue, now restricted to a roll of paper tape. we watch as our
subject glances back and forth along the tape, writing symbols, some
times backing up and erasing symbols so new symbols can be written in
their place. Her decision about what to write next will depend not
only on which symbols she is paying attention to but also on her
current state of mind. Even in the case of our simple multiplication
example, as she notes pairs of digits, her states of mind will
determine whether she multiplies or adds them.

### Seguimos.

Una persona llevando a cabo una computación artimetica, o cualquier otra,
opera con las siguientes restricciones:

* En toda etapa de la computación solo a un numero chico de símbolos
se les presta atención.
* La acción tomada en una etapa depende solo del símbolo en particular
al que se le presta atención y al estado de la mente de la persona
llevando a cabo la computación.

A cuantos símbolos se les puede prestar atención simultáneamente?
Cuantos son realmente necesario??
Para la primer pregunta, depende de la persona aunque seguro que son pocos.
La respuesta a la segunda es **uno**!!

Esto es porque el efecto de prestarle atención a varios símbolos
puede llevarse a prestarle atención a uno a la vez. Y lo mismo para
el movimiento en la cinta.

Este análisis lleva a la conclusión que para cualquier computación
se procede de la siguiente manera:
* Escribir símbolos en un rectángulo de una cita cuadriculada.
* A cada etapa la persona llevando a cabo la computación presta atención
al símbolo en uno de estos rectángulos.
* Su siguiente acción solo dependerá de este símbolo y su
estado de mente.
* Esta nueva acción consistirá en escribir un símbolo
en el rectángulo al que le presta atención y luego posiblemente
cambiando su atención al rectángulo que está inmediatamente a su
izquierda o derecha.

Y esto es una máquina de Turing!! Todo lo computable por un algoritmo
se puede computar con una máquina de Turing.

Turing además creó lo que es conocido como la Máquina Universal de Turing.
