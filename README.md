# htmlPrueba
Prueba de código html
<!DOCTYPE html>
<html lang="es">
<head> <!-- Encabezado del Documento-->
    <meta charset="UTF-8">  <!--Define la codificación de caracteres del documento.-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"><!--Hace que la página sea responsive (adaptable a diferentes tamaños de pantalla).-->
    <title>Página de Aprendizaje HTML</title> <!--Título que aparece en la pestaña del navegador.-->
</head>
<body>  <!-- Cuerpo del Documento-->
    <header> <!-- Contiene el encabezado principal de la página, con un título `<h1>`.-->
        <h1>Bienvenido a mi Página de Aprendizaje HTML</h1>
    </header>

    <nav> <!--  Barra de navegación con enlaces a diferentes secciones de la página.-->
        <ul>
            <li><a href="#sobre-mi">Sobre Mí</a></li>
            <li><a href="#hobbies">Mis Hobbies</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>

    <section id="sobre-mi"> 
        <h2>Sobre Mí</h2>
        <p>Hola, soy un aprendiz de HTML y esta es mi primera página web. Estoy emocionado de aprender más sobre desarrollo web.</p>
    </section> <!-- Secciones individuales con contenido específico. Cada sección tiene un identificador (`id`) para ser enlazada desde la navegación.-->

    <section id="hobbies">
        <h2>Mis Hobbies</h2>
        <p>Algunos de mis hobbies incluyen:</p>
        <ul>
            <li>Programación</li>
            <li>Leer libros</li>
            <li>Jugar videojuegos</li>
        </ul>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Puedes contactarme a través de las siguientes redes sociales:</p>
        <ul>
            <li><a href="https://twitter.com">Twitter</a></li>
            <li><a href="https://facebook.com">Facebook</a></li>
            <li><a href="https://linkedin.com">LinkedIn</a></li>
        </ul>
    </section>

    <footer> <!-- Pie de página con información de copyright.-->
        <p>&copy; 2024 Mi Página de Aprendizaje HTML</p>
    </footer>
</body>
</html>

<!-- Elementos Comunes-->
  <!--  Encabezados (`<h1>`, `<h2>`): Utilizados para títulos y subtítulos.-->
  <!--  Párrafos (`<p>`): Para bloques de texto.-->
  <!--  Listas (`<ul>`, `<li>`): Para listas de elementos.-->
  <!--  Enlaces (`<a href="URL">Texto</a>`): Para crear hipervínculos.-->

<!-- Este ejemplo es un buen punto de partida para un aprendiz y cubre las estructuras y elementos más básicos del HTML.-->
