# Programación con JavaScript
## **¿Qué es “Control Flow” (Control de Flujo)?**

El control de flujo en JavaScript determina el orden en que se ejecutan las instrucciones en un programa. Incluye:

### Condicionales: Ejecutan código basado en condiciones.

* `if: if (condición) {`
  `// código si la condición es verdadera`
`}`
`if...else:`

* `if (condición) {`
  `// código si la condición es verdadera`
`} else {`
  `// código si la condición es falsa`
`}`

* `switch:`
`switch (expresión) {`
  `case valor1:`
    `// código`
    `break;`
  `case valor2:`
    `// código`
    `break;`
  `default:`
    `// código`
`}`

### Bucles: Repite código mientras se cumpla una condición.

* `for:`
`for (let i = 0; i < 5; i++) {`
  `// código`
`}`

* `while:`
`while (condición) {`
  `// código`
`}`

* `do...while:`
`do {`
  `// código`
`} while (condición);`
`Manejo de Excepciones: Gestiona errores en tiempo de ejecución.`

* `try...catch:`
`try {`
  `// código que puede lanzar una excepción`
`} catch (error) {`
`// código para manejar el error`
`}`

Estos elementos permiten estructurar el flujo lógico de un programa para que realice tareas específicas bajo ciertas condiciones y repita acciones según sea necesario.

## **¿Qué es una “function” (Función) de JavaScript?**

Una función es un bloque de código diseñado para realizar una tarea específica. Permite reutilizar y organizar el código de manera eficiente.
### Tipos de Definición

*Declaración de Función: Definida con la palabra clave function seguida por el nombre de la función.
*Expresión de Función: Asignada a una variable.
*Función Flecha: Una sintaxis más corta introducida en ES6.
### Uso
* Definir: Especifica el nombre de la función y los parámetros.
* Llamar: Invoca la función utilizando su nombre y pasando los argumentos necesarios.
### Beneficios

* Modularidad: Divide el código en piezas manejables.
* Reutilización: Usa la misma función en diferentes partes del programa.
* Mantenimiento: Facilita la actualización y corrección del código.

Las funciones son fundamentales para escribir código limpio y eficiente en JavaScript.

## ¿Qué significa “invoke” o “call” en una función?

"Invocar" o "llamar" a una función significa ejecutar el bloque de código que está definido dentro de esa función. Es el acto de hacer que la función realice su tarea.

***¿Por qué es Importante?***
Invocar una función es crucial porque define cuándo y cómo se ejecuta el código contenido en la función. Sin invocarla, el código de la función no se ejecutará.

***¿Cómo se Hace?***
Para invocar una función, simplemente se escribe el nombre de la función seguido de paréntesis. Si la función requiere datos (parámetros), estos se colocan dentro de los paréntesis.

***Beneficios***
* Organización del Código: Permite dividir el código en bloques manejables.
* Reutilización: Permite usar el mismo bloque de código múltiples veces sin duplicación.
* Claridad: Hace que el código sea más fácil de leer y mantener.
### Resumen Conceptual

Invocar una función en JavaScript es como darle una orden a un trabajador especializado. Cuando "llamas" al trabajador (función), este realiza una tarea específica que tiene definida. Esto permite que el programa ejecute tareas complejas de manera ordenada y eficiente.

## ¿Para qué sirven los paréntesis () cuando defines una función?

* Declaración de Parámetros: Los paréntesis indican qué datos (parámetros) la función puede recibir.
* Invocación de Funciones: Los paréntesis permiten ejecutar la función y pasarle argumentos.

**Ejemplos**
Definir:

`function saludar(nombre) {`
  `console.log(Hola, ${nombre});`
`}`

`Invocar:`
`saludar('Juan'); // Llama a la función con el argumento 'Juan'`

* Concepto Clave

Los paréntesis en una función en JavaScript son esenciales para definir qué información la función necesita y para ejecutar el código dentro de la función.
