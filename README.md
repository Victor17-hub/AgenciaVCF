# AgenciaVCF
<!DOCTYPE html>
<html lang="es">
<head>
    <title>Agencia de Viajes | VCF</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie-edge">

    <!--Estilos-->
    <link rel="stylesheet" href="estilos.css">
    <link href="https://fonts.googleapis.com/css?family=Raleway&display=swap" rel="stylesheet">
</head>
<body>

    <!-- Ir arriba -->
    <div class="go-top">
        <span><i class="fas fa-angle-up"></i></span>
    </div>
    

    <!--Menu de navegacion-->
        <header id="header">
            <nav class="menu">
                <div class="logo-box">
                    <h1><a href="#">Agencia VCF</a></h1>
                    <span class="btn-menu"><i class="fas fa-bars"></i></span>
                </div>

                <div class="list-container">
                    <ul class="lists">
                        <li><a href="#" class="activo">Inicio</a></li>
                        <li><a href="#">Nosotros</a></li>
                        <li><a href="../Agencia/Viajes/Viajes.html">Servicios</a></li>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">Contacto</a></li>
                    </ul>
                </div>
            </nav>

            <!--IMG Header-->
            <div class="img-header">
                <div class="welcome">
                    <h1>Bienvenidos Aventureros</h1>
                    <hr>
                    <p>Agencia de Viajes</p>
                    <button id="abajo">Ver abajo</button>
                </div>
            </div>

        </header>
    <!--Menu de navegacion-->

   <main>

    <!--Acerca de nosotros-->
    <section class="acerca-de">
        <div class="info-container">
            <h1>Acerca de nosotros</h1>
            <p>Somos una empresa aventurera, que nos gustan los sitios exoticos, deserticos y cualquier sitio en el que podamos disfrutar del paisaje.</p>
         <div class="about-gallery">
            <img class="img1" src="../Agencia/bahamas.jpg" alt="">
            <img class="img1" src="../Agencia/egipto.jpg" alt="">
            <img class="img1" src="../Agencia/sahara.jpg" alt="">
         </div>
         
         <div class="about-more"><button>Leer mas</button></div>

        </div>
    </section>

    <!--Nuestros proyectos-->
    <section class="our-projects">
        <div class="deg-background"></div>

        <div class="ejeZproject">
            <div class="container-project">
                <div class="project-title">
                    <h2>Nuestros Viajes</h2>
                    <hr>
                </div>

                <div class="project-img">
                    <img class="img2" src="../Agencia/budapest.jpg" alt="">
                    <img class="img2" src="../Agencia/cancun.jpg" alt="">
                    <img class="img2" src="../Agencia/japon.jpg" alt="">
                    <img class="img2" src="../Agencia/madrid.jpg" alt="">
                    <img class="img2" src="../Agencia/santamonica.jpg" alt="">
                    <img class="img2" src="../Agencia/venecia.jpg" alt="">
                </div>
            </div>
        </div>
    </section>

    <!--Testimonios-->
    <section class="testimonio">
        <div class="testimonio-title">
            <h2>Testimonios</h2>
            <hr>
        </div>

        <div class="box-testimonio">
            <div class="card-testimonio">
                <div class="card-img"><img src="../Agencia/mujer.jpg" alt=""></div>
                <div class="testimonio-text">
                    <h4>Raquel Jimenez</h4>
                    <p>Compre un billete para ir a Japon y estoy muy contenta con el trato recibido. No he tenido ningun tipo de problema.</p>
                </div>
            </div>

            <div class="card-testimonio">
                <div class="card-img"><img src="../Agencia/hombre.jpg" alt=""></div>
                <div class="testimonio-text">
                    <h4>Bruno Fernandez</h4>
                    <p>Bastante bien en aspectos generales, pero mejoraria el tiempo de confirmacion del viaje.</p>
                </div>
            </div>

            <div class="card-testimonio">
                <div class="card-img"><img src="../Agencia/mujer2.jpg" alt=""></div>
                <div class="testimonio-text">
                    <h4>Sara Lopez</h4>
                    <p>Hay ofertas muy asequibles y de buena calidad. Compre un viaje a Budapest por un precio bastante atractivo.</p>
                </div>
            </div>
        </div>

    </section>

</main>

<!--Footer-->
<footer class="footer">
    <div class="deg-footer"></div>

    <div class="ejeZfooter">
        <div class="footer-content">
        <div class="footer-title">
            <h2>Formulario de contacto</h2>
            <hr>
        </div>

        <div class="formulario-content">
            <form id="formulario">
                <label for="user">Nombre:</label>
                <input type="text" id="user" name="user" placeholder="Ingresa tu nombre">

                <label for="email">Correo Electronico:</label>
                <input type="email" id="email" name="email" placeholder="Ingresa tu Correo Electronico">

                <label for="mensaje">Escribe tu mensaje:</label>
                <textarea name="mensaje" id="mensaje"></textarea>

                <div class="send"><button>Enviar</button></div>

                <div class="mensaje-form">
                    <p>Escribenos un mensaje, con gusto tendras una respuesta de nuestra parte en poco tiempo. </p>
                </div>
            </form>
        </div>

        <div class="footer-text">
            <p>&copy; Agencia VCF - 2020 | Todos los derechos reservados</p>
        </div>

        </div>
    </div>
</footer>

<!--Scripts-->
<script src="https://kit.fontawesome.com/35db202371.js"></script>
<script src="app.js"></script>

</body>
</html>
