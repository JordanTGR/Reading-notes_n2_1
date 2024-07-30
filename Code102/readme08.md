# Operadores y bucles
## ¿Qué es una “expresión” en JavaScript?

En JavaScript, una "expresión" es cualquier fragmento de código que produce un valor.

### Ejemplos:

**1. Literales:**

* Números: 42
* Cadenas: 'Hello'
* Booleanos: true

**2. Aritméticas:**

* 5 + 3
* 10 * 2

**3. Lógicas:**

* true && false
* !true

**4. Asignación:**

* var x = 10
* x += 5

**5. Comparación:**

* 5 == '5'
* 10 > 2

**6. Llamada a función:**

alert('Hi')
Math.max(1, 2)
Las expresiones son fundamentales en JavaScript porque cualquier código que genera un valor es una expresión

## ¿Por qué usaríamos un bucle en nuestro código?

1. Bucle for: Ejecuta un bloque de código un número específico de veces. Utilizado cuando conoces el número exacto de iteraciones.

* Estructura:

`for (inicialización; condición; incremento) {`
  `// Código a ejecutar`
`}`

2. Bucle `while`: Ejecuta un bloque de código mientras una condición sea verdadera. Utilizado cuando no conoces el número exacto de iteraciones.

* Estructura:
`while (condición) {`
  `// Código a ejecutar`
`}`

3. Bucle `do...while`: Similar a `while`, pero ejecuta el bloque de código al menos una vez antes de evaluar la condición.

* Estructura
`do {`
  `// Código a ejecutar`
`} while (condición);`

4. Bucle for...in: Itera sobre las propiedades enumerables de un objeto.

* Estructura
`for (propiedad in objeto) {`
  `// Código a ejecutar`
`}`

5. Bucle `for...of`: Itera sobre objetos iterables como arrays, strings, mapas, etc.

* Estructura

`for (variable of iterable) {`
  `// Código a ejecutar`
`}`

#### Métodos de Iteración de Arrays

1. forEach: Ejecuta una función una vez por cada elemento del array.

2. map: Crea un nuevo array con los resultados de aplicar una función a cada elemento del array original.

3. filter: Crea un nuevo array con todos los elementos que pasan una prueba definida en una función.

4. reduce: Ejecuta una función reductora sobre cada elemento del array, resultando en un único valor.

#### Ventajas de Usar Bucles

* Eficiencia: Permiten manejar grandes volúmenes de datos de manera repetitiva sin duplicar código.

* Legibilidad y Mantenimiento: Hacen el código más conciso y fácil de leer y mantener.

* Flexibilidad: Permiten ajustes fáciles en el comportamiento del bucle cambiando las condiciones o el bloque de código que se ejecuta.

## ¿Cuándo deja de ejecutarse un bucle `for`?

Un bucle for deja de ejecutarse cuando la condición especificada en su estructura evalúa como falsa.

## ¿Cuántas veces se ejecutará un bucle “ while “?

Un bucle `while` se ejecutará mientras la condición especificada evalúe como verdadera. La cantidad de veces que se ejecuta depende de cómo cambia la condición en cada iteración. Si la condición nunca se vuelve falsa, el bucle puede continuar indefinidamente, causando un bucle infinito.