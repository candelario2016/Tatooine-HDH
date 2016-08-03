# MarkDown


### ¿Que es MarkDown?
 MarkDown es un lenguaje de marcado ligero basado originalmente en convenciones existentes en el mercado de los correos Electronico emplea texto plano, procurando que sea legible pero consiguiendo que se convierta en XHTML correctamente.


### Usos de Markdown

Este lenguaje de marcado empleado para crear sitio, que permite formatear el texto facilmente simplemente con los caracteres de Markdown le indicamos al interprete lo necesario para que lo convierta en etiquetas HTML de manera correcta.


### Sintaxis MarkDown

Haciendo uso correcto de los caracteres especiales que nos proporciona Markdown los cuales el interprete cambiara por etiquetas HTML para visualizacion.

A continuacion se mostrara algunos caracteres que nos proporciona la Sintaxis de Markdown.


- **Encabezados**: Estos se producen colocando un numero determinado de almohadilla '#' antes del  texto correspondiente al nivel de encabezado deseado  y segun la cantidad de signos. HTML ofrece seis niveles.

Código:
~~~
# Esto es una cabecera H1
~~~
Resultado:
# Esto es una cabecera H1
- - -
Código:
~~~
## Esto es una cabecera H2
~~~
Resultado:

## Esto es una cabecera H2
- - -
Código:
~~~
### Esto es una cabecera H3
~~~
Resultado:

### Esto es una cabecera H3
- - -
Código:
~~~
#### Esto es una cabecera H4
~~~
Resultado:

#### Esto es una cabecera H4
- - -
Código:
~~~
##### Esto es una cabecera H5
~~~
Resultado:

##### Esto es una cabecera H5
- - -
Código:
~~~
###### Esto es una cabecera H6
~~~
Resultado:

###### Esto es una cabecera H6
- - -

- **Formato**: Este es el formato basico del texto, como las **Negritas** y *Cursivas*

Código:
~~~
*Texto en Cursivas*
~~~
Resultado:

*Texto en Cursivas*
- - -
Código:
~~~
**Texto en Negritas**
~~~
Resultado:

**Texto en Negritas**
- - -
Codigo.
~~~
_Esto también es cursiva_
~~~
Resultado
_Esto también es cursiva_
---
Codigo
~~~
***Esto es negrita y cursiva***
~~~
Resultado:
***Esto es negrita y cursiva***
---
Codigo:
~~~
___Esto también es negrita y cursiva___
~~~
Resultado:
___Esto también es negrita y cursiva___

se puede ultilizar de distinta manera tanto con el asterisco * como el guión bajo _ siempre y cuando no se mezclen y lo que determina el formato es el número de ellos antes y después del bloque de texto a formatear. Uno es cursiva, dos es negrita, y tres ambas a la vez, así de facil.

- **Enlaces**: Hay dos maneras de crear un enlace.

Código:
~~~
[Google](https://google.com "Titulo del enlace")
~~~
Resultado:

[Google](https://google.com "Titulo del enlace")
- - -
Codigo:
~~~
[Google](https://google.com)
~~~
Resultado:
[Google](https://google.com)
- - -
Cóodigo:
~~~
[Google][1], [Facebook][2], [YouTube][3]

 [1]: https://google.com
 [2]: https://facebook.com "Facebook"
 [3]: https://www.youtube.com/
~~~
Resultado:

[Google][1], [Facebook][2], [YouTube][3]

 [1]: https://google.com
 [2]: https://facebook.com "Facebook"
 [3]: https://www.youtube.com/
- - -

- **Imágenes**:

Código:
~~~
![Texto alternativo](http://kirkstrobeck.github.io/whatismarkdown.com/img/markdown.png "titulo")
~~~
Resultado:

![Texto alternativo](http://kirkstrobeck.github.io/whatismarkdown.com/img/markdown.png "titulo")
- - -
Código:
~~~
![Texto alternativo][1]  ![Texto alternativo][2]

 [1]:http://kirkstrobeck.github.io/whatismarkdown.com/img/markdown.png
 [2]: http://static.gatespace.jp/wp-content/uploads/2014/07/markdown1.gif "Markdown"
~~~
Resultado:

![Texto alternativo][1]  ![Texto alternativo][2]

 [1]:https://norfipc.com/fotos/cristianas/sombras-no-pueden-tapar-fe-dios.jpeg
 [2]:http://www.tusimagenesbonitas.com/wp-content/uploads/2014/08/Reflexiones-de-Vida-para-Facebook.jpg "La Vida"
 - - -

 - **LIstas**: Markdown permite crear dos tipos de listas, numeradas o listas con puntos.

 Código:

~~~
Esto es una lista ordenada

1. Primer elemento
2. Segundo elemento
3. Tercer elemento
~~~
Resultado:

Esto es una lista Enumerada

1. Primer elemento
2. Segundo elemento
3. Tercer elemento
- - -

Código:
~~~
Esto es una lista con puntos.

- Primer elemento
- Segundo elemento
- Tercer elemento
~~~
Resultado:

Esto es una lista con puntos.

- Primer elemento
- Segundo elemento
- Tercer elemento
