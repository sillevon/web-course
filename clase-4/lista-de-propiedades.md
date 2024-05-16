# Propiedades

1. **color**: Define el color del texto.
2. **font-family**: Especifica la fuente del texto.
3. **font-size**: Define el tamaño del texto.
4. **font-weight**: Controla el grosor del texto (normal, negrita, etc.).
5. **text-align**: Define la alineación del texto.
6. **background-color**: Define el color de fondo de un elemento.
7. **width**: Establece el ancho de un elemento.
8. **height**: Establece la altura de un elemento.
9. **margin**: Define el margen alrededor de un elemento.
10. **padding**: Define el relleno dentro de un elemento.
11. **border**: Define el borde de un elemento.
12. **display**: Controla cómo se muestra un elemento en el flujo del documento.
13. **position**: Controla el método de posicionamiento de un elemento.
14. **float**: Permite que un elemento flote hacia la izquierda o la derecha de su contenedor.
15. **z-index**: Controla la superposición de elementos posicionados.
16. **opacity**: Define la opacidad de un elemento.
17. **transition**: Permite suavizar los cambios entre los estilos CSS.
18. **box-shadow**: Agrega sombras a los elementos.
19. **border-radius**: Define el radio de los bordes de un elemento.
20. **flexbox**: Un conjunto de propiedades para diseño flexible de elementos en un contenedor.

## Tipos de display

1. **`block`**: Los elementos con esta propiedad ocupan todo el ancho disponible de su contenedor y comienzan en una nueva línea. Ejemplos de elementos de bloque son `<div>`, `<p>`, `<h1>` - `<h6>`, entre otros.

2. **`inline`**: Los elementos con este valor se muestran en línea con el texto circundante, sin iniciar una nueva línea. Ejemplos de elementos en línea son `<span>`, `<a>`, `<strong>`, `<em>`, entre otros.

3. **`inline-block`**: Este valor combina las características de los elementos de bloque y en línea. Los elementos `inline-block` se comportan como elementos en línea, pero pueden tener ancho, alto, margen y relleno, similar a los elementos de bloque. Esto los hace útiles para elementos que necesitan ser dispuestos horizontalmente pero que también necesitan tener dimensiones.

4. **`none`**: Con este valor, el elemento no se muestra en absoluto. Es como si el elemento no estuviera presente en el documento, aunque sigue ocupando espacio en el flujo del documento. Esto es útil para ocultar temporalmente elementos con CSS.

5. **`flex`**: Con la aparición de Flexbox en CSS, este valor permite la creación de un diseño flexible en un contenedor. Los elementos dentro de un contenedor con `display: flex` pueden ser colocados y alineados de manera flexible en relación con el contenedor y entre sí.

6. **`grid`**: Similar a Flexbox, Grid Layout (`display: grid`) proporciona un sistema de diseño bidimensional que permite organizar los elementos en filas y columnas. Es particularmente útil para diseñar estructuras de diseño más complejas y controladas.

Estos son algunos de los valores más comunes para la propiedad `display`, pero hay otros menos comunes y más especializados, como `table`, `table-cell`, `table-row`, etc., que se utilizan para controlar el diseño de tablas y sus componentes. La elección del valor `display` adecuado depende del diseño y la estructura deseados para los elementos HTML en tu página web.

## Modelo de caja

El modelo de caja es un concepto fundamental en CSS que describe cómo se representan visualmente los elementos HTML en una página web. Cada elemento HTML se considera una "caja" rectangular que consiste en cuatro áreas principales: contenido, relleno, borde y margen. Estas áreas afectan el tamaño total del elemento y cómo se muestra en la página.

Aquí está una explicación de cada una de estas áreas:

1. **Contenido (Content)**: Esta es el área interior de la caja y contiene el contenido real del elemento, como texto, imágenes, otros elementos anidados, etc.

2. **Relleno (Padding)**: El relleno es el espacio entre el contenido y el borde de la caja. Se puede pensar en él como un espacio adicional dentro de la caja alrededor del contenido. Se utiliza la propiedad `padding` en CSS para controlar el tamaño del relleno.

3. **Borde (Border)**: El borde es una línea que rodea el contenido y el relleno de la caja. Se utiliza para definir el límite visual del elemento. Puedes establecer el ancho, el estilo y el color del borde usando la propiedad `border` en CSS.

