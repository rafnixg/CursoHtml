## Índice 
* [Que es HTML?](#que-es-html)
* [Estructura básica de un documento HTML](#estructura-b%C3%A1sica-de-un-documento-html)
* [Formato básico del texto](#formato-b%C3%A1sico-del-texto)
  * [Títulos](#títulos)
  * [Párrafos](#párrafos)
  * Abreviaturas
  * Direcciones
  * Blockquote
  * Listas
 * Enlaces
   * Anclas
 * Imágenes
 * Tablas

## Que es HTML?

>HTML, siglas de HyperText Markup Language («lenguaje de marcas de hipertexto»), hace referencia al lenguaje de marcado para la elaboración de páginas web. Es un estándar que sirve de referencia para la elaboración de páginas web en sus diferentes versiones, define una estructura básica y un código (denominado código HTML) para la definición de contenido de una página web, como texto, imágenes, videos, entre otros. Es un estándar a cargo de la W3C, organización dedicada a la estandarización de casi todas las tecnologías ligadas a la web, sobre todo en lo referente a su escritura e interpretación.

[Más info](https://es.wikipedia.org/wiki/HTML)

## Estructura básica de un documento HTML


```html
<!DOCTYPE html>
<html>
  <head>
    <title>Título de la página</title>
  </head>
<body>

<h1>Esto es un título</h1>
<p>Esto es un párrafo</p>

</body>
</html>
```

(•ิ_•ิ)? SAY WHAT?

Ok, te explico un poco...

* La declaración ```DOCTYPE``` define el tipo de documento para ser HTML
* El texto entre ```<html>``` y ```</html>``` describe un documento HTML
* El texto entre ```<head>``` y ```</head>``` proporciona información sobre el documento
* El texto entre ```<title>``` y ```</title>``` ofrece un título para el documento
* El texto entre ```<body>``` y ```</body>``` describe el contenido de la página visible
* El texto entre ```<h1>``` y ```</h1>``` describe un título
* El texto entre ```<p>``` y ```</p>``` describe un párrafo

El uso de esta descripción, nuestro navegador web puede mostrar un documento con un encabezado y un párrafo.

> NOTA: Cuando hablamos de documentos nos referimos a nuestra página web ( ͡ᵔ ͜ʖ ͡ᵔ )

### Formato básico del texto

#### Títulos:

HTML acepta seis encabezados para definir la estructura jerárquica de los párrafos en un documento:

```html
<h1>Texto</h1>
<h2>Texto</h2>
<h3>Texto</h3>
<h4>Texto</h4>
<h5>Texto</h5>
<h6>Texto</h6>
```
Y tendremos algo así:

# Texto
## Texto
### Texto
#### Texto
##### Texto
###### Texto

#### Párrafos

Para incluir un párrafo dentro de nuestro documento solamente debemos incluir las siguiente etiquetas ```<p>``` y ```</p>``` ejemplo:

```html
<p> Esto es un texto de prueba </p>
```
Tendremos algo así:

Esto es un texto de prueba



