
### Medios en HTML: Utilizar Imágenes

1. **¿Cuál es un caso práctico del atributo `alt` en una página web?**
   - El atributo `alt` proporciona una descripción alternativa de una imagen. Esto es útil en varias situaciones:
     - **Accesibilidad:** Los lectores de pantalla usan el texto alternativo para describir la imagen a personas con discapacidad visual.
     - **Carga de Imágenes:** Si una imagen no se carga debido a un problema técnico o conexión lenta, el texto alternativo se muestra en su lugar, proporcionando contexto sobre lo que se esperaba ver.
     - **SEO:** Los motores de búsqueda utilizan el texto alternativo para comprender el contenido de la imagen, lo que puede mejorar la visibilidad en los resultados de búsqueda.

2. **¿Cómo puedes mejorar la accesibilidad de las imágenes en un documento HTML?**
   - **Uso del Atributo `alt`:** Siempre proporciona una descripción clara y concisa usando el atributo `alt` en las etiquetas `<img>`.
   - **Texto Descriptivo:** Si la imagen es decorativa y no aporta información, puedes usar `alt=""` para indicar que el contenido de la imagen es irrelevante para el usuario.
   - **Asegúrate de que la Imagen sea Contextual:** Incluye descripciones que sean útiles y relevantes para el contexto en el que se presenta la imagen.
   - **Usa Anclas y Botones Apropiadamente:** Si una imagen funciona como un enlace o un botón, asegúrate de que tenga un texto alternativo que explique su función.

3. **Da un ejemplo en el que el elemento `<figure>` sería útil en un documento HTML.**
   - El elemento `<figure>` es útil cuando deseas agrupar una imagen con una leyenda. Esto proporciona una mejor semántica y estructura al documento. 
     ```html
     <figure>
         <img src="foto-vacaciones.jpg" alt="Vista panorámica de la playa durante el atardecer">
         <figcaption>Foto de nuestras vacaciones en la playa al atardecer.</figcaption>
     </figure>
     ```

4. **Describe la diferencia entre una imagen GIF y una imagen SVG, imagina que se lo estás explicando a una persona mayor de tu comunidad.**
   - **GIF (Graphics Interchange Format):** Es un tipo de imagen que puede tener animaciones y es buena para imágenes simples con colores limitados. Piensa en un GIF como una pequeña película que se repite en bucle.
   - **SVG (Scalable Vector Graphics):** Es un tipo de imagen que está hecha de líneas y formas en lugar de píxeles. Esto significa que puedes hacerla más grande o más pequeña sin perder calidad. Es útil para logos y gráficos que necesitan verse bien a cualquier tamaño. Piensa en SVG como un dibujo hecho con lápiz y regla que puedes redibujar sin que se vea borroso.

5. **¿Qué tipo de imagen usarías para mostrar una captura de pantalla en tu página web y por qué?**
   - **PNG** es generalmente la mejor opción para capturas de pantalla. Esto se debe a que PNG soporta alta calidad de imagen y mantiene los detalles, además de ofrecer compresión sin pérdida que conserva la claridad de la imagen.

### Aprende CSS: Usando Color y Estilizando Elementos de Texto

1. **Describe la diferencia entre un color de primer plano y un color de fondo de un elemento HTML, imagina que estás hablando con una persona sin conocimientos técnicos.**
   - **Color de Primer Plano (Foreground Color):** Es el color del texto o del contenido que se muestra sobre el fondo. Por ejemplo, el color del texto en una página.
   - **Color de Fondo (Background Color):** Es el color que aparece detrás del contenido. Por ejemplo, el color del área detrás del texto o de una caja de contenido.

2. **Tu amigo te pide que le des un retoque a su blog. ¿Cómo utilizarías color para darle carácter a su blog?**
   - **Paleta de Colores:** Elige una paleta de colores que se alinee con el tema del blog o la marca. Usa colores principales para los encabezados y elementos destacados, y colores secundarios para fondos y acentos.
   - **Contraste:** Asegúrate de que haya suficiente contraste entre el texto y el fondo para que sea fácil de leer.
   - **Colores de Enlace:** Usa colores que destaquen para los enlaces, para que sean fácilmente reconocibles.
   - **Estilos de Sección:** Utiliza colores diferentes para las secciones del blog para crear una jerarquía visual y hacer que el contenido sea más atractivo.

3. **¿Qué debes tener en cuenta al escoger tipos de letra para un documento HTML?**
   - **Legibilidad:** Asegúrate de que el tipo de letra sea fácil de leer en diferentes tamaños y en diferentes dispositivos.
   - **Compatibilidad:** Usa fuentes que sean ampliamente soportadas o proporciona una lista de fuentes alternativas en caso de que la fuente principal no esté disponible.
   - **Consistencia:** Mantén la coherencia en el uso de fuentes a lo largo del documento para crear un diseño armonioso.
   - **Estilo y Tonalidad:** Elige una fuente que refleje el estilo y tono del contenido del documento.

4. **¿Cuál es la relación entre `font-size`, `font-weight`, y `font-style` con los elementos de texto en HTML?**
   - **`font-size`:** Controla el tamaño del texto. Un tamaño mayor hará que el texto sea más grande, y un tamaño menor lo hará más pequeño.
   - **`font-weight`:** Controla el grosor del texto. Puedes hacer el texto más grueso (negrita) o más delgado, dependiendo del valor que configures.
   - **`font-style`:** Controla el estilo del texto, como si está en cursiva (`italic`) o normal. Esto afecta cómo se ve el texto en términos de inclinación.

5. **Describe dos formas de añadir espaciado alrededor de los caracteres mostrados en un elemento `<h1>`.**
   - **`letter-spacing`:** Ajusta el espaciado entre caracteres individuales. Puedes usar esta propiedad para aumentar o disminuir el espacio entre letras.
     ```css
     h1 {
         letter-spacing: 2px; /* Aumenta el espacio entre letras */
     }
     ```
   - **`word-spacing`:** Ajusta el espaciado entre palabras. Esto afecta el espacio entre las palabras en el texto del `<h1>`.
     ```css
     h1 {
         word-spacing: 4px; /* Aumenta el espacio entre palabras */
     }
     ```