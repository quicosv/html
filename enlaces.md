---
title: Enlaces
---

Los enlaces sirven para que el usuario se desplace a otra página de internet, visualice un documento, se descargue un archivo o envíe un correo electrónico. Con su explicación introduciremos un nuevo concepto de HTML: los atributos.

Los atributos recogen cierta información que puede necesitar el navegador para interpretar las etiquetas. Se establecen cuando escribimos la etiqueta de apertura, entre el nombre de la etiqueta y el signo de mayor que. Deberemos escribir el nombre del atributo, un signo igual y el valor que debe tener entre comillas. Por lo tanto, una etiqueta con un atributo quedaría así:

```
<etiqueta atributo="valor">Texto.</etiqueta>
```

Los enlaces se incluyen utilizando la etiqueta a. Habrá que establecer el atributo `href` con el lugar al que apunte. Lo que debe haber entre la apertura y el cierre de la etiqueta es el texto en el que se hará click para activarlo y deberá describir por sí sólo el lugar al que apunta. Por tanto, la etiqueta quedaría de esta forma:

```
<a href="destino">Texto para hacer click.</a>
```

A continuación se dan unas ideas sobre los posibles valores que admite el atributo href.

- Si el destino es un fichero para visualizar o descargar (como otro archivo html de nuestra página, un documento de word o pdf o un programa para descargar) se deberá incluir la ruta y el nombre del fichero. Lo más fácil es que el fichero y el archivo en el que esté el enlace estén en la misma carpeta, de manera que con el nombre es suficiente.
- Si el enlace debe apuntar a otra página de internet se deberá indicar la dirección completa empezando por http o https según corresponda.
- Si el enlace es a una dirección de correo electrónico se deberá escribir la palabra «mailto», el signo de dos puntos y la dirección de correo electrónico.


A continuación se expone el código de ejemplo para cada una de estas situaciones.

```
<a href="otrapagina.html">Visite otra página.</a>
<a href="programa.zip">Descargue el programa.</a>
<a href="http://ejemplo.com">Visite la página ejemplo.com.</a>
<a href="mailto:info@ejemplo.com">Contacte por correo electrónico.</a>
```