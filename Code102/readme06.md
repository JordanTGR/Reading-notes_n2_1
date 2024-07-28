# Paginas web dinámicas con JavaScript
## ¿Qué son las variables en JavaScript?
En JavaScript, las variables son contenedores que almacenan datos. Se tienen la siguientes al declararlas en el codigo las cuales son var, let o const.
var:

* Se usa desde versiones antiguas de JavaScript.
* Tiene ámbito de función (accesible dentro de la función donde se declara).
* Permite redeclaración y reasignación.

let:

* Tiene ámbito de bloque (accesible solo dentro del bloque {} donde se declara).
* Permite reasignación, pero no redeclaración en el mismo ámbito.

const:

* Tiene ámbito de bloque.
* No permite reasignación (el valor asignado no puede cambiar).

**Ejemplos:**

`var nombre = "Juan";`
`nombre = "Carlos"; // Permite reasignación`

`let edad = 25;`
`edad = 26; // Permite reasignación`

`const PI = 3.14159;`
`// PI = 3.14; // Error, no permite reasignación`

**Tipos de Datos:**

1. Números: let numero = 10;
2. Cadenas de Texto: let texto = "Hola";
3. Booleanos: let esVerdadero = true;
4. Arreglos: let lista = [1, 2, 3];
5. Objetos: let objeto = { nombre: "Ana", edad: 30 }

## ¿Qué significa “declarar” una variable?
Declarar una variable en JavaScript es el proceso de crear una variable y reservar espacio en la memoria para ella. Esto se hace utilizando var, let o const. La declaración puede o no incluir la asignación de un valor inicial.

**Ejemplos**

* `let nombre;` <-----> se declara
* `let edad = 25;` <-------> se declara y asigna

Con la declaracion se almacena los datos y se manipulan.

## ¿Qué es un operador de “asignación” y qué hace?

Un operador de asignación en JavaScript se utiliza para asignar valores a las variables. El operador de asignación más básico es el signo igual (=), que asigna el valor del lado derecho a la variable del lado izquierdo.

* `let x = 5;`

Aqui el valor que se asinga a x = 5

Operadores de Asignación Compuestos
Estos operadores realizan una operación y asignan el resultado a la variable:

* `+=`: Suma el valor de la derecha a la variable y asigna el resultado.

`x += 3; // x = x + 3`

* `-=`: Resta el valor de la derecha de la variable y asigna el resultado.

`x -= 2; // x = x - 2`

* `*=`: Multiplica la variable por el valor de la derecha y asigna el resultado.

`x *= 4; // x = x * 4`

* `/=` : Divide la variable por el valor de la derecha y asigna el resultado.

`x /= 2; // x = x / 2`

* `%=` : Asigna el resto de dividir la variable por el valor de la derecha.

`x %= 3; // x = x % 3`

**Ejemplo**

`let y = 10;`
`y += 5; // Ahora y es 15`

En resumen, los operadores de asignación en JavaScript se utilizan para establecer y actualizar el valor de las variables.

## ¿Cómo se llama la información recibida del usuario?

La información recibida del usuario comúnmente se llama "entrada" o "input" en el contexto de programación y desarrollo de software. Esta entrada puede provenir de diversas fuentes, como formularios web, comandos de línea, clics del ratón, y más.

En JavaScript, la información recibida del usuario comúnmente se refiere a "entrada del usuario" o "input del usuario". Esta información puede provenir de diversas fuentes, como formularios, campos de texto, clics de botones, entre otros. 