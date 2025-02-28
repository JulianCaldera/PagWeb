# PagWeb


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BIOTECH</title>
    <link rel="stylesheet" href="Inicio.css">
</head>
<body>
    <!-- Header que contiene el logo y el menú -->
    <header>
        <!-- Logo a la izquierda -->
        <div class="logo">
            <img src="/BioTech/Proyectos de interés/imagenes-pdi copy/Logo BioTech.PNG" alt="Logo de BioTech">
        </div>

        <!-- Menú (inicialmente oculto) -->
        <nav class="menu">
            <ul>
                <li><a href="/BioTech/Inicio/Inicio.html">Inicio</a></li>
                <li><a href="/BioTech/Proyectos de interés/pdi.html">Proyectos de interés</a></li>
                <li><a href="/BioTech/Participar/participar.html">Trabaja en un proyecto</a></li>
                <li><a href="/BioTech/Financiar/financiar.html">Financiar</a></li>
            </ul>
        </nav>

        <!-- Botón para abrir y cerrar el menú -->
        <div class="menu-toggle" onclick="toggleMenu()">☰</div>
    </header>

    <div class="banner">
        <img src="/BioTech/Proyectos de interés/imagenes-pdi copy/Logo BioTech.PNG" alt="">
        <br>
        <br>
    </div>
    <div class="container">
        <div class="image">
            <img src="imagen/image.png" alt="Imagen de ciudad">
        </div>
        <div class="content">
            <h2>SOBRE NOSOTROS:</h2> <br>
            <h3>MISIÓN</h3>
            <p>Facilitar la conexión entre emprendedores e inversores para impulsar proyectos con impacto social <br> 
                y ambiental, brindando visibilidad, apoyo e inversión a iniciativas sostenibles.</p>
            <h3>VISIÓN</h3>
            <p>Ser la plataforma líder en colaboración e inversión para proyectos que transformen el mundo, <br> 
                promoviendo un futuro más justo, equilibrado y sostenible.</p>
        </div>
    </div>
    <br><br>
    <br><br>

    <div class="projects-section">
        <div class="project-box">
            <h2> EXPLORAR PROYECTOS:</h2>
            <br><br>
            <p>Explora proyectos innovadores, conecta con emprendedores y encuentra oportunidades de inversión o colaboración. Nuestra plataforma te permite descubrir ideas frescas con gran potencial. ¡No pierdas la oportunidad de ser parte del futuro y hacer crecer grandes proyectos desde su inicio!</p>
            <p><strong>Únete hoy y sé parte del cambio.</strong></p>
            <a href="/BioTech/Proyectos de interés/pdi.html" class="project-button">EXPLORAR</a>
        </div>
        <div class="project-box">
            <h2>PUBLICAR UN PROYECTO:</h2>
            <br><br>
            <p>¿Tienes un proyecto en mente? ¡No esperes más para hacerlo realidad! Publica con nosotros y consigue la visibilidad que necesitas para llegar a más personas, aumentar tu impacto y ver cómo tu idea crece. ¡Es el momento perfecto para dar el siguiente paso y hacer que tu proyecto destaque!</p>

            <a href="/BioTech/Publicar/escrito.html" class="project-button">PUBLICAR</a>
        </div>
    </div>  


    <!-- Espaciador para separar secciones -->
<div class="espaciador"></div>

<!-- Sección de recomendaciones -->
<section class="recomendaciones">
    <h2 class="titulo">RECOMENDACIONES</h2>
    
    <div class="contenedor-recomendaciones">
        <!-- Testimonio 1 -->
        <div class="testimonio">
            <img src="imagen/mujer 1.jpg" alt="Mariana Sanchez">
            <h3 class="nombre">MARIANA SANCHEZ</h3>
            <p class="rol">Colaborador del proyecto “Educa tu país”</p>
            <p class="comentario">
                «Estoy muy feliz de haber encontrado esta oportunidad. Desde que comencé a buscar trabajo como profesora, este proyecto me dio la oportunidad que tanto necesitaba para crecer y enseñar.»
            </p>
            <div class="estrellas">★★★★★</div>
        </div>

        <!-- Testimonio 2 -->
        <div class="testimonio">
            <img src="imagen/hombre.jpg" alt="Miguel Torres">
            <h3 class="nombre">MIGUEL TORRES</h3>
            <p class="rol">Inversionista del proyecto “Tecnología e innovación”</p>
            <p class="comentario">
                «Invertir en este proyecto ha sido una gran decisión. He visto un retorno significativo y un impacto positivo. Es una oportunidad de crecimiento y rentabilidad.»
            </p>
            <div class="estrellas">★★★★★</div>
        </div>

        <!-- Testimonio 3 -->
        <div class="testimonio">
            <img src="imagen/mujer 2.jpg" alt="Carla Orozco">
            <h3 class="nombre">CARLA OROZCO</h3>
            <p class="rol">CEO del proyecto “Conmoviendo hogares”</p>
            <p class="comentario">
                «Invertir en este proyecto ha sido una gran decisión. He visto un retorno significativo y un impacto positivo. Es una oportunidad de crecimiento y rentabilidad.»
            </p>
            <div class="estrellas">★★★★★</div>
        </div>
    </div>
</section>


    <footer class="footer">                                                                                                         
        <div class="footer-info">
            <div class="contacto">
                <h2>Contacto</h2>
                <p>Dirección: Carrera 45 #75B Sur 120, Sabaneta, Antioquia.</p>
                <p>Email: contacto@biotech.com</p>
                <p>Teléfono: +57 305 297 9679</p>
            </div>
            <div class="redes-sociales">
                <h2>Síguenos</h2>
                <a href="https://facebook.com" target="_blank" class="social-icon"><i class="fab fa-facebook"></i> Facebook</a>
                <a href="https://instagram.com" target="_blank" class="social-icon"><i class="fab fa-instagram"></i> Instagram</a>
            </div>
        </div>

        <!-- Logo de BioTech en el footer -->
        <div class="logo">
            <img src="/BioTech/Proyectos de interés/imagenes-pdi copy/Logo BioTech.PNG" alt="Logo de BioTech">
        </div>
    </footer>

    <!-- Aquí iría el JavaScript para el menú desplegable -->

    <script src="inicio.js"></script>
</body>
</html>
