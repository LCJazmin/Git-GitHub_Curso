Soy texto dentro de un README.MD para GitHub
# CABECERAS
# cabecera H1 
## cabecera H2
### cabecera H3
#### cabecera H4
##### cabecera H5
###### cabecera H6

# UNDERLINE
Underline 1. Se escribe un guión debajo del texto para generar un formato diferente del texto. 
-

Underline 2. Se escribe signo igual debajo del texto para generar un forato diferente del texto, el formato es similar a una cabecera H1.
=

# FORMATO DE TEXTO
*Texto en formato itálica, se pone el texto/palabra/caracter entre asteriscos. Forma 1.*

_Texto en formato itálica, se pone el texto/palabra/caracter entre guión bajo. Forma 2._

**Texto en formato bold o strong, se pone el texto/palabra/caracter entre dos asteristicos. Forma 1.**

__Texto en formato bold o strong, se pone el texto/palabra/caracter entre dos guiones bajos. Forma 2.__

~~Texto en formato tachado, se pone el texto/palabra/caracter entre dos guiones bajos. Forma 2.~~

Podemos tener todas las formas de formato en un solo texto, por ejemplo, tenemos formato *italica*, formato **bold** y formato ~~tachado~~.

# LISTAS
Para una lista ordenada, similar a ol en HTML
1. Este es un item.
2. Este es un item.
3. Este es un item.

Para una lista desordenada,  similar a ul en HTML
- Estes es un item.
- Este es un item.
- Este es un item. 

Para listas ordenadas y desordenadas combinadas
1. Este es un item primario ol
- Estes es un item primario ul
    - Este es un item secundario ul
        1. Estes es un item secundario ol
            1. Estes es un item tercerario ol
    - Este es un item secundario ul
- Este es un item primario ul

# LINKS
 
<a href="https://www.google.com.mx/">Este es un LINK a GOOGLE en HTML</a>

[Descripcion](URL de la pagina)

[Este es un LINK a GOOGLE en Markdown ](https://www.google.com.mx/)

[Este es un LINK a index del proyecto](index.html)


# IMAGENES
![Descrpcion](URL de la imagen)
![Esta es una imagen con Markdowm](https://image.flaticon.com/icons/png/512/25/25231.png)

# CODE SNIPPETS
Código JSON
``` JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```  
Código Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```
Código Markdown
```Markdowm
# hello world

you can write text [with links](http://example.com) inline or [link references][1].

* one _thing_ has *em*phasis
* two __things__ are **bold**

[1]: http://example.com

---

hello world
===========

<this_is inline="xml"></this_is>

> markdown is so cool

    so are code segments

1. one thing (yeah!)
2. two thing `i can write code`, and `more` wipee!
```
Visitar https://highlightjs.org/static/demo/ para conocer más sobre como adjuntar códigos a README.MD

# TABLAS
Codigo para generar una tabla
```
| ColumnaA | ColumnaB | ColumnaC | ColumnaD |
|----------|----------|----------|----------|
| CampoA1 | CampoB1 | CampoC1 | CampoD1 |
| CampoA2 | CAmpoB2 | CampoC2 | CampoD2 |
| CampoA3 | CampoB3 | CampoC3 | CampoD3 |
```
Resultado
| ColumnaA | ColumnaB | ColumnaC | ColumnaD |
|----------|----------|----------|----------|
| CampoA1 | CampoB1 | CampoC1 | CampoD1 |
| CampoA2 | CAmpoB2 | CampoC2 | CampoD2 |
| CampoA3 | CampoB3 | CampoC3 | CampoD3 |


# CITAS
Asi se crea una cita en Markdown
```
> Esto es el contenido de la cita
```
Resultado
S
> Esto es el contenido de la cita mas

# LINEAS DIVISORAS
Este es un texto, linea divisora creada por 3 asteriscos (***) debajo del texto
***
Este es un texto, linea divisora creada por 3 guiones medios (---) debajo del texto mas un enter. 

---
Este es un texto, linea divisora creada por 3 guiones bajos (___) debajo del texto
___ 



