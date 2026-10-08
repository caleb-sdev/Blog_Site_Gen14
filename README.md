## Estructura del proyecto

## Tecnologias usadas HTML + CSS + Boostrap

Blog_Site_Gen14
|
|-index.html
|-css
|   |_ styles.css
|-images
    |_cat_play*.jpeg
    |_cat_sleep.jpeg
    |_cat_windows.jpg

# se usa boilerplate para tener la estructura basisca de HTML

## Se estara usando CDN 
Dentro del <head>

<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
  rel="stylesheet"
>

# antes de cerrar el </body>

<script
  src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js">
</script>


# Explicacion de cada segmento (Body)
# Estructura general
    <nav>
    |_<div class="container">
        |_<a class="navbar-toggler">
        |_<button class="navbar-toogler">
        |       |_<span class="navbar=togler-icon">
        |_<div class="collapse navbar-collapse">
                |_<ul class="navbar-nav">
                |_<li>
                |   |_<a>Inicio</a>
                |_<li>
                |   |_<a>Articulo</a>
                |_<li>
                    |_<a>Quienes Somos</a>

El <nav>
Es una etiqueta HTML que representa la zona de navegacion, pero las clases viene de Bootstrap
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
- navbar
    Le dice a Bootstrap:
        "Este es un elemento de barra de navegacion"
    Bootstrap le aplica estilos especiales.
- navbar-expand-lg
    Esta clase hace la navbar sea responsive (Adaptar a la pantalla) (lg = large)
- navbar-dark
    Le indica a Bootstrap que utilizaremos un tema oscuro
- bg-dark
    Fondo oscuro, la barra aparece negra.

El <div>
<div class="container">
div es un contenedor genérico de HTML.
container sirve para colocar el contenido dentro de un ancho adecuado y dejar márgenes laterales.

El <a>
<a class="navbar-brand" href="#">🐱 Mundo Gato</a>
Aquí tenemos un enlace:
<a>
a significa anchor (ancla) y se utiliza para crear enlaces.
<a href="https://google.com">Google</a>

- navbar-brand
    class="navbar-brand"
    Esta clase de Bootstrap indica:
    "Este es el nombre o logo principal de la página."
- href
    href="#"
    href indica a dónde lleva el enlace.

# ahora
<button
    class="navbar-toggler"
    type="button"
    data-bs-toggle="collapse"
    data-bs-target="#menu"
>
    <span class="navbar-toggler-icon"></span>
</button>

- navbar-toggler
    class="navbar-toggler"
    Esta clase le dice a Bootstrap:
    "Este botón es el botón que abre/cierra el menú de navegación."

- data-bs-toggle="collapse"
    Le dice a Bootstrap:
    "Este botón va a controlar un elemento que puede abrirse y cerrarse."
    collapse significa colapsar/contraer.

- data-bs-target="#menu"
    Esto le dice:
    "Cuando hagan clic en este botón, quiero controlar el elemento cuyo ID es menu."

El <span>
<span class="navbar-toggler-icon"></span>
span es un elemento HTML que normalmente se utiliza para envolver pequeños fragmentos de contenido.
    - navbar-toggler-icon
        |_muestra el icono de menu


