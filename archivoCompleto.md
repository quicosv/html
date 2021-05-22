---
title: Archivo HTML completo
---

Con idea de que su aprendizaje de HTML fuese lo más sencillo posible, hasta ahora se han ido presentando las distintas etiquetas que se podían aprender de forma individualy cuyo efecto se podía ver reflejado inmediatamente en la pantalla del navegador.

Sin embargo, esto no es un archivo HTML completo, ya que, además de aquello que se ve en la pantalla, debemos comunicar una serie de datos al navegador, como puede ser la versión de HTML que estamos utilizando, el título de la ventana, lo que debe hacer para que los acentos se representen correctamente o una descripción para que los buscadores encuentren más fácilmente la página.

A continuación se presenta un archivo completo y luego se explica el código.

```
<!DOCTYPE html>
<html lang="es">
<head>
<title>Título de la ventana</title>
<meta charset="utf-8" />
</head>
<body>
<p>Texto de la página.</p>
</body>
</html>
```

Todo documento html empieza con una línea en la que determinamos cuál es la versión que estamos utilizando. Se compone de un signo de menor que, uno de admiración y la palabra `DOCTYPE+ (<span lang="en">document type</span) escrita en mayúscula. Separado por un espacio escribimos `html`y cerramos con el signo de mayor que. Con esto le decimos al navegador que queremos usar la última versión.

A partir de aquí abrimos la etiqueta `html`y aprovechamos para indicar con el atributo `lang` que la página está escrita en español. La etiqueta `html` se cierra al final del documento. Esta etiqueta contendrá dos secciones: la cabecera (head) y el cuerpo (body).

Dentro de la etiqueta `head` van todos los datos que queremos comunicar al navegador sobre cómo debe mostrarse la página. En este caso hemos usado la etiqueta `title` para establecer el título que debe aparecer en la ventana del navegador. Además, hemos establecido que la codificación de caracteres será UTF-8 con esta etiqueta:

```
<meta charset="utf-8" />
```

Además, si tuviéramos un archivo con el estilo en el que debe visualizarse la página y/o algún programa que deba ejecutar el navegador también deberíamos indicarlo en esta sección.

Finalmente, tenemos la sección `body`, en la que dispondremos lo que se mostrará en la pantalla, es decir, el contenido propiamente dicho de la página. Aquí es donde van todas las etiquetas parendidas hasta ahora.