4. **Margen (Margin)**: El margen es el espacio fuera del borde de la caja y entre esta y otras cajas vecinas. Es el espacio en blanco alrededor del elemento que separa visualmente el elemento de otros elementos en la página. Se utiliza la propiedad `margin` en CSS para controlar el tamaño del margen.

El modelo de caja de CSS es fundamental para diseñar y posicionar elementos en una página web. Al comprender cómo se aplican estas áreas y cómo pueden modificarse con CSS, los diseñadores web pueden crear diseños más efectivos y visualmente atractivos. Además, el modelo de caja es compatible con varias técnicas de diseño, como el diseño responsivo y el diseño adaptable, lo que lo convierte en una parte esencial del desarrollo web moderno.

## Flex

Flexbox, o Flexible Box Layout, es un modelo de diseño en CSS que proporciona una manera eficiente de diseñar y organizar elementos en un contenedor de manera flexible y dinámica. Con Flexbox, puedes alinear y distribuir elementos de manera automática dentro de un contenedor, lo que facilita la creación de diseños complejos y responsivos sin depender tanto de flotadores, posiciones absolutas o tablas.

Aquí hay una explicación de los conceptos clave de Flexbox:

1. **Contenedor Flex (Flex Container)**: El contenedor flex es un elemento que contiene uno o más elementos secundarios (hijos) que se organizan utilizando el modelo de caja flexible. Para convertir un elemento en un contenedor flex, se aplica la propiedad `display: flex` o `display: inline-flex` al elemento padre.

2. **Ejes Flex (Flex Axes)**: Flexbox opera en dos ejes: el eje principal (main axis) y el eje transversal (cross axis). El eje principal se alinea a lo largo del flujo de la escritura (horizontal o vertical), mientras que el eje transversal es perpendicular al eje principal.

3. **Elementos Flex (Flex Items)**: Son los elementos secundarios directos del contenedor flex. Se colocan y alinean dentro del contenedor según las propiedades y los valores aplicados a ellos.

4. **Dirección de Flexión (Flex Direction)**: Define la dirección en la que se colocan los elementos dentro del contenedor flex. Puede ser `row` (horizontal, de izquierda a derecha), `row-reverse` (horizontal, de derecha a izquierda), `column` (vertical, de arriba a abajo) o `column-reverse` (vertical, de abajo a arriba).

5. **Justificación y Alineación (Justify Content y Align Items)**: Permiten controlar la distribución de los elementos a lo largo del eje principal y el eje transversal respectivamente. `justify-content` alinea los elementos a lo largo del eje principal, mientras que `align-items` alinea los elementos a lo largo del eje transversal.

6. **Alineación de las Líneas (Align Content y Align Self)**: `align-content` controla la alineación de las líneas flexibles dentro del contenedor cuando hay espacio adicional en el eje transversal, mientras que `align-self` controla la alineación de un elemento flex individual dentro del contenedor.

7. **Orden de Visualización (Order)**: La propiedad `order` permite cambiar el orden visual de los elementos flex dentro del contenedor, sin cambiar el orden en el marcado HTML.

Flexbox es muy flexible y potente, lo que lo hace ideal para crear diseños complejos y responsivos de manera eficiente. Además, es ampliamente compatible con la mayoría de los navegadores modernos, lo que lo convierte en una herramienta versátil para el diseño web.

## Grid

CSS Grid Layout es un sistema de diseño bidimensional que permite crear diseños complejos y flexibles utilizando filas y columnas. Similar a Flexbox, CSS Grid Layout proporciona una manera poderosa y predecible de organizar elementos en una página web, pero con un enfoque más en el diseño de la estructura de la página en lugar de la disposición de los elementos individuales.

Aquí hay una explicación de los conceptos clave de CSS Grid Layout:

1. **Contenedor de Cuadrícula (Grid Container)**: Es el elemento que contiene todos los elementos secundarios (hijos) y sobre el cual se aplica el sistema de cuadrícula. Se convierte en un contenedor de cuadrícula estableciendo la propiedad `display` en `grid` o `inline-grid`.

2. **Filas y Columnas (Rows and Columns)**: En CSS Grid, puedes definir tanto filas como columnas para crear una cuadrícula. Puedes especificar el número de filas y columnas, así como sus tamaños y distribuciones utilizando propiedades como `grid-template-rows`, `grid-template-columns`, `grid-auto-rows` y `grid-auto-columns`.

3. **Celda de Cuadrícula (Grid Cell)**: Cada espacio en la cuadrícula formado por la intersección de una fila y una columna se conoce como una celda de cuadrícula. Los elementos secundarios (hijos) de un contenedor de cuadrícula se colocan en estas celdas.

