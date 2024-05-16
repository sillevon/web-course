# CSS: Hojas de Estilo en Cascada

CSS, que significa Hojas de Estilo en Cascada en inglés, es un lenguaje utilizado para describir la presentación de un documento escrito en HTML (Lenguaje de Marcado de Hipertexto). HTML se utiliza para estructurar el contenido en la web, mientras que CSS se utiliza para dar estilo y formato a ese contenido. Piensa en HTML como el esqueleto de una página web, y CSS como la piel que le da estilo y belleza.

## ¿Qué hace CSS?

CSS permite a los desarrolladores web controlar la apariencia de las páginas web. Les permite especificar los colores, fuentes, espaciado y diseño de los elementos HTML. Al utilizar CSS, los desarrolladores pueden crear diseños visualmente atractivos y consistentes en diferentes páginas web o incluso sitios web enteros.

## ¿Cómo funciona CSS?

CSS funciona al dirigirse a los elementos HTML y aplicar reglas de estilo a ellos. Estas reglas de estilo están escritas en la sintaxis de CSS y definen cómo se deben mostrar los elementos.

### Ejemplo:

```css
/* Este es un comentario en CSS */
body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
}

h1 {
  color: blue;
  text-align: center;
}

p {
  font-size: 16px;
  line-height: 1.5;
}
```

En este ejemplo:

- `body`, `h1` y `p` son elementos HTML que se están seleccionando.
- `{ }` encierra las reglas de estilo para cada elemento.
- Dentro de las llaves `{ }`, tienes pares de propiedad-valor separados por dos puntos `:`. Estos pares definen cómo se debe estilar el elemento.
- Cada regla termina con un punto y coma `;`.

## Selectores

Los selectores son patrones utilizados para seleccionar los elementos que deseas estilar. Hay varios tipos de selectores en CSS:

- **Selectores de elemento**: Seleccionan elementos HTML específicos. (por ejemplo, `p`, `h1`, `div`)
- **Selectores de clase**: Seleccionan elementos con un atributo de clase específico. (por ejemplo, `.contenedor`, `.btn`)
- **Selectores de ID**: Seleccionan un único elemento con un atributo de ID específico. (por ejemplo, `#encabezado`, `#barra-lateral`)
- **Selectores de atributo**: Seleccionan elementos en función de sus atributos. (por ejemplo, `[type="text"]`, `[href^="https://"]`)
- **Pseudo-clases y pseudo-elementos**: Seleccionan elementos en estados especiales o partes de elementos. (por ejemplo, `:hover`, `::before`, `::after`)

## Cascada y Especificidad

CSS se llama Hojas de Estilo en Cascada porque los estilos pueden cascarse, lo que significa que múltiples reglas de estilo pueden aplicarse al mismo elemento. El orden de precedencia se determina por la especificidad y el orden de aparición en la hoja de estilos.

- **Especificidad**: Es un peso que determina qué regla se aplica cuando múltiples reglas tienen selectores conflictivos. Se calcula en función del tipo de selector utilizado y su combinación. Generalmente, las reglas más específicas anulan a las menos específicas.
- **Orden de Aparición**: Si dos reglas tienen la misma especificidad, la que aparece más tarde en la hoja de estilos tiene prioridad.

## CSS Externo, Interno e Inline

CSS se puede aplicar a documentos HTML de tres formas:

- **CSS Externo**: El CSS se escribe en un archivo separado con la extensión `.css` y se enlaza al documento HTML mediante el elemento `<link>`.
- **CSS Interno**: El CSS se escribe dentro de un elemento `<style>` en la sección `<head>` del documento HTML.
- **CSS Inline**: El CSS se aplica directamente a un elemento HTML utilizando el atributo `style`.

## Conclusión

CSS es un lenguaje poderoso utilizado para dar estilo a documentos HTML, lo que hace que las páginas web sean visualmente atractivas y mejoren la experiencia del usuario. Proporciona control sobre la disposición, tipografía, colores y otros aspectos visuales del diseño web. Al comprender CSS, los desarrolladores web pueden crear sitios web hermosos y receptivos que involucren efectivamente a los usuarios.
