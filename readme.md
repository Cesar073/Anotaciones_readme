Este archivo es copia del readme.

Archivo para tener a mano sintáxis de markdown.
Está separado en 2 partes, la 1ra es código general de Markdown, la 2da es código que suma GitHub y sólo funciona en su web.

<!--
############################################################
                    MARKDOWN GENERAL
############################################################
-->


<!--
Para poder ver una preview del formato, seguir los siguientes pasos:
F1 -> Escribir: Markdown
Seleccionar la que dice: Markdown: Open Preview
-->

<!-- TÍTULOS -->
# Título H1
## Título H2
### Título H3
#### Título H4
##### Título H5
###### Título H6

### SALTO DE LÍNEA
El salto de línea es con br del html <br>
Pero si dejamos...

una línea entre textos, también se verá reflejada en el archivo final pero con una línea vacía, a diferencia del br que no tiene interlineado.

### FORMATEO DE TEXTO
*Esto es un texto en cursiva o itálica*<br>
**Esto es un texto en negrita**<br>
~~Esto es un texto tachado~~<br>
<span style="color:darkred">Esto es color darkred.</span>
<!--
Para ver todos los nombres de colores podemos visitar la siguiente web:
https://www.manualweb.net/html/colores-html/
-->
### LISTAS
Esto es una lista desordenada:
* item 1
* item 2

Esto es una lista ordenada:
1. item 1
2. item 2

Estos son listas añidadas:
1. Pasos
    * paso 1
    * paso 2
2. Herramientas
    * Herramienta 1
    * Herramienta 2
        <!-- Observar que genera letras y no números -->
        1. Uso tradicional
        2. Uso experto

### LINKS
[mi cuenta github](https://github.com/Cesar073)
<!-- Le agregamos el título que queremos que se vea al hacer hover-->
[mi cuenta github](https://github.com/Cesar073 "Cuenta de Cesar")

### CITAS
> Esto es una cita

### LÍNEAS HR
---
___

### CODIGO
`con 1 backtick tenemos una línea de código`
```
Con 3 backtick podemos
crear varias líneas de código.
```
Resaltamos las sintáxis según el lenguaje
```python
print("Hola mundo")
```
```javascript
console.log('hello world')
```
```html
<h1>Hello world<h1>
```

### TABLAS
Mantener ordenado con tabulaciones
|Col 1      |Col 2      | Col3      |
|-----------|-----------|-----------|
|fila 1     |fila 1     | fila 1    |
|fila 2     |fila 2     | fila 2    |

### IMAGENES
![logo python](https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg)

También se puede usar una imagen local colocando el path y agregar el texto de hover.
Por ejemplo, si estuviera al mismo nivel de carpetas que el que tenemos en el archivo readme, entonces sólo ponemos `![logo](image.png "Texto para el hover")` por ejemplo.<br>



<!--
############################################################
                    MARKDOWN GITHUB
############################################################
-->
### CHECKBOX
Podemos crear checkbox, con y sin tilde:
* [x] check con tilde
* [ ] check sin tilde

### EMOJIS
Ingresando a la siguiente web, podemos ver los emojis que se pueden utilizar en Github:
[emojis de Github](https://gist.github.com/rxaviers/7360908 "Emojis")
:octocat:
:cat2:

### MENCIONES
Si mencionamos a algún usuario, cuando se suba ésto al repositorio le llegará su notificación:
@nombre_usuario

### VIDEOS
El tutorial para ésta info lo saqué de éste video:
[Tutorial](https://www.youtube.com/watch?v=ssMNCIUPOLI "Tutorial")
1. Podemos subir el link de la forma tradicional:
    * `[Tutorial](https://www.youtube.com/watch?v=ssMNCIUPOLI "Tutorial")`
2. Para subir un video desde nuestra PC, tenemos que estar editando el readme dentro de GitHub y luego sólo hay que arrastrarlo al documento. No puede pesar más de 10mb, aunque dicho tamaño pudo haber cambiado. Esta modalidad permite que se reproduzca en la propia web de Github.
3. Video de youtube, no se reproduce pero nos coloca la miniatura del video y el logo de youtube, si hacemos clic nos redirige:
    * Escribir lo siguiente y cambiar el hash de youtube y obtener el link del mismo haciendo click en compartir:
    `[![](https://markdown-videos.deta.dev/youtube/<hash_video>)](link_youtube)`
    Ejemplo:
    [![](https://markdown-videos.deta.dev/youtube/ssMNCIUPOLI)](https://youtu.be/ssMNCIUPOLI)



