my css

task 4. Variables for storing certain font types

se utiliza el selector :root para seleccionar el elemento raíz, que generalmente es el elemento <html>. Dentro de este selector, se definen dos variables personalizadas de font-family: --font-family-base y --font-family-title. Estas variables almacenan la lista de fuentes en el orden de preferencia deseado.

Luego, se aplica la variable --font-family-base al selector body. Esto establece la propiedad font-family del elemento body con el valor de la variable --font-family-base, lo que significa que se utilizará la lista de fuentes definida en --font-family-base para el texto del cuerpo del documento.

Además, se utiliza el selector h1, h2, h3, h4, h5 y h6 para seleccionar los seis niveles de encabezados de sección. Estos encabezados se colocan antes de la declaración de los enlaces en el código CSS. A estos encabezados se les aplica la variable --font-family-title, lo que significa que su propiedad font-family se establecerá en el valor de la variable --font-family-title. Esto asegura que los encabezados de sección utilicen la lista de fuentes definida en --font-family-title.

La ventaja de utilizar variables CSS es que puedes actualizar fácilmente las listas de fuentes en un solo lugar (las variables personalizadas en :root) y todos los elementos que hacen uso de esas variables se actualizarán automáticamente en consecuencia


task 6. Variables for the font-weight

 hemos añadido dos nuevas propiedades personalizadas en el selector :root. Estas propiedades son --font-weight-regular y --font-weight-bold. Estas propiedades almacenan los valores de peso de fuente (font-weight), donde --font-weight-regular está definido como 400 y --font-weight-bold está definido como 700.

Luego, hemos aplicado estas propiedades personalizadas en las reglas de estilo. En el selector body, hemos añadido font-weight: var(--font-weight-regular);, lo que significa que el peso de fuente para el texto del cuerpo será el valor de --font-weight-regular, es decir, 400, que es el peso de fuente regular.

En los selectores de los encabezados (h1, h2, h3, h4, h5, h6), hemos añadido font-weight: var(--font-weight-bold);, lo que establece el peso de fuente en negrita para los encabezados utilizando el valor de --font-weight-bold, es decir, 700.
