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