# **DAMOS EL CURSO POR FINALIZADO**

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

# TABLAS

[Enlace a la docu de git](https://docs.github.com/es/github/writing-on-github/organizing-information-with-tables)

| Comando | Descripción |
| --- | --- |
| git status | Enumera todos los archivos nuevos o modificados |
| git diff | Muestra las diferencias de archivo que no han sido preparadas |


# CITAS 

Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto fuera de la cita anterior.
> Esto es otra cita

# HR (Líneas horizontales)

Esto es un texto que será dividido por un hr.

---

Esto es un texto que está debajo divido por guiones

***

Dividido por asteriscos

___

Dividido por barras bajas.

# SALTOS DE LÍNEA

Párrafo 1.
 Este párrafo tiene mucho texto

 pero para saltar la línea hay que dar dos saltos de carro en el editor.
