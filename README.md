# Markdown

Markdown es un lenguaje de marcado y una forma sencilla de agregar formato a textos web. Con formato nos referimos a itálicas, negritas, listas, y demás. Markdown fue creado originalmente por John Gruber, con ayuda de Aaron Swartz, con el propósito de crear un texto plano fácil de escribir y fácil de leer, y que pudiera convertirse de forma sencilla y válida a XHTML.

## Tabla de contenido

- [Insertar HN](#insertar-hn).
- [Cursivas](#cursivas).
- [Negrilla](#negrilla).
- [Viñetas para tablas de contenido](#vinetas).
- [insertar imágenes](#insertar-imagenes).
- [Insertar enlaces](#insertar-enlaces).
- [Hacer anclaje](#hacer-anclaje).
- [Insertar una línea de código](#insertar-una-linea-de-codigo).
- [Insertar un bloque de código](#insertar-un-bloque-de-codigo).
- [Resaltar el código](#resaltar-el-codigo).
- [Insertar tablas](#insertar-tablas).
- [Otras referencias sobre Markdown](#otras-referencias-sobre-markdown).

### Insertar HN

```plain
# Esto es un H1
## Esto es un H2
### Esto es un H3
#### Esto es un H4

```

### Cursivas

`*Esto es cursiva*`

### Negrilla

`**Esto es negrilla**`

### Vinetas

```plain

- Esto es viñeta 1.
  - Viñeta 1.1 con sangria.
  - Viñeta N.
  
```

### Insertar imagenes

`![texto cualquiera por si no carga la imagen](url completa de la imagen)`

### Insertar enlaces

`[texto a mostrar](url completa)`

### Hacer anclaje

Usar los títulos con la almohadilla `#` y para anclar el título a una tabla de contenido, ponemos lo siguiente:

`[texto a mostrar](#mi-titulo-a-anclar)`

### Insertar una linea de codigo

Encerrar la linea de código entre la tilde al revés ` Código en ASCII: alt96

Ejemplo:

<pre><code>`tu linea de codigo`</code></pre>

### Insertar un bloque de codigo

Encerrar el bloque de código entre tres tildes al revés ``` Código en ASCII: alt96

Ejemplo:

<pre>
		```
		
		//bloque de codigo...
		
		```
</pre>


### Resaltar el codigo

Encerramos el bloque de código con las tres tildes al revés ``` y le ponemos al lado el lenguaje que se está usando, ejemplo:

<pre>
		```java
		
		//bloque de codigo...
		
		```
</pre>

### Insertar tablas

```plain

| TITULO1| TITULO2|
| ----- | ---- |
| CONTENIDO COLUMNA 1 | CONTENIDO COLUMNA 2 |


```

### Otras referencias sobre Markdown:

http://www.genbeta.com/guia-de-inicio/que-es-markdown-para-que-sirve-y-como-usarlo

https://help.github.com/articles/markdown-basics

https://guides.github.com/features/mastering-markdown/

http://bitelia.com/2013/04/que-es-markdown

http://es.wikipedia.org/wiki/Markdown
