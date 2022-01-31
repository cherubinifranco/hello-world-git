# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
---

Underline 2
===


# Formatos de enfasis
- Formato *italica* de la primer forma.
- Formato _italica_ de la segunda forma.
- Formato **bold o strong** de la primer forma.
- Formato __bold o strong__ de la primer forma.
- Formato ~~tachado~~.

Tambien se pueden ~~_**combinar formatos**_~~.


# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
4. Esto es un item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="www.google.com">Esto es un link HTML</a>
- [Esto es un link en MARKDOWN](www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code Snippets
Codigo en JSON
```JSON
    [{
        "title": "apples",
        "count": [1200, 2000],
        "description": {"text": "...", "sensitive": false}
    }]
```

Codigo en Javascript
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