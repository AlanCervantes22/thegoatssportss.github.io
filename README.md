# thegoatssportss.github.io
tienda de deportes online
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Deportes - THE GOATS SPORT</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        /* General */
        body {
            font-family: Arial, sans-serif;
        }

        /* Navegación */
        .navbar-brand {
            font-weight: bold;
            font-size: 1.5em;
        }

        /* Logotipo */
        .navbar-logo {
            max-height: 100px; /* Ajusta el tamaño del logo */
        }

        /* Sección Inicio */
        #inicio {
            padding: 2em 0;
        }

        #inicio h1 {
            font-size: 2.5em;
            font-weight: bold;
        }

        #inicio p {
            font-size: 1.2em;
        }

        /* Sección Quiénes Somos */
        #nosotros img {
            border-radius: 5px;
            margin-top: 10px;
        }

        /* Sección Productos */
        #productos img {
            border-radius: 5px;
            margin-top: 10px;
        }

        #productos p {
            font-weight: bold;
        }

        /* Footer */
        footer {
            font-size: 0.9em;
        }
    </style>
</head>
<body>

<!-- Navegación -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <!-- Logo de la tienda -->
    <a class="navbar-brand" href="#">
        <img src="https://www.example.com/path/to/logo20.jpeg" alt="Logotipo" class="navbar-logo">
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item"><a class="nav-link" href="#inicio">Inicio</a></li>
            <li class="nav-item"><a class="nav-link" href="#nosotros">¿Quiénes Somos?</a></li>
            <li class="nav-item"><a class="nav-link" href="#productos">Productos</a></li>
            <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
        </ul>
    </div>
</nav>

<!-- Sección Inicio -->
<section id="inicio" class="container my-5">
    <h1 class="text-center">Bienvenidos a THE GOATS SPORT</h1>
    <p class="text-center">Somos una tienda especializada en el más grande deporte del mundo, el fútbol. Encontrarás los mejores productos de la más alta calidad.</p>
    <p class="text-center font-italic">"Deporte para campeones, productos para leyendas"</p>
</section>

<!-- Sección Quiénes Somos -->
<section id="nosotros" class="container my-5">
    <h2 class="text-center">¿Quiénes Somos?</h2>
    <div class="row">
        <div class="col-md-4"><img src="https://www.example.com/images/socio1.jpg" class="img-fluid" alt="Deporte 1"></div>
        <div class="col-md-4"><img src="https://www.example.com/images/socio2.jpeg" class="img-fluid" alt="Deporte 2"></div>
    </div>
    <p class="text-center mt-3">Somos dos socios que compartimos la pasión por el deporte y decidimos crear esta tienda para que más personas compartan nuestra pasión.</p>
</section>

