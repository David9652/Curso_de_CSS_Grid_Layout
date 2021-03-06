# Información Útil

* **CSS Grid Layout** es un módulo de maquetación CSS con un **sistema basado en rejillas bidimensionales** (filas y columnas) y es soportado por todos los navegadores.

## Componentes Principales

* **Grid Container** &rarr; Va a ser el elemento padre que va a tener puesto un nuevo tipo de display (grid). Nos permite colocar otras propiedades para manipular nuestro layaout.

* **Grid Item** &rarr; Son nuestro componentes, contenido, lo que vamos a manejar. Nuestras filas o columnas que vamos a mover a nuestro gusto. Son hijos directos de grid.

* **Grid Line** &rarr; Lineas divisorias horizontales y verticales.

* **Grid Track** &rarr; Espacio entre dos líneas adyacentes. Filas y columnas.

* **Grid Cell** &rarr; Celdas, espacio en dos filas adyacentes y 2 columnas adyacentes.

* **Grid Area** &rarr; Espacio rodeado por 4 grid lines.

* **Grid explícito (explicit grid)** &rarr; Es cuando nosotros definimos el número de filas o columnas.

* **Grid implícito (implicit grid)** &rarr; Es cuando tenemos filas o columnas que no definimos pero son parte de nuestro grid.

* **grid-column-gap: valor;** &rarr; Definir espaciado entre columnas.

* **grid-row-gap: valor;** &rarr; Definir espaciado entre filas.

* **grid-template-areas** &rarr; Definimos los nombres de las áreas de contenido.

* **grid-area** &rarr; Asigna a un **item** el nombre de área que creamos con **grid-template-areas**, haciéndole referencia para poder utilizarlo. Solamente aplica para hijos directos.

* **grid-column-start & grid-column-end** &rarr; Definir el tamaño de columnas dentro de un grid (líneas).
	* **grid-column: inicio / final;** &rarr; Sintáxis resumida
	* Para usar por espacios &rarr; **span** #
	* Para usar el espacio de toda la columna usamos **-1** al final.

* **grid-auto-flow: column** &rarr; Cambiar el flujo automático de mi grid (row por defecto).4

* **grid-auto-columns & grid-auto-rows** &rarr; Asignar el valor por defecto del espacio de las columnas o filas que no han sido asignadas (implícitas)

* **justify-items & align-items** &rarr; Alineación horizontal y vertical, respectivamente (contenedor padre). Los valores que toman por defecto es **stretch**, el cual hace que tomen todo el valor asignado en la fila o columna.

* **justify-self & align-self** &rarr; Alineación horizontal y vertical, respectivamente (contenedor hijo). Los valores que toman por defecto es **stretch**, el cual hace que tomen todo el valor asignado en la fila o columna.

* **justify-content & align-content** &rarr; Alineación Horizontal y Vertical de todo el contenedor.
	* **space-around** &rarr; Los items tienen el mismo espacio a su alrededor.
	* **space-evenly** &rarr; Hay un espacio más homogéneo entre items.
	* **space-between** &rarr; El primer item al inicio, el último al final.

* **fr (Nueva Unidad de medida)** &rarr; **fr** distrubuye el espacio disponible en formas iguales.

* **Auto** es lo mismo que **fr** pero al mismo tiempo no lo es, porque auto distribuye el espaciado que tiene la columna pero con referencia a su contenido.

## Funciones

* **repeat(cantidad, valor)** &rarr; Usa el mismo valor varias veces.

* **minmax(min, max)** &rarr; Agrega un valor mínimo y máximo para el tamaño.

**NOTA** &rarr; Flexbox para diseños unidimensionales (componentes) y CSS Grid para diseños bidimensionales (estructura).

## Links Importantes

* [Resumen Curso](https://github.com/yomar-dev/css-grid "Resumen Curso").
* [W3C CSS Grid Layout](https://www.w3.org/TR/css-grid-1/ "W3C CSS Grid Layout").
* [Firefox CSS Grid Layout](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout "Firefox CSS Grid Layout").
* [Comparación CSS Grid y Boostrap](https://platzi.com/tutoriales/1229-css-grid-layout/2071-por-que-css-grid-es-mejor-que-bootstrap-para-crear-disenos/ "Comparación CSS Grid y Boostrap").
* [Más sobre CSS Grid Firefox](https://mozilladevelopers.github.io/playground/css-grid/ "Más sobre CSS Grid Firefox").
* [EMMET para Agilizar Escritura de Código](https://docs.emmet.io/cheat-sheet/ "EMMET para Agilizar Escritura de Código").
* [Más sobre EMMET](https://code.visualstudio.com/docs/editor/emmet "Más sobre EMMET").
* [Explicación CSS Grids](https://css-tricks.com/snippets/css/complete-guide-grid/ "Explicación CSS Grids").
* [Explicit Grid & Implicit Grid](https://www.quackit.com/css/grid/tutorial/explicit_vs_implicit_grid.cfm "Explicit Grid & Implicit Grid").
* Post CSS instalar Subgrid (Hereda la definición de Filas y Columnas del padre).
* [Selectores CSS](https://dazzet.co/simbolos-css-en-hojas-estilo-html/ "Selectores CSS").
* [Unidad fr CSS](https://css-tricks.com/introduction-fr-css-unit/ "Unidad fr CSS").
* [Página para practicar CSS-Grid](http://cssgridgarden.com/#es "Página para practicar CSS-Grid").
* [Unidades VH y VW en CSS](https://devcode.la/tutoriales/unidades-vh-vw-css/ "Unidades VH y VW en CSS").
* [Imágenes 1](https://pixabay.com/ "Imágenes 1").
* [Imágenes 2](https://www.pexels.com/ "Imágenes 2").
* [Imágenes 3](https://pikwizard.com/ "Imágenes 3").
* [Flexbox Vs CSS Grids](https://platzi.com/blog/flexbox-vs-css-grid-cual-es-la-diferencia/ "Flexbox Vs CSS Grids").
* [Extensión VSCode Data Fake](https://marketplace.visualstudio.com/items?itemName=deerawan.vscode-faker "Extensión VSCode Data Fake").
* [Instagram Layout Ejemplo](https://jjonatansosa.github.io/instagram-layout/index.html# "Instagram Layout Ejemplo").
* [Iconos Google](https://material.io/tools/icons/?style=baseline "Iconos Google").
* [Uso Iconos Google](https://www.w3schools.com/icons/google_icons_intro.asp "Uso Iconos Google"). 
* [Iconos Awesome](https://fontawesome.com/ "Iconos Awesome").
* [Grid-auto-flow - Layout Masonry (Pinterest)](https://scrimba.com/p/pWqLHa/cBq3PsP "Grid-auto-flow - Layout Masonry (Pinterest)").
* [AutoFill Vs AutoFit CSS Grid](https://css-tricks.com/auto-sizing-columns-css-grid-auto-fill-vs-auto-fit/ "AutoFill Vs AutoFit CSS Grid").
* [Portafolio Front-end](http://leandrovidela.com/ "Portafolio Front-end").