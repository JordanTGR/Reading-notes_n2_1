# Fundamentos de texto en HTML. Formateo de texto avanzado.

## ¿Por qué es importante utilizar elementos semánticos en nuestro HTML?
Utilizar elementos semánticos en HTML es crucial por varias razones:

1. **Mejora la Accesibilidad**: Los elementos semánticos proporcionan una estructura clara que ayuda a los lectores de pantalla y otras tecnologías de asistencia a interpretar el contenido de manera más efectiva. Esto facilita la navegación y comprensión del sitio para usuarios con discapacidades.

2. **Optimización para Motores de Búsqueda (SEO)**: Los motores de búsqueda utilizan la estructura semántica para entender mejor el contenido y la jerarquía de una página. Los elementos como `<header>`, `<footer>`, `<article>`, y `<section>` ayudan a los motores de búsqueda a indexar y clasificar el contenido de manera más precisa, lo que puede mejorar el ranking en los resultados de búsqueda.

3. **Mejora la Mantenibilidad del Código**: Los elementos semánticos proporcionan una estructura lógica y coherente al código HTML. Esto hace que el código sea más fácil de leer y mantener, tanto para el desarrollador actual como para otros que puedan trabajar en el proyecto en el futuro.

4. **Facilita el Diseño y la Estilización**: Al utilizar elementos semánticos, se puede aplicar CSS de manera más específica y eficiente. Los estilos se pueden asignar a elementos específicos con base en su propósito semántico, lo que simplifica el diseño y mejora la consistencia visual.

5. **Fomenta las Mejores Prácticas de Desarrollo**: Usar elementos semánticos sigue las mejores prácticas de desarrollo web, promoviendo una codificación más organizada y estructurada. Esto ayuda a construir páginas web más robustas y estables.

En resumen, los elementos semánticos no solo mejoran la accesibilidad y SEO, sino que también facilitan la mantenibilidad y el diseño del código, contribuyendo a un desarrollo web más eficaz y profesional.
## ¿Cuántos niveles de encabezado existen en HTML?
En HTML, hay seis niveles de encabezado, desde `<h1>` hasta `<h6>`. `<h1>` es el nivel más alto, usado para el título principal, y `<h6>` es el nivel más bajo, usado para subsecciones menores. Cada nivel organiza el contenido en una jerarquía, facilitando la lectura y la navegación.
## ¿Cuáles son algunos de los usos para los elementos `<sup>` y `<sub>`?

Los elementos <sup> y <sub> en HTML se utilizan para mostrar texto en superíndice y subíndice, respectivamente. El <sup> coloca el texto ligeramente por encima de la línea base del texto normal, mientras que el <sub> lo coloca por debajo. Estos elementos son útiles para representar anotaciones, exponentes, o cualquier texto que requiera una posición especial en relación con el texto principal.

## Al utilizar el elemento `<abbr>`, qué atributo se debe añadir para proporcionar una ampliación del término?

Al utilizar el elemento `<abbr>`, se debe añadir el atributo title para proporcionar una ampliación o definición del término abreviado.


# Cómo se estructura el CSS.


## ¿De qué formas podemos añadir CSS a nuestro HTML?

Podemos añadir CSS a HTML de tres formas: usando estilos en línea con el atributo `style`, incorporando estilos internos dentro de una etiqueta `<style>` en el `<head>`, o enlazando un archivo CSS externo con la etiqueta `<link>`.

## ¿Por qué deberíamos evitar utilizar estilos inline?

Deberíamos evitar utilizar estilos en línea porque:

1. **Dificultan el Mantenimiento**: Hacer cambios en el diseño requiere modificar cada elemento individualmente en lugar de actualizar un solo archivo CSS.

2. **Reducen la Reusabilidad**: Los estilos en línea no permiten aplicar el mismo diseño a múltiples elementos fácilmente, lo que lleva a redundancia y menos consistencia.

3. **Afectan el Rendimiento**: Aumentan el tamaño del HTML, lo que puede ralentizar la carga de la página.

4. **Complican el Diseño**: La separación de contenido y estilo se pierde, haciendo el código menos organizado y más difícil de leer. 

Utilizar CSS externo o interno promueve un diseño más limpio, mantenible y eficiente.

## Revisa el código a continuación y responde a las siguientes preguntas:
  `h2 {`
     `color: black;`
     `padding: 5px;`
   `}`
### ¿Qué representa el selector?
El selector h2 representa todos los elementos <h2> en el documento HTML, aplicando los estilos definidos a esos elementos.
### ¿Qué componentes son declaraciones CSS?

Las declaraciones CSS son las combinaciones de propiedades y valores dentro de las llaves `{}`. En este caso, las declaraciones son `color: black`; y `padding: 5px;`.


### ¿Qué componentes se consideran propiedades?

Las propiedades son las partes de las declaraciones que definen qué aspecto se está estilizando. En el código dado, las propiedades son `color` y `padding`.

# Aprende JS

## ¿Qué tipo de dato es una secuencia de texto entre comillas simples?

Una secuencia de texto entre comillas simples es un string en JavaScript.

## Enumera 4 tipos de operadores en JavaScript.

   * Operadores aritméticos (e.g., `+`, `-`)
   * Operadores de comparación (e.g., `==`, `===`)
   * Operadores lógicos (e.g., `&&`, `||`)
   * Operadores de asignación (e.g., `=`, `+=`)

## Describe un problema práctico que puedes resolver con una función.

Puedes usar una función para calcular el total de una factura sumando los precios de varios artículos, aplicando descuentos, y agregando impuestos. Esto permite reutilizar el cálculo en diferentes contextos sin tener que reescribir el código.

# Tomando decisiones en tu código — condicionales.

## Si una declaración if comprueba un __ y si resulta ___, entonces el código se ejecutará.

   Si una declaración `if` comprueba una **condición** y si resulta **verdadera**, entonces el código se ejecutará.

## ¿Cuál es el uso del else if?

   El `else if` se usa para comprobar múltiples condiciones alternativas si la condición del `if` inicial es falsa.

## Enumera 3 tipos de operadores de comparación.

   * `==` (igualdad)
   * `===` (igualdad estricta)
   * `!==` (desigualdad)

## ¿Cuál es la diferencia entre los operadores lógicos `&&` y `||`?

 El operador `&&` (AND) devuelve verdadero solo si ambas condiciones son verdaderas, mientras que `||` (OR) devuelve verdadero si al menos una de las condiciones es verdadera.