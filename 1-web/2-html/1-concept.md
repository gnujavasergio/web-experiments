# HTML
## HTML - Hypertext Markup Language
- Referencia de html [https://htmlreference.io/](https://htmlreference.io/)
- No es un lenguaje de programación pero si es un lenguaje de marcado para hacer paginas web.
- Determina el contenido: texto, imagenes, videos, enlaces.
- Se tiene muchos elementos para marquetar la pagina web.
- En un documento HTML se lo puede escribir en cualquier editor de texto simple.
- El navegador web, busca el codigo HTML para mostrar el contenido.

### Sifnificado
- Hiper: Significa enlace, que permite pasar de una pagina a otra.
- Text: Texto que se escribira
- Markup: Como se muestra el texto
- Language: Se lo utilizo para completar.

## Anatomia de un elemento HTML
```html
<!-- Elemento-->
<etiqueta-apertura atributo="valor">contenido</etiqueta-cierre>

<h1 class="title">Contenido</h1> 

<!-- Elementos vacios -->
<!-- alt sirve para tener accesibilidad-->
<img src="logo.png" alt="Logo">
```

## Anatomia de un documento HTML
- Todos los elementos en HTML son una caja.
```html
<!DOCTYPE html>
<!-- html es la etiqueta principal-->
<html lang="en">
<!-- Etiqueta especial el contenido escrito en su interior no se muestra en la pagina web-->
<head>
    <!-- Se añade cualquier otra instrucción que se desee dar al navegador -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Titulo de la pagina web que se muestra en la pestaña del navegador-->
    <title>Document</title>
</head>
<!-- body es la etiqueta donde se muestra el contenido que se muestra o es visible en la web-->
<body>
    <h1>Hola Mundo</h1>
    <p>Este es un parrafo </p>
    <div>
        <p>Esta es una caja</p>
    </div>
</body>
</html>
```

## Etiquetas semanticas
- `<header></header`: Etiqueta para definar la cabecera para colocar a veces logo, menu de navegacion.
- `<nav></nav>`: Etiqueta para colocar los enlaces de navegación
- `<article></article>`: Etiqueta que se usa normalmente para colocar contenido que puede ser independiente.
- `<section></section>`: Etiqueta se usa para colocar las secciones de nuestra pagina: Listas, tendencias
- `<aside></aside>`: Etiqueta que se usa para agregar publicidad y si se la elimina no afecta a la pagina
- `<footer></footer>`: Etiqueta que esta en la parte final de nuestra pagina y donde se coloca la informacion de nosotros que necesitara el usuario.
- `<h1></h1 ... <h6></h6>`: Etiqueta para añadir titulos del mas importante al menos importante.
- [Ejempo1](../projects/ejemplo1/index.html)

## Debug
- Para poder validar codigo HTML y que se esta siguiendo correctamente el codigo.
    - Validar por URI
    - Validar subiendo un archivo
    - Validar director copiando y pegando el codigo HTML.
- [https://validator.w3.org/](https://validator.w3.org/)
