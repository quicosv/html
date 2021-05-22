---
title: Tablas
---

Si ha ido practicando todo lo visto hasta ahora no le será difícil entender cómo se crean las tablas, ya que todo consiste en ir anidando etiquetas, algunas de las cuales pueden tener propiedades.

En pimer lugar, tenemos la etiqueta de la tabla, que será `table`. Dentro de ella, cada fila llevará su propia etiqueta, que será `tr` (<span lang="en">table row</span>). Por último, dentro de cada fila habrá que definir una etiqueta por cada celda. Lasetiquetas disponibles para ello son:

- `th` (<span lang="en">table heading</span> se utiliza para los encabezados, es decir, la pimera fila y/o la primera columna.
- `td` (<span lang="en">table data</span>) se utiliza para el resto de las celdas.
- Opcionalmente, dentro de la tabla podemos poner la etiqueta caption con una explicación del contenido de la tabla. 


Además, existen un par de atributos que se pueden utilizar para mejorar la presentación y la accesibilidad de la tabla.

- La etiqueta `table` tiene el atributo `border` que permite establecer el grosor de las líneas de división.
- La etiqueta `th` tiene el atributo `scope` que espera el valor «row» si esa celda es cabecera de fila o «col» si la celda es cabecera de columna. Esto hace que los productos de apoyo interpreten mejor la tabla.


A continuación se presenta el código de una tabla que recoge algunos países y capitales de Europa.

```
<table border="1">
<caption>Algunos países y capitales de Europa</caption>
<tr>
<th scope="col">País</th>
<th scope="row">Capital</th>
</tr>
<tr>
<th scope="row">Francia</th>
<td>París</td>
</tr>
<tr>
<th scope="row">Italia</th>
<td>Roma</td>
</tr>
<tr>
<th scope="row">Grecia</th>
<td>Atenas</td>
</tr>
</table>
```