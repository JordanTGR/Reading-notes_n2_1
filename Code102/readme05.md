# Read 05: Diseño de paginas web con CSS
## ¿Cuál es el propósito de CSS?
El propósito del CSS es especificar cómo se presentan los documentos a los usuarios, diseñando y compaginando el contenido. Permite cambiar estilos básicos, como color y tamaño de texto, crear diseños complejos con áreas de contenido y barras laterales, y agregar efectos de animación.

![CSS](https://ksra.eu/wp-content/uploads/2021/05/Vp9WvV7YKdH4k8sKRePcE8-1200-80.jpeg)

## ¿Cuáles son las tres formas de insertar CSS en tu proyecto?
Las tres formas de insertar CSS en tu proyecto son:

1. CSS en línea (inline): Usar el atributo style directamente en los elementos HTML.

`<p style="color: red;">Este es un texto rojo.</p>`

2. CSS interno (internal): Incluir CSS dentro de una etiqueta `<style>` en el `<head>` del documento HTML.

`<head>`
  `<style>`
    `p { color: blue; }`
  `</style>`
`</head>`

3. CSS externo (external): Enlazar un archivo CSS separado usando la etiqueta `<link>` en el `<head>` del documento HTML.

`<head>`
  `<link rel="stylesheet" href="styles.css">`
`</head>`


## Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos `<p>`
Una buena forma es de la siguiente manera, que es mas directo en el documento html.

`<head>`

  `<style>`

    p{
      color: red;
    }

  `</style>`

`</head>`

![CSSColor](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/CSS_basics/css-declaration-small.png)