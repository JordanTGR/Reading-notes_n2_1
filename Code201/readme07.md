### Modelado de Dominio

1. **Explica por qué necesitamos los modelos de dominio.**
   - Los modelos de dominio son esenciales porque ayudan a entender y representar la lógica de negocio y los conceptos clave de un sistema o aplicación en términos de objetos y relaciones. Al crear un modelo de dominio:
     - **Claridad:** Facilita la comprensión de cómo funcionan las partes del sistema y cómo se relacionan entre sí.
     - **Estructuración:** Permite organizar el código de manera que refleje los conceptos del negocio, lo que hace que el desarrollo y el mantenimiento sean más eficientes.
     - **Comunicación:** Proporciona un lenguaje común para desarrolladores, diseñadores y otros stakeholders, ayudando a alinear las expectativas y los objetivos del proyecto.
     - **Flexibilidad:** Permite modificar o extender la funcionalidad del sistema de manera más sencilla, ya que el modelo actúa como una guía para implementar cambios.

### Conceptos Básicos de las Tablas HTML

1. **¿Por qué no se debe utilizar tablas para los layouts de página?**
   - **Semántica Incorrecta:** Las tablas están diseñadas para mostrar datos tabulares y no para estructurar layouts. Usar tablas para layouts puede llevar a una estructura de HTML semánticamente incorrecta.
   - **Accesibilidad y Usabilidad:** Las tablas mal utilizadas pueden dificultar la navegación para usuarios de lectores de pantalla y dispositivos móviles. Las técnicas modernas de diseño web usan CSS para crear layouts más flexibles y accesibles.
   - **Mantenimiento y Escalabilidad:** Los layouts basados en tablas son menos flexibles y más difíciles de mantener y adaptar a diferentes tamaños de pantalla. Las soluciones basadas en CSS proporcionan un control más preciso y sencillo.

2. **Enumera y describe 3 diferentes elementos semánticos HTML utilizados en un `<table>`.**
   - **`<thead>`:** Define el encabezado de la tabla. Contiene filas (`<tr>`) con celdas (`<th>`) que describen los encabezados de cada columna.
     ```html
     <thead>
       <tr>
         <th>Nombre</th>
         <th>Edad</th>
       </tr>
     </thead>
     ```
   - **`<tbody>`:** Define el cuerpo de la tabla. Contiene las filas (`<tr>`) que representan los datos de la tabla.
     ```html
     <tbody>
       <tr>
         <td>Alice</td>
         <td>30</td>
       </tr>
     </tbody>
     ```
   - **`<tfoot>`:** Define el pie de la tabla. Se usa para colocar filas de resumen o información adicional al final de la tabla.
     ```html
     <tfoot>
       <tr>
         <td>Total</td>
         <td>30</td>
       </tr>
     </tfoot>
     ```

### Introducción a los Constructores

1. **¿Qué es un constructor y cuáles son las ventajas de utilizarlo?**
   - **Constructor:** Un constructor es una función especial en JavaScript que se utiliza para crear e inicializar objetos cuando se instancia una clase. En ES6, se define dentro de una clase usando la palabra clave `constructor`.
     ```javascript
     class Persona {
       constructor(nombre, edad) {
         this.nombre = nombre;
         this.edad = edad;
       }
     }
     ```
   - **Ventajas de Usar Constructores:**
     - **Reusabilidad:** Permite crear múltiples instancias de objetos con la misma estructura y comportamiento, reutilizando el mismo código.
     - **Inicialización Automática:** Automatiza la asignación de valores a las propiedades del objeto en el momento de su creación.
     - **Organización:** Facilita la organización del código y el mantenimiento al encapsular la lógica de inicialización en una única ubicación.

2. **¿Cómo es que el término `this` se diferencia cuando se utiliza en un objeto literal y cuando se utiliza en un constructor?**
   - **Objeto Literal:**
     - En un objeto literal, `this` se refiere al objeto literal en el que está definido el método. Por ejemplo:
       ```javascript
       const persona = {
         nombre: 'Carlos',
         saludar: function() {
           console.log(this.nombre); // `this` se refiere al objeto `persona`
         }
       };
       persona.saludar(); // Imprime 'Carlos'
       ```
   - **Constructor:**
     - En un constructor, `this` se refiere a la instancia del objeto que está siendo creada por el constructor. Por ejemplo:
       ```javascript
       class Persona {
         constructor(nombre) {
           this.nombre = nombre; // `this` se refiere a la instancia de `Persona`
         }
       }
       const juan = new Persona('Juan');
       console.log(juan.nombre); // Imprime 'Juan'
       ```

### Herencia Prototípica

1. **Explica los prototipos y las herencias por medio de una analogía sobre tu experiencia laboral previa.**
   - Imagina que trabajas en una empresa donde todos los empleados tienen un manual de procedimientos estándar que define cómo realizar tareas comunes, como cómo redactar informes o cómo usar el sistema de correo interno. Cada nuevo empleado recibe una copia de este manual para seguir las mismas prácticas estándar.
   - **Prototipo:** El manual de procedimientos es como un prototipo en JavaScript. Define métodos y propiedades comunes que los empleados (objetos) pueden usar.
   - **Herencia Prototípica:** Cuando un nuevo empleado se une a la empresa, hereda estas prácticas estándar del manual. Si hay un nuevo procedimiento añadido al manual, todos los empleados nuevos lo recibirán automáticamente, sin necesidad de actualizar cada manual individualmente.
   - En JavaScript, los objetos pueden heredar métodos y propiedades de otros objetos a través de prototipos, lo que permite que los objetos compartan y reutilicen código de manera eficiente, similar a cómo los empleados comparten prácticas estándar del manual de la empresa.