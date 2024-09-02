
### HTML: Crear Hipervínculos

1. **Para crear un enlace básico, ¿en qué elemento colocamos el texto u otro contenido?**
   - El texto u otro contenido para un enlace se coloca dentro del elemento `<a>`. El contenido dentro de este elemento es lo que se mostrará como el enlace en la página web.
     ```html
     <a href="https://www.ejemplo.com">Visita nuestro sitio</a>
     ```

2. **¿Qué información contiene el atributo `href`?**
   - El atributo `href` en el elemento `<a>` especifica la URL o dirección del recurso al que el enlace debe llevar al usuario. Puede ser una URL completa, una dirección relativa, o un enlace a una ancla dentro de la misma página.
     ```html
     <a href="https://www.ejemplo.com">Enlace a Ejemplo</a>
     ```

3. **¿Cuáles son algunas de las formas en las que podemos asegurarnos de que los enlaces a nuestras páginas sean accesibles a todos los lectores?**
   - **Texto Descriptivo:** Usa texto descriptivo en los enlaces para que sean comprensibles para lectores de pantalla.
   - **Atributo `title`:** Proporciona información adicional sobre el enlace usando el atributo `title`, aunque no debe ser la única forma de comunicar la información.
   - **Contraste y Tamaño:** Asegúrate de que los enlaces tengan un buen contraste con el fondo y sean suficientemente grandes para ser clicables.
   - **Uso de ARIA:** Usa atributos ARIA (Accessible Rich Internet Applications) para mejorar la accesibilidad.

### CSS Layout

1. **¿A qué se refiere con “normal flow”?**
   - "Normal flow" se refiere al flujo de documentos en el modelo de caja de CSS estándar, donde los elementos se colocan uno tras otro en el orden en que aparecen en el HTML. Los elementos de bloque (block-level) ocupan todo el ancho disponible y comienzan en una nueva línea, mientras que los elementos en línea (inline) se colocan uno al lado del otro en la misma línea.

2. **¿Cuáles son algunas de las diferencias entre los elementos block-level e inline?**
   - **Elementos block-level:**
     - Ocupan todo el ancho disponible de su contenedor.
     - Comienzan en una nueva línea.
     - Ejemplos: `<div>`, `<p>`, `<h1>`.
   - **Elementos inline:**
     - Solo ocupan el ancho necesario para su contenido.
     - No comienzan en una nueva línea; se sitúan al lado de otros elementos en línea.
     - Ejemplos: `<span>`, `<a>`, `<strong>`.

3. **El ___ positioning es la posición por defecto de todos los elementos en HTML.**
   - **"Static"** es el valor por defecto para la propiedad `position` de todos los elementos en HTML. Los elementos con `position: static` se colocan en el flujo normal del documento.

4. **Nombra algunas ventajas de utilizar absolute positioning en un elemento.**
   - **Control Preciso:** Permite posicionar un elemento en una ubicación específica dentro de su contenedor más cercano con `position: relative`.
   - **Independencia del Flujo:** El elemento con `position: absolute` no afecta la disposición de otros elementos en el flujo del documento.
   - **Superposiciones y Diseño Complejo:** Es útil para crear elementos flotantes, superposiciones y diseños complejos que requieren un posicionamiento exacto.

5. **¿Cuál es una diferencia clave entre fixed positioning y absolute positioning?**
   - **`position: absolute`:** El elemento se posiciona en relación con el contenedor más cercano que no tenga `position: static`. Si no hay tal contenedor, se posiciona en relación con el elemento `<html>`.
   - **`position: fixed`:** El elemento se posiciona en relación con la ventana del navegador. Permanece en la misma posición incluso cuando el usuario desplaza la página.

### JavaScript: Funciones

1. **Describe la diferencia entre una declaración de función y una invocación de función.**
   - **Declaración de Función:** Es el proceso de definir una función, especificando su nombre, parámetros y el bloque de código que ejecutará. Se realiza usando la palabra clave `function`.
     ```javascript
     function saludar(nombre) {
         console.log("Hola, " + nombre);
     }
     ```
   - **Invocación de Función:** Es el proceso de ejecutar una función previamente declarada, utilizando su nombre y proporcionando los argumentos necesarios.
     ```javascript
     saludar("Juan"); // Esto llama a la función saludar con el argumento "Juan"
     ```

2. **¿Cuál es la diferencia entre un parameter y un argument?**
   - **Parameter:** Es una variable en la declaración de una función que recibe un valor cuando la función es llamada. Es parte de la definición de la función.
     ```javascript
     function sumar(a, b) { // `a` y `b` son parámetros
         return a + b;
     }
     ```
   - **Argument:** Es el valor real que se pasa a la función cuando se invoca. Es lo que se usa para llenar los parámetros de la función.
     ```javascript
     sumar(5, 3); // `5` y `3` son argumentos
     ```