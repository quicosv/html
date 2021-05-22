---
title: Legibilidad
---

Cuando el navegador interpreta el código html lo único que le importa es el punto en el que abrimos y cerramos cada etiqueta. De hecho, si hay varios espacios consecutivos o varios saltos de línea, éstos serán tratados como un único espacio.

Por lo tanto, si queremos que el navegador muestre el texto en otro párrafo (separado del anterior por una línea en blanco) debemos cerrar el párrafo actual y abrir uno nuevo.

```
<p>Esto es un párrafo.</p><p>Esto es otro párrafo distinto.</p>
```

El ejemplo anterior funciona correctamente y el navegador crea dos párrafos, pero no es aconsejable. La razón es que debemos pensar que quizás necesitemos modificar el código (para ampliar el contenido, actualizarlo o para corregir errores). En esta versión es muy difícil encontrar donde termina el primer párrafo y dónde empieza el segundo. Por lo tanto, deberíamos separar cada párrafo con la cantidad de saltos de línea que nos convenga, aprovechando que éstos serán ignorados por el navegador que, recordemos, sólo se fija en las etiquetas. Esto es lo que se conoce como legibilidad del código. Por lo tanto, nuestro código sería mucho más legible de esta manera:

```
<p>Esto es un párrafo.</p>
<p>Esto es otro párrafo distinto.</p>
```