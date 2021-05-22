---
title: Imágenes
---

La etiqueta que sirve para insertar las imágenes es img. Todos los parámetros necesarios deben indicarse a través de atributos, por lo que esta etiqueta se abre y se cierra en el mismo momento. Para ello, sólo hay que escribir una barra antes del signo de mayor que. A continuación se listan los atributos de la etiqueta con los valores que pueden recibir.

\ Atributo | Descripción \
| --- | --- |
| `src` | Ruta y nombre del archivo de la imagen. |
| `width` | Ancho de la imagen. Normalmente se especifica en pixels. |
| `height` | Altura de la imagen. Normalmente se especifica en pixels. |
| `alt` | Descripción de la imagen. Será lo que lean los lectores de pantalla al posicionar el cursor allí o lo que mostrarán aquellos navegadores que sólo sean capaces de mostrar texto. |


Por lo tanto, si tuviéramos una imagen en un archivo llamado «foto.jpg» y quisiéramos que al visualizarse en el navegador ocupara 200 pixels de alto y 100 de ancho, el código para insertar esta imagen sería:

```
<img src="foto.jpg" width="100" height="200" alt="Descripción de la foto" />
```