<!-- Sección Productos -->
<section id="productos" class="container my-5">
    <h2 class="text-center">Nuestros Productos</h2>
    <div class="row">
        <div class="col-md-3">
            <img src="https://th.bing.com/th/id/OIP.qQSC1LfGo6u6o6ukG5QwNgAAAA?rs=1&pid=ImgDetMain" class="img-fluid" alt="Balon adidas">
            <p class="text-center">Balón ADIDAS UEFA CHAMPIONS LEAGUE 2017/18 $599</p>
        </div>
        <div class="col-md-3">
            <img src="https://media.futbolmania.com/media/catalog/product/cache/1/thumbnail/9df78eab33525d08d6e5fb8d27136e95/c/q/cq7147-100-5_imagen-del-balon-de-futbol-nike-flight-premier-league-2020-2021-blanco_1_frontal.jpg" class="img-fluid" alt="Balon nike">
            <p class="text-center">Balón NIKE Premier League 2020/21 $400</p>
        </div>
        <div class="col-md-3">
            <img src="https://files.merca20.com/uploads/2023/06/Captura-de-Pantalla-2023-06-13-a-las-12.48.58.png" class="img-fluid" alt="Balon Voit">
            <p class="text-center">Balón VOIT Liga MX 2023 $399</p>
        </div>
        <div class="col-md-3">
            <img src="https://img.planetafobal.com/2024/02/puma-cumbre-libertadores-sudamericana-2024-pelota-oficial.webp" class="img-fluid" alt="Balón puma">
            <p class="text-center">Balón PUMA Copa Libertadores 2024 $499</p>
        </div>
        <div class="col-md-3">
            <img src="https://img.planetafobal.com/2023/06/cruz-azul-jersey-2023-2024-pirma-visita-zaq.webp" class="img-fluid" alt="Playera Cruz Azul">
            <p class="text-center">Playera Cruz Azul 2023/24 $1,399</p>
        </div>
        <div class="col-md-3">
            <img src="https://th.bing.com/th/id/R.a869a330391e1a9d83570a1beb17a1d4?rik=0QbjHfyllmrEAA&riu=http%3a%2f%2fwww.footkorner.com%2fcdn%2fshop%2ffiles%2ffootkorner-maillot-domicile-real-madrid-2023-2024-blanc-bleu-orange_2.png%3fv%3d1687248001&ehk=%2bjpL8wh0pn7FFycf41A%2bGrtmOqEoxQTIC6NGiOSFtSI%3d&risl=&pid=ImgRaw&r=0" class="img-fluid" alt="Playera Real Madrid">
            <p class="text-center">Playera Real Madrid 2024 $1,999</p>
        </div>
        <div class="col-md-3">
            <img src="https://theshoppies.pk/wp-content/uploads/2023/01/Al-Nassar-Ronaldo-Shirt-2023.jpg" class="img-fluid" alt="Playera Al-Nassar Ronaldo 2023">
            <p class="text-center">Playera Al-Nassar Ronaldo 2023 $1,399</p>
        </div>
        <div class="col-md-3">
            <img src="https://th.bing.com/th/id/OIP.mlmzHenrFeUZAZpjYr6gtwHaHa?rs=1&pid=ImgDetMain" class="img-fluid" alt="Playera Manchester City">
            <p class="text-center">Playera Manchester City 2024 $1,899</p>
        </div>
        <div class="col-md-3">
            <img src="https://http2.mlstatic.com/tacos-nike-mercurial-cr7-75-mx-envio-gratis-D_NQ_NP_779696-MLM27951491988_082018-F.jpg" class="img-fluid" alt="Tacos Nike CR7">
            <p class="text-center">Tacos NIKE MERCURIAL CR7 $3,500</p>
        </div>
        <div class="col-md-3">
            <img src="https://www.futbolemotion.com/imagesarticulos/188221/grandes/bota-adidas-x-speedportal-messi-.1-fg-solar-orange-silver-met.-core-black-0.jpg" class="img-fluid" alt="Tacos Adidas Messi">
            <p class="text-center">Tacos Adidas Speedportal Messi $3,500</p>
        </div>
    </div>
</section>

<!-- Sección de Contacto -->
<section id="contacto" class="container my-5">
    <h2 class="text-center">Contacto</h2>
    <form class="mx-auto d-block" style="max-width: 600px;">
        <div class="form-group">
            <label for="nombre">Nombre</label>
            <input type="text" class="form-control" id="nombre" placeholder="Introduce tu nombre">
        </div>
        <div class="form-group">
            <label for="email">Correo Electrónico</label>
            <input type="email" class="form-control" id="email" placeholder="Introduce tu correo electrónico">
        </div>
        <div class="form-group">
            <label for="mensaje">Mensaje</label>
            <textarea class="form-control" id="mensaje" rows="4" placeholder="Escribe tu mensaje"></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Enviar</button>
    </form>
</section>

<!-- Footer -->
<footer class="text-center py-4">
    <p>&copy; 2024 THE GOATS SPORT. Todos los derechos reservados.</p>
</footer>

<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

</body>
</html>
