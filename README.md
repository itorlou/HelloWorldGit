# **CABECERAS**

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# **UNDERLINES**

Underline 1
-------
Underline 2
========

# **FORMATOS DE ÉNFASIS**

- Formato *itálico* de primera forma. (con asteriscos *)
- Formato _itálico_ de segunda forma. (con barras bajas _)
- Formato **Strong** de primera forma. (con asteriscos **)
- Formato __Strong__ de segunda forma. (con con barras bajas __)
- Formato ~~tachado~~. (con dos virgulillas ~~)
- Podemos *__Combinar__* *~~Formatos~~*.

# **LISTAS**

1. Esto es un item de lista con index.
2. Esto es un item de lista con index.
3. Esto es un item de lista con index.
4. Esto es un item de lista con index.

- Esto es un item de lista sin  index.
- Esto es un item de lista sin  index.
- Esto es un item de lista sin  index.
- Esto es un item de lista sin  index.

# LINKS

Esto es un <a href="http://google.com">enlace</a> mezclando markdown con html.

Esto es un [enlace](http://google.com) de markdown.

Esto es un link al [index](index.html)

Esto es un link a la [parte superior del readme](**CABECERAS**)

# IMAGENES

![Logo github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# CODE SNIPPETS

Codigo en JSON  https://highlightjs.org/static/demo/
 ```JSON 
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
```` 
Código en JavaScript 
```JavaScript 
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