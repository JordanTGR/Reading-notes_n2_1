
### Conceptos Básicos de los Objetos JavaScript

1. **¿Cómo le describirías un objeto a un amigo sin conocimiento técnico con el que creciste?**
   - Imagina que un objeto en JavaScript es como una caja de herramientas. Dentro de esta caja, tienes diferentes compartimentos (llamados "propiedades") donde guardas cosas específicas, como un martillo, destornilladores, etc. Cada compartimento tiene un nombre (como "martillo" o "destornillador") y guarda algo dentro (como las características o la información del objeto). Además, la caja puede tener algunos "botones" (llamados "métodos") que te permiten hacer cosas con lo que guardas dentro, como usar el martillo para clavar un clavo.

2. **¿Cuáles son algunas de las ventajas de crear objetos literales?**
   - **Simplicidad:** Los objetos literales son fáciles de crear y entender, ya que se definen de manera directa en el código.
   - **Organización:** Permiten agrupar datos y funciones relacionadas en una sola estructura, haciendo el código más organizado y fácil de mantener.
   - **Lectura y Escritura:** Facilitan la lectura y escritura de datos al usar una sintaxis clara y concisa.
   - **Flexibilidad:** Pueden ser modificados y extendidos fácilmente en tiempo de ejecución.

3. **¿En qué se diferencian los objetos de los arrays?**
   - **Objetos:**
     - Almacenan pares clave-valor. Las claves son cadenas (o símbolos) y los valores pueden ser cualquier tipo de dato.
     - Son ideales para representar entidades con propiedades no ordenadas, como una persona con nombre, edad, etc.
   - **Arrays:**
     - Almacenan elementos en una lista ordenada, accesible por índices numéricos.
     - Son ideales para manejar colecciones de datos que requieren un orden específico, como una lista de números o nombres.

4. **Da un ejemplo acerca de los momentos en los que necesitarías utilizar bracket notation para acceder a la propiedad de un objeto en vez de dot notation.**
   - La notación de corchetes (`[]`) es útil cuando el nombre de la propiedad:
     - **Contiene caracteres especiales o espacios:**
       ```javascript
       const person = {
           'full name': 'John Doe'
       };
       console.log(person['full name']); // Usa corchetes porque el nombre tiene un espacio
       ```
     - **Es una variable:**
       ```javascript
       const key = 'age';
       const person = {
           name: 'Alice',
           age: 30
       };
       console.log(person[key]); // Usa corchetes para acceder con una variable
       ```

5. **Evalúa el siguiente código. ¿A qué se refiere el término `this` y cuál es la ventaja de utilizarlo?**
   ```javascript
   const dog = {
     name: 'Spot',
     age: 2,
     color: 'white with black spots',
     humanAge: function() {
       console.log(`${this.name} is ${this.age * 7} in human years`);
     }
   }
   ```
   - **`this`** se refiere al objeto actual en el contexto en el que se está ejecutando el método. En este caso, dentro de la función `humanAge`, `this` hace referencia al objeto `dog`.
   - **Ventaja de usar `this`:** Permite acceder a las propiedades del objeto dentro de sus métodos sin necesidad de referirse explícitamente al nombre del objeto. Esto hace que el código sea más limpio y reutilizable, especialmente cuando el objeto puede cambiar o cuando se crean múltiples instancias de un objeto similar.

### Introducción al DOM

1. **¿Qué es el DOM?**
   - El DOM (Document Object Model) es una interfaz de programación para documentos HTML y XML. Representa la estructura del documento como un árbol de nodos, donde cada nodo es un componente del documento (como elementos, atributos y texto). El DOM permite a los programas y scripts interactuar y modificar la estructura, estilo y contenido del documento web de manera dinámica.

2. **Describe brevemente la relación entre el DOM y JavaScript.**
   - JavaScript utiliza el DOM para manipular y actualizar el contenido y la estructura de las páginas web en tiempo real. A través del DOM, JavaScript puede acceder a elementos HTML, modificar sus atributos, cambiar su estilo, responder a eventos (como clics y entradas de teclado) y actualizar el contenido de la página sin necesidad de recargarla. Esto permite crear aplicaciones web interactivas y dinámicas.
