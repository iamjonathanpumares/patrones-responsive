# Patrones de diseño Responsive

## Tiny Tweaks

Es el patrón más simple y sencillo de implementar de todos. Se basa en una sóla columna para el contenido.

Sus cambios son básicamente que dependiendo del tamaño de la pantalla, se amplían los espaciados y el tamaño de fuente.

Es muy utilizado en sitios con mucho contenido escrito, así mejoran la experiencia de lectura.

## Colum Drop

Este patrón consiste en que cada bloque de contenido, que en un smartphone vemos en filas, vaya formando columnas según vaya siendo más grande la pantalla del dispositivo.

Tendremos un primer breakpoint donde la segunda fila pasa a ser columna, pero ocupando la primera posición, habitualmente para un menú de navegación.

El contenido que aparecía en primer lugar en la versión móvil, pasa a ocupar la segunda columna en el primer corte.
Tendremos un segundo punto de corte donde la última fila se convierte en columna también.

## Mostly Fluid

Este patrón consiste en tener una grilla o Grid de tamaño flexible.

Cuando estamos en un smartphone todo forma una única columna, y en varias filas quedan colocados los distintos bloques.

Según vaya creciendo la pantalla, los distintos bloques se agrupan ocupando toda la pantalla disponible.

En pantallas más grandes, el diseño es el mismo pero queda agrupado dentro de un contenedor que queda centrado en la página con un tamaño fijo de ancho.

## Layout Shifter

Este es uno de los patrones más complejos. Consiste en mover los bloques de contenido cambiando totalmente el Layout, de ahí el nombre del patrón.

Gracias a Flexbox, estos cambios podemos realizarlos con mayor facilidad.

## Off Canvas

El patrón más complejo de implementar pero uno de los más utilizados, sobre todo en aplicaciones móviles.

Este patrón esconde contenido en la pantalla y únicamente es visible si realizamos un determinado gesto. Este contenido oculto normalmente es un menú de navegación. Cuando la pantalla es más ancha, este contenido se hace visible.