4. **Áreas de la Cuadrícula (Grid Areas)**: CSS Grid permite definir áreas en la cuadrícula que contienen múltiples celdas. Esto simplifica la organización de elementos en áreas específicas de la página. Se puede hacer mediante la propiedad `grid-template-areas`.

5. **Rejillas Implícitas (Implicit Grids)**: Si los elementos secundarios de la cuadrícula no caben dentro de las filas o columnas definidas explícitamente, se crean filas y columnas adicionales automáticamente para acomodarlos. Estas filas y columnas se llaman rejillas implícitas y su tamaño se controla con las propiedades `grid-auto-rows` y `grid-auto-columns`.

6. **Alineación de Cuadrícula (Grid Alignment)**: Se utiliza para alinear elementos dentro de las celdas de la cuadrícula, así como para alinear la cuadrícula en sí dentro de su contenedor. Las propiedades `justify-items`, `align-items`, `justify-content` y `align-content` se utilizan para este propósito.

7. **Superposición de Cuadrículas (Grid Overlay)**: CSS Grid Layout permite superponer múltiples cuadrículas dentro del mismo contenedor, lo que brinda una gran flexibilidad para organizar elementos de manera precisa.

CSS Grid Layout es una herramienta poderosa para crear diseños complejos y responsivos con facilidad. Al igual que Flexbox, es ampliamente compatible con la mayoría de los navegadores modernos y ofrece una solución sólida para el diseño web.

## Responsive design

El diseño web responsivo es una técnica de diseño y desarrollo que permite que un sitio web se adapte y se vea bien en una variedad de dispositivos y tamaños de pantalla, desde computadoras de escritorio hasta teléfonos inteligentes y tabletas. La idea fundamental detrás del diseño responsivo es crear una experiencia de usuario óptima independientemente del dispositivo que se esté utilizando para acceder al sitio web.

Aquí hay algunas prácticas comunes asociadas con el diseño web responsivo:

1. **Diseño Fluid (Fluid Design)**: En lugar de utilizar dimensiones fijas para los elementos en un sitio web, se utilizan unidades relativas como porcentajes o `em` para especificar tamaños. Esto permite que los elementos se redimensionen automáticamente según el tamaño de la pantalla del dispositivo.

2. **Media Queries**: Las media queries son reglas de CSS que se utilizan para aplicar estilos específicos basados en las características del dispositivo, como el ancho de la pantalla, la altura de la pantalla, la orientación, etc. Se pueden utilizar para cambiar el diseño, el tamaño del texto, la visibilidad de elementos y otras propiedades según las necesidades del dispositivo.

3. **Imágenes Flexibles (Flexible Images)**: Se utilizan imágenes flexibles que pueden cambiar de tamaño de manera dinámica según el ancho de la ventana del navegador. Esto se logra generalmente estableciendo el ancho máximo de la imagen en un porcentaje o utilizando la propiedad `max-width`.

4. **Grids y Flexbox**: El uso de sistemas de diseño como CSS Grid Layout y Flexbox permite crear diseños flexibles que pueden adaptarse fácilmente a diferentes tamaños de pantalla y dispositivos.

5. **Viewport Meta Tag**: Se utiliza la etiqueta `viewport` en el encabezado HTML para controlar cómo se escala y se muestra el contenido en dispositivos móviles. Por ejemplo, especificar `width=device-width` asegura que el ancho del contenido se ajuste al ancho de la pantalla del dispositivo.

6. **Diseño de Contenido Priorizado (Content Prioritization)**: En el diseño responsivo, es importante priorizar el contenido más relevante y hacerlo accesible de manera clara y concisa, especialmente en dispositivos móviles donde el espacio es limitado.

7. **Pruebas en Dispositivos Reales y Emuladores**: Es crucial probar el sitio web en una variedad de dispositivos reales y utilizar emuladores para asegurarse de que se vea y funcione bien en diferentes plataformas y tamaños de pantalla.

El diseño web responsivo se ha convertido en un estándar en la industria del desarrollo web debido a la creciente diversidad de dispositivos y tamaños de pantalla. Al adoptar prácticas de diseño responsivo, los sitios web pueden proporcionar una experiencia de usuario consistente y de alta calidad en cualquier dispositivo.

## Links de materiales

- [CSSReference](https://cssreference.io/)
- [juego de flex](https://flexboxfroggy.com/)
