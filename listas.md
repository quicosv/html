---
title: Listas
---

Las listas en HTML son un poquito más complejas de lo visto hasta ahora, ya que requiere anidar distintas etiquetas, es decir, habrá que hacer que unas etiquetas estén dentro de otras. El procedimiento es el siguiente:

1. Abrimos la lista.
1. Cada elemento se abre, se escribe lo que contiene y se cierra.
1. Finalmente, se cierra la lista.


Disponemos de tres tipos de listas: las ordenadas, las no ordenadas y las de definición.

## Listas ordenadas

Como su propio nombre sugiere, estas listas generan un orden. El navegador antepondrá un número y un punto a cada una de ellas. La etiqueta para la lista es `ol` (<span lang="en">ordered list</span>) y la de cada uno de sus elementos será `li` (<span lang="en">list item</span>). A continuación veremos el código que crea una de estas listas.

```
<ol>
<li>El primer elemento.</li>
<li>El segundo elemento.</li>
<li>El último elemento.</li>
</ol>
```

Aquí hay varias cosas a destacar:

- Se ve que iniciamos y terminamos la lista y que dentro de ella cada elemento tiene su etiqueta.
- En ningún momento indicamos el número de elemento por el que vamos. El navegador ya se encarga de eso.


## Listas no ordenadas


Sólo existen dos diferencias entre las listas ordenadas y las no ordenadas.

1. La etiqueta para la lista es `ul` (<span lang="en">unordered list).
- El navegador antepone un símbolo en vez de un número a cada elemento.


A continuación se presenta un código de ejemplo.

```
<ul>
<li>Una cosa.</li>
<li>Otra cosa.</li>
<li>Y otra cosa.</li>
</ul>
```


## Listas de definición

Este tipo de listas sirven para relacionar un término con su definición. Aquí intervienen tres etiquetas:

- `dl` (<span lang="en">definition list</span) es la etiqueta de la lista.
- `dt` (<span lang="en">definition term</span) es la etiqueta para expresar el término.
- `dd` (<span lang="en">definition definition</span>) es la etiqueta que recoge la definición.


A continuación un código de ejemplo:

```
<dl>
<dt>Triángulo.</dt>
<dd>Tiene tres lados.</dd>
<dt>Cuadrado.</dt>
<dd>Tiene cuatro lados.</dd>
<dt>Pentágono.</dt>
<dd>Tiene cinco lados.</dd>
</dl>
```