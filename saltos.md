---
title: Saltos de línea
---

Dentro del texto que se verá en el navegador todos los saltos de línea se interpretan como si fueran espacios en blanco. Por ejemplo:

```
<p>Esto es un
párrafo
que
hemos partido por donde hemos
querido, pero que el
navegador interpretará.
bien.</p>
```

Si queremos que el navegador cree un salto de línea debremos usar la etiqueta `<br />` que viene del inglés <span lang="en">break.</span> Ésta es una etiqueta un tanto extraña, pero se comprende fácilmente. Como no tiene sentido abrirla, no escribir nada y cerrarla (obviamente el texto irá antes y después del salto de línea) el espacio y la barra que hay antes del signo de mayor que significa que la etiqueta se cierra en el mismo momento en el que la estamos abriendo. Aquí tenemos un párrafo con varios saltos de línea:

```
<p>Línea 1.<br />
Línea 2.<br />
Línea final.</p